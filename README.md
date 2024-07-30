*Text Generation AI - Next Word Prediction in Python*

This repository contains a Python project that demonstrates how to predict the next word in a given text sequence using an LSTM (Long Short-Term Memory) model. The model is trained on a sequence of words to learn the context and predict the most likely next word in the sequence.

Features

Tokenizes text using regular expressions.

Creates input and output sequences for training.

Builds and trains an LSTM model using Keras.

Predicts the next word in a given text sequence.

Requirements

Python 3.x

numpy

nltk

tensorflow

Usage

Tokenize text and create sequences:

The script tokenizes text using a regular expression pattern and creates input-output sequences for training the model.

Train the model:

The script defines an LSTM model, compiles it with the RMSprop optimizer, and trains it on the tokenized text sequences.

Predict the next word:

Use the predict_next_word function to predict the next word in a given text sequence.

