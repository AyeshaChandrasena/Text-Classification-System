# Text-Classification-System
This project implements a binary text classification pipeline using:
  1. Hugging Face Transformers for tokenization
  2. Sentence Transformers for generating sentence embeddings
  3. PyTorch for building and training a Multi-Layer Perceptron (MLP) classifier

The pipeline includes data preprocessing, model training, evaluation, and visualization of results.

MLP Classifier: Constructs a simple neural network with:

 Input layer
 Hidden layer with 64 neurons and ReLU activation
 Output layer with sigmoid activation for binary classification

Training:

  Loss Function: Binary Cross-Entropy Loss
  Optimizer: Adam

Evaluation:

  Accuracy calculation
  Confusion matrix
  Classification report
  Training and validation loss and accuracy curves


