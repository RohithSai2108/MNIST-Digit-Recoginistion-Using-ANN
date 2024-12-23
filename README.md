# MNIST-Digit-Recoginistion-Using-ANN
This repository demonstrates handwritten digit recognition using an Artificial Neural Network (ANN) on the MNIST dataset. The goal is to classify images of digits (0-9) by training a neural network model implemented using TensorFlow/Keras.

## Overview:
The MNIST dataset is a standard benchmark for machine learning and computer vision tasks.

This project involves:

## Preprocessing the MNIST dataset.
Building and training an Artificial Neural Network (ANN) for digit classification.
Evaluating the model's performance and visualizing predictions.

## Dataset
The MNIST dataset contains:
60,000 training images and 10,000 test images.
Grayscale images of size 28x28 pixels, each representing a single digit (0-9).

### Project Features
### Data Preprocessing:
Normalization and reshaping of images for model input.
### ANN Model:
Input layer: Flattened 28x28 images.

Hidden layers: Fully connected layers with ReLU activation.

Output layer: Softmax activation for 10 classes.

Training: Optimization using Adam and cross-entropy loss.

Evaluation: Metrics include accuracy and loss.

Visualization: Display of training performance and predictions on test images.

### Dependencies
Python 3.7+

TensorFlow/Keras

NumPy

Matplotlib
