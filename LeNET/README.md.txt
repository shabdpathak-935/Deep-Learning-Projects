# 🧠 LeNet-5: Digit Classification with CNN

A classic Convolutional Neural Network (CNN) implementation of **LeNet-5**, trained on the **MNIST** dataset using TensorFlow/Keras.

## 📌 Overview

This project demonstrates the end-to-end pipeline of image classification using one of the earliest deep learning architectures — **LeNet-5**, proposed by Yann LeCun in 1998.

It includes:
- Data preprocessing
- Model architecture (CNN)
- Training & validation
- Performance evaluation
- Visualization of metrics

## 📊 Dataset

- **Name:** MNIST Handwritten Digits
- **Size:** 60,000 training images & 10,000 test images
- **Shape:** 28x28 grayscale images
- **Classes:** Digits (0–9)

## 🧱 LeNet-5 Architecture

- Input: 32x32x1 (after padding MNIST images)
- C1: Conv layer (6 filters, 5x5)
- S2: Average Pooling
- C3: Conv layer (16 filters, 5x5)
- S4: Average Pooling
- C5: Conv layer (120 filters, 5x5)
- F6: Fully Connected (84 units)
- Output: Fully Connected (10 units with Softmax)

## 🚀 Getting Started

### 🔧 Prerequisites

- Python 3.x
- TensorFlow 2.x
- NumPy
- Matplotlib
