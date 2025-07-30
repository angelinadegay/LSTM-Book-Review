# LSTM-Book-Review

This project was completed as part of the Break Through Tech (BTT) AI program, where I explored different approaches to text classification using a real-world book review dataset.

## Project Overview
The goal was to classify text reviews as positive or negative sentiment using two different NLP pipelines:

LSTM-based model that captures word order and sequential dependencies.

TF-IDF + Feedforward Neural Network as a baseline for comparison.

I evaluated both models across accuracy, precision, recall, and F1-score — and uncovered some surprising insights about how simpler models can outperform more complex ones on smaller datasets.

## Key Details
Dataset: Preprocessed book review text

Models: Bidirectional LSTM, TF-IDF + Dense NN

Optimizer: SGD (learning rate = 0.1)

Loss: Binary Cross-Entropy

Evaluation: Accuracy, Precision, Recall, F1-score

## What I Learned
Tokenization and padding for sequential models

Importance of evaluation metrics beyond accuracy

When simpler models like TF-IDF can outperform LSTM

Practical experience implementing deep learning pipelines in Keras
