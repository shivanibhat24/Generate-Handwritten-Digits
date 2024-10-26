# Digit Generation with GANs

This repository contains a script (`digitgen.py`) to train a Generative Adversarial Network (GAN) for generating handwritten digits based on the MNIST dataset. The model learns from the MNIST training dataset to produce images that resemble real handwritten digits.

## Features

- **Dataset**: Uses the MNIST dataset of handwritten digits.
- **Image Normalization**: Normalizes images to the [-1, 1] range for better GAN performance.
- **Model Architecture**: Implements a simple GAN using TensorFlow and Keras.
- **Training**: Trains the GAN to generate realistic digit images.

## Prerequisites

To run this script, you need the following Python packages:
- `tensorflow`
- `numpy`
- `matplotlib`
- `PIL`
- `imageio`

You can install them using pip:
```bash
pip install tensorflow numpy matplotlib pillow imageio

## Usage
Load and preprocess the dataset: The script automatically loads the MNIST dataset and normalizes the images.
Define the GAN architecture: Both generator and discriminator models are defined in the code.
Train the GAN: Run the training function to start generating digits.
