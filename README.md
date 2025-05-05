# Text-Classification-System
This project implements a binary text classification pipeline using:
  1. Hugging Face Transformers for tokenization
  2. Sentence Transformers for generating sentence embeddings
  3. PyTorch for building and training a Multi-Layer Perceptron (MLP) classifier

The pipeline includes data preprocessing, model training, evaluation, and visualization of results.

MLP Classifier: Constructs a simple neural network with:
  1. Input layer
  2. Hidden layer with 64 neurons and ReLU activation
  3. Output layer with sigmoid activation for binary classification

Training:
  1. Loss Function: Binary Cross-Entropy Loss
  2. Optimizer: Adam

Evaluation:
  1. Confusion matrix
  2. Classification report
  3. Training and validation loss and accuracy curves


