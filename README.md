# XOR MLP using TensorFlow

This project implements a simple **Multilayer Perceptron (MLP)** using **TensorFlow** to solve the classic **XOR logic problem**, demonstrating the power of deep learning in learning non-linear patterns.

---

## 🧠 What is Deep Learning?

**Deep Learning** is a subfield of **machine learning** that uses layered neural networks to automatically learn complex patterns from data. It mimics how the human brain processes information.

### Key Concepts:
- **Neurons**: Basic computing units that process input and generate output.
- **Layers**: Arranged sequences of neurons (input → hidden → output).
- **Activation Functions**: Introduce non-linearity so networks can learn complex tasks.
- **Backpropagation**: An algorithm used to adjust weights by minimizing error.

MLPs are a fundamental type of deep learning model used in classification, regression, and pattern recognition tasks.

---

## 🔍 Problem: XOR Logic

The XOR (exclusive OR) logic gate outputs true (1) only when the inputs differ. Its truth table:

| Input A | Input B | Output |
|---------|---------|--------|
|   0     |    0    |   0    |
|   0     |    1    |   1    |
|   1     |    0    |   1    |
|   1     |    1    |   0    |

Traditional linear models **cannot learn XOR**, but a neural network **with a hidden layer** can.

---

## 🚀 Model Overview

- **Model Type**: Multilayer Perceptron (MLP)
- **Framework**: TensorFlow / Keras
- **Architecture**:
  - Input layer: 2 neurons
  - Hidden layer: 4 neurons, ReLU activation
  - Output layer: 1 neuron, Sigmoid activation
- **Loss Function**: Binary Crossentropy
- **Optimizer**: Adam

---

## 📦 Dependencies
    
pip install tensorflow numpy

## ✅ Sample Output
Accuracy: 1.0000
Predictions: [[0.]
              [1.]
              [1.]
              [0.]]
