# Multi-Layer Perceptron (MLP) Implementation

## 🧠 Project Overview
This project features a custom implementation of a **Multi-Layer Perceptron (MLP)**, a fundamental architecture in deep learning. It explores how neural networks can capture non-linear relationships through multiple hidden layers and the backpropagation algorithm.

##  Technical Implementation
In this project, I implemented and analyzed the following core components:
* **Neural Architecture:** Design of input, hidden, and output layers with customizable neuron counts.
* **Backpropagation:** Manual implementation of the chain rule to compute gradients and update weights/biases.
* **Non-Linear Activations:** Used functions like **ReLU**, **Sigmoid**, or **Tanh** to enable the model to learn complex patterns.
* **Optimization:** Applied Gradient Descent to minimize the Cross-Entropy loss function during training.
* **Vectorized Math:** Efficient matrix operations using **NumPy** to handle thousands of parameters simultaneously.

##  Tech Stack
* **Language:** Python 3.x
* **Environment:** Jupyter Notebook
* **Libraries:** NumPy, Matplotlib (for loss and accuracy visualization).

##  Results & Performance
The notebook includes:
- **Training Visualization:** A plot showing the loss decreasing over epochs.
- **Model Evaluation:** Accuracy metrics on the test set (using MNIST or similar datasets).
- **Architecture Insights:** Comments on how changing the number of neurons or layers affects the final results.
