# Sentiment Detection Using Deep Learning

This project implements sentiment detection using a Recurrent Neural Network (RNN) with TensorFlow/Keras. The model is trained on the IMDB movie reviews dataset to classify text sentiment as positive or negative.

## Project Overview

The project demonstrates:
- Text preprocessing using Keras Tokenizer
- Sequence padding for uniform input lengths
- Implementation of a Simple RNN model
- Binary sentiment classification

## Dependencies

- TensorFlow
- Keras
- NumPy

## Model Architecture

The model consists of:
1. A SimpleRNN layer with 32 units
2. A Dense output layer with sigmoid activation for binary classification

Model summary:
- Total parameters: 1,121
- All parameters are trainable
- Input shape: (50, 1)
- Output shape: (None, 1)

## Dataset

The project uses two datasets:
1. A small sample dataset for tokenization demonstration
2. The IMDB movie reviews dataset for sentiment analysis training
   - 25,000 training samples
   - 25,000 test samples

## Implementation Details

1. Text Preprocessing:
   - Tokenization of text data
   - Converting text to sequences
   - Padding sequences for uniform length

2. Model Training:
   - Binary cross-entropy loss
   - Adam optimizer
   - Accuracy metric
   - 100 epochs with validation

## Usage

The code is provided in a Jupyter notebook format (.ipynb) and can be run in environments like Google Colab or local Jupyter installations.

## Performance

The model's performance metrics include:
- Training accuracy
- Validation accuracy
- Training loss
- Validation loss

 
