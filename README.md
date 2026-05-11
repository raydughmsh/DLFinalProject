# Introduction to Deep Learning — Final Project

## Course
Introduction to Deep Learning

## Project Overview

This project implements three deep learning models in Python using TensorFlow/Keras, covering both text and image data modalities.

| # | Model | Data Type | Problem |
|---|---|---|---|
| 1 | Artificial Neural Network (ANN) | Text | SMS Spam Detection |
| 2 | Autoencoder | Image | MNIST Image Reconstruction |
| 3 | Convolutional Neural Network (CNN) | Image | FashionMNIST Classification |

## Files

- `1_ANN_SpamDetection.ipynb` — ANN for text classification (spam vs. ham)
- `2_Autoencoder_MNIST.ipynb` — Autoencoder for image reconstruction
- `3_CNN_FashionMNIST.ipynb` — CNN for 10-class image classification

## Requirements

Install all dependencies with:

```bash
pip install -r requirements.txt
```

## Running the Notebooks

Each notebook is self-contained and can be run from top to bottom. Datasets are either loaded automatically via Keras built-ins or downloaded from a public URL on first run.

```bash
jupyter notebook
```

Then open each `.ipynb` file in order.

## Dependencies

- Python 3.9+
- TensorFlow >= 2.13
- scikit-learn >= 1.3
- pandas >= 2.0
- matplotlib >= 3.7
- seaborn >= 0.12
- numpy >= 1.24
