# Abalone Rings Prediction

Deep learning regression project for predicting abalone shell rings from physical measurements using PyTorch.

## Project Overview
This project studies how neural network size affects regression performance on the Abalone dataset.

Four feed-forward neural network architectures were trained under the same training conditions while varying the number of neurons in the hidden layers.

## Data Preparation
The preprocessing workflow included:
- One-hot encoding for categorical features
- Standardization for numerical features
- Train/test splitting
- Conversion to PyTorch tensors
- Mini-batch training with DataLoader

## Model Architectures
Four three-hidden-layer architectures were compared:

- Model 1: 16 → 8 → 4
- Model 2: 32 → 16 → 8
- Model 3: 64 → 32 → 16
- Model 4: 128 → 64 → 32

## Evaluation
Model performance was evaluated using Mean Squared Error (MSE) on both training and testing data.

The experiment focused on examining whether increasing network capacity improved regression performance.

## Tools
- Python
- PyTorch
- pandas
- NumPy
- scikit-learn

## Key Learning
This project strengthened my understanding of:
- neural network architecture
- regression with deep learning
- data preprocessing for neural networks
- model capacity
- training and testing behavior
- Mean Squared Error (MSE)
- PyTorch model training workflow
