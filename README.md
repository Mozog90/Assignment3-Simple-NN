# AI-ML-Assignment-3-Simple-NN

**Name:** Mateusz Ozog  
**Course:** AD 331  
**Framework:** scikit-learn  

## Overview
This assignment builds a simple **feedforward neural network (FNN)** to classify handwritten digits (0–9) using the MNIST dataset.

## Dataset
- MNIST handwritten digits
- Images are 28x28 grayscale
- Each image is flattened into 784 input features

## Data Preparation
- Pixel values normalized from 0–255 to 0–1
- Data split into training and testing sets (80/20)
- One-hot encoding demonstrated for labels

## Model
- Feedforward neural network using `MLPClassifier`
- Two hidden layers:
  - 128 neurons (ReLU)
  - 64 neurons (ReLU)
- Optimizer: Adam
- Training iterations: 10

## Resu74696 (varies slightly per run)

## Demo
The notebook includes:
- Final evaluation on the test set
- Confusion matrix visualization
- Prediction on a randomly selected test image
