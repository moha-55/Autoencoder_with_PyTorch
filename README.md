# Autoencoder Implementation in PyTorch

This project demonstrates the implementation of an autoencoder using PyTorch. Autoencoders are a type of self-supervised model that learn to reconstruct their inputs from a compressed latent representation. They are widely used for tasks such as dimensionality reduction, denoising, and feature extraction.

## Features
- Encoder: Compresses the input data into a lower-dimensional representation.

- Decoder: Reconstructs the original input data from the compressed representation.

- Gaussian Noise Layer: Adds Gaussian noise during training to improve the model's robustness.
  
- Utility Functions: Includes a utils.py file with reusable functions to simplify training and evaluation.

## Project Files
- Notebook (1-Autoencoder.ipynb): Contains the code for:

1. Building the autoencoder model.

2. Adding a custom Gaussian noise layer.

3. Training and evaluating the model on a dataset.

- Utils (utils.py): Contains helper functions for:

1. Training loops.

2. Model evaluation.

3. Data preprocessing.

## Model Structure

- Encoder

The encoder compresses the input data into a lower-dimensional latent representation using several fully connected layers.

- Decoder

The decoder reconstructs the original data from the latent representation.

- AddGaussianNoise Layer

A custom PyTorch module that adds Gaussian noise during training to enhance model generalization.

## How to Run

1. Clone the repository and navigate to the project folder:
```
git clone <repository_url>
cd <repository_folder>
```
2. Open the notebook 1-Autoencoder.ipynb in Jupyter Notebook or JupyterLab.

3. Run the cells step-by-step to:

- Build the model.

- Train the autoencoder.

- Evaluate its performance.

