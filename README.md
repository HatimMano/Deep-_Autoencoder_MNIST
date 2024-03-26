# Autoencoder and Denoising Autoencoder on MNIST dataset

## Overview
This code implements autoencoder and denoising autoencoder models on the MNIST dataset. It includes the implementation of both the encoder and decoder parts of the autoencoder architecture.

## Requirements
- Python 3.x
- TensorFlow 2.x
- Keras

## Usage
1. Load the MNIST dataset using `keras.datasets.mnist`.
2. Normalize the data by dividing by 255.0.
3. Define the encoder architecture using dense layers with ReLU activation and dropout.
4. Define the decoder architecture using dense layers with ReLU activation, dropout, and reshape layer.
5. Compile the model using suitable loss and optimizer (e.g., 'nadam' optimizer and 'binary_crossentropy' loss for denoising autoencoder).
6. Train the autoencoder model using the training data.
7. Optionally, apply noise to the training data to create a denoising autoencoder.
8. Define the sampling layer for the variational autoencoder.
9. Build the encoder and decoder models separately.
10. Define the latent inputs and build the autoencoder model.
11. Compile the autoencoder model using suitable loss and optimizer (e.g., 'mse' loss and 'adam' optimizer).
12. Train the autoencoder model using the training data.

