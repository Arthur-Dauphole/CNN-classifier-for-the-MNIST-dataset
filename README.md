# Handwritten Digit Recognition (CNN)

![Python](https://img.shields.io/badge/Python-3.8%2B-blue)
![TensorFlow](https://img.shields.io/badge/TensorFlow-2.x-orange)
![Status](https://img.shields.io/badge/Status-Completed-green)

## 📄 Project Overview
This project demonstrates a computer vision pipeline capable of recognizing handwritten digits (0-9) using the MNIST dataset. 

It implements a **Convolutional Neural Network (CNN)** from scratch using TensorFlow/Keras to achieve high classification accuracy. The goal is to showcase a structured approach to deep learning, from data preprocessing to model evaluation.

## 🏗 Architecture
The model is built with the following architecture:
1.  **Input Layer**: 28x28x1 grayscale images (Normalized).
2.  **Conv2D**: Feature extraction with 3x3 kernels and ReLU activation.
3.  **MaxPooling2D**: Spatial downsampling to reduce parameters.
4.  **Flatten**: Conversion from 2D feature maps to 1D vectors.
5.  **Dense Layers**: Two fully connected layers (64 units) for interpretation.
6.  **Output Layer**: Softmax activation for multi-class probability distribution.

## 📊 Results
* **Final Test Accuracy**: ~98% (varies slightly based on initialization)
* **Loss Function**: Sparse Categorical Crossentropy
* **Optimizer**: Adam

## 🚀 Getting Started

### Prerequisites
* Python 3.x
* Jupyter Notebook
