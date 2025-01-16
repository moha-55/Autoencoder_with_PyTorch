# Autoencoder Implementation in PyTorch

This project demonstrates the implementation of an autoencoder using PyTorch. Autoencoders are a type of self-supervised model that learn to reconstruct their inputs from a compressed latent representation. They are widely used for tasks such as dimensionality reduction, denoising, and feature extraction.

## Features
- Encoder: Compresses the input data into a lower-dimensional representation.

- Decoder: Reconstructs the original input data from the compressed representation.

- Gaussian Noise Layer: Adds Gaussian noise during training to improve the model's robustness.
  
- Utility Functions: Includes a utils.py file with reusable functions to simplify training and evaluation.

## Project Files
- Notebook (1-Autoencoder.ipynb): Contains the code for:

-- Building the autoencoder model.

-- Adding a custom Gaussian noise layer.

-- Training and evaluating the model on a dataset.

- Utils (utils.py): Contains helper functions for:

-- Training loops.

-- Model evaluation.

-- Data preprocessing.
