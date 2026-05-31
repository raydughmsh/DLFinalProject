# Deep Learning Final Project

![Python](https://img.shields.io/badge/Python-3.9%2B-blue)
![TensorFlow](https://img.shields.io/badge/TensorFlow-2.20-orange)
![License](https://img.shields.io/badge/License-Academic-lightgrey)

**Course:** Introduction to Deep Learning  
**Instructor:** Dr. Öğr. Üyesi Ümit Demirbaga  
**Student:** Rayan Dughmoush

---

## Overview

This project implements and evaluates three deep learning models in Python using TensorFlow/Keras, covering both **text** and **image** data modalities across **supervised** and **unsupervised** learning paradigms.

| # | Model | Data Type | Task | Dataset |
|---|-------|-----------|------|---------|
| 1 | Artificial Neural Network (ANN) | Text | Binary Classification | SMS Spam Collection |
| 2 | Autoencoder | Image | Unsupervised Reconstruction | MNIST |
| 3 | Convolutional Neural Network (CNN) | Image | Multi-class Classification | Fashion-MNIST |

---

## Results

| Model | Metric | Value |
|-------|--------|-------|
| ANN (Spam Detection) | Test Accuracy | **97.49%** |
| ANN (Spam Detection) | Spam F1-Score | **0.90** |
| Autoencoder (MNIST) | Test MSE | **0.0087** |
| Autoencoder (MNIST) | Test RMSE | **0.093** |
| CNN (Fashion-MNIST) | Test Accuracy | **91%** |
| CNN (Fashion-MNIST) | Macro F1-Score | **0.91** |

---

## Project Structure

```
DeepLearningProject/
├── 1_ANN_SpamDetection.ipynb     # ANN - SMS spam vs. ham (TF-IDF + Dense layers)
├── 2_Autoencoder_MNIST.ipynb     # Autoencoder - MNIST image reconstruction
├── 3_CNN_FashionMNIST.ipynb      # CNN - 10-class Fashion-MNIST classification
├── requirements.txt              # Python dependencies
└── README.md
```

---

## Datasets

| Dataset | Type | Link |
|---------|------|------|
| SMS Spam Collection | Text | [UCI Repository](https://archive.ics.uci.edu/ml/machine-learning-databases/00228/smsspamcollection.zip) |
| MNIST | Image | [yann.lecun.com](http://yann.lecun.com/exdb/mnist/) |
| Fashion-MNIST | Image | [zalandoresearch/fashion-mnist](https://github.com/zalandoresearch/fashion-mnist) |

> MNIST and Fashion-MNIST are downloaded automatically via `tensorflow.keras.datasets`.  
> The SMS Spam Collection is downloaded automatically on first run from the UCI URL above.

---

## Setup & Running

**1. Install dependencies:**

```bash
pip install -r requirements.txt
```

**2. Launch Jupyter:**

```bash
jupyter notebook
```

**3. Open and run each notebook from top to bottom** - all datasets are fetched automatically on first run, no manual downloads required.

---

## Dependencies

| Package | Version |
|---------|---------|
| Python | 3.9+ |
| TensorFlow | >= 2.13 |
| scikit-learn | >= 1.3 |
| pandas | >= 2.0 |
| matplotlib | >= 3.7 |
| seaborn | >= 0.12 |
| numpy | >= 1.24 |
