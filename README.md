# News-groups
# Text Classification with Naive Bayes

This repository contains a Python implementation for text classification using the Naive Bayes algorithm.

## Description

The project involves:
- Loading the 20 Newsgroups dataset using scikit-learn.
- Preprocessing the text data, including converting to lowercase, removing punctuation and digits, tokenizing, lemmatizing, removing stopwords, and performing part-of-speech tagging.
- Splitting the dataset into training and testing sets.
- Converting text documents into a numerical feature matrix using TF-IDF (Term Frequency-Inverse Document Frequency) vectorization.
- Training a Multinomial Naive Bayes classifier on the training data.
- Evaluating the model's performance on the testing data.

## Requirements

- pandas
- scikit-learn
- nltk

## Usage

1. Clone this repository to your local machine.
2. Make sure you have the required dependencies installed.
3. Run the provided Python script.
