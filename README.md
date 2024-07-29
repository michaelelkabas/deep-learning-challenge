# deep-learning-challenge

The nonprofit foundation Alphabet Soup wants a tool that can help it select the applicants for funding with the best chance of success in their ventures. With your knowledge of machine learning and neural networks, you’ll use the features in the provided dataset to create a binary classifier that can predict whether applicants will be successful if funded by Alphabet Soup.

From Alphabet Soup’s business team, you have received a CSV containing more than 34,000 organizations that have received funding from Alphabet Soup over the years. 

# Alphabet Soup Charity Funding Predictor

This project aims to predict the success of charity funding applications using a neural network model. The model is built using TensorFlow and Keras and is trained on a dataset of historical charity funding applications.

## Overview

The goal of this project is to create a binary classification model that can predict whether an Alphabet Soup-funded organization will be successful based on the features in the dataset.

## Data Preprocessing

- **Target Variable:** `IS_SUCCESSFUL`
- **Features:**
  - `STATUS`
  - `ASK_AMT`
  - `APPLICATION_TYPE_T10`
  - `APPLICATION_TYPE_T19`
  - `APPLICATION_TYPE_T3`
  - `APPLICATION_TYPE_T4`
  - `APPLICATION_TYPE_T5`
  - `APPLICATION_TYPE_T6`
  - `APPLICATION_TYPE_T7`
  - ... (include all other relevant features)
- **Variables Removed:** Any variables not contributing to the target or features, such as identifiers or non-informative columns.

## Model Architecture

- **First Hidden Layer:**
  - Units: 80
  - Activation: ReLU
  - Regularization: L2
- **Second Hidden Layer:**
  - Units: 30
  - Activation: ReLU
  - Regularization: L2
- **Output Layer:**
  - Units: 1
  - Activation: Sigmoid

## Training and Evaluation

The model is compiled and trained using the Adam optimizer and binary cross-entropy loss. The model is evaluated on the test data to determine its loss and accuracy.

## Results

- **Test Accuracy:** 1.0
- **Test Loss:** 0.0065

## Improvements

Several techniques were attempted to improve the model performance:
- Adjusting the number of neurons in hidden layers.
- Adding or removing hidden layers.
- Applying dropout and L2 regularization.
- Tuning the learning rate and number of epochs.

## Google Colab Notebook

The project and model training can also be run in Google Colab. You can access the Colab notebook using the following link:
[Google Colab Notebook](https://colab.research.google.com/drive/1RWHaMRxlmi3aXZ8m5OyTNMOzEO0NpiTm#scrollTo=QiQ9gYLc3SRt)


