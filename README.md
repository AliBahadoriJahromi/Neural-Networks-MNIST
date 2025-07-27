# 🧠 Neural Networks from Scratch

This repository, **Neural_networks**, contains implementations of several fundamental **neural network architectures** built entirely **from scratch** (no high-level deep learning frameworks like PyTorch or TensorFlow) and applied to the **MNIST** handwritten digits dataset.

The goal of this project is to provide educational, transparent, and clean code to understand the inner workings of different types of neural networks.

---

## 📂 Repository Structure
Neural_networks/  
├── CNN/ # Convolutional Neural Network  
├── Hebbian/ # Hebbian Learning Rule implementation  
├── Perceptron/ # Single-layer Perceptron  
├── Adaline/ # ADAptive LInear NEuron  
└── Multilayer_perceptron/ # Fully connected feedforward network (MLP)  

---

## 📊 Neural Network Types

### 🔹 Perceptron
- Binary classifier based on a simple threshold activation
- Trained using the perceptron learning rule

### 🔹 Adaline
- Similar to Perceptron but uses linear activation and minimizes mean squared error

### 🔹 Hebbian
- Unsupervised learning based on Hebb's rule: “cells that fire together wire together”

### 🔹 Multilayer Perceptron (MLP)
- Feedforward neural network with one or more hidden layers
- Trained using backpropagation and gradient descent

### 🔹 Convolutional Neural Network (CNN)
- Designed to process image data efficiently
- Includes convolutional and pooling layers for feature extraction

---

## 🧪 Dataset: MNIST

All models are trained and evaluated on the **MNIST** dataset of 28x28 grayscale handwritten digits (0–9). Each network is adapted to handle this format and evaluate classification performance.
