#  Stochastic Gradient Descent (SGD) Lab

##  Overview
This lab explores **Stochastic Gradient Descent (SGD)** and compares different training strategies:
- **SGD without minibatching** (updating weights after each sample)
- **SGD with minibatching** (updating weights after a batch of samples)

We analyze how batch size impacts **convergence speed**, **stability**, and **generalization performance**.  
The experiments are conducted using a **feedforward neural network** trained on the **MNIST dataset**.

---

##  **Neural Network Architecture**
For all experiments, we used a simple **fully connected feedforward neural network** with **three layers**:

- **Input layer**: 784 neurons (28x28 flattened MNIST images)
- **Hidden layer 1**: 32 neurons, **ReLU** activation
- **Hidden layer 2**: 32 neurons, **ReLU** activation
- **Output layer**: 10 neurons, **Softmax** activation (for digit classification)

This model was trained using **SGD with different configurations** to observe its learning behavior.

---
