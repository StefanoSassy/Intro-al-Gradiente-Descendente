# Intro-al-Gradiente-Descendente

This repository contains an educational implementation of the **Gradient Descent** method, using a simple neural network setup to demonstrate how weights and biases are updated during training.

The goal is to help understand how gradient descent works step by step, particularly how the error is minimized by adjusting model parameters.

## 📌 What you'll find

- A basic neural network with:
  - One input (representing a phrase with a fixed probability).
  - A single hidden layer with multiple outputs representing possible responses.
- Manual implementation of:
  - The sigmoid activation function and its derivative.
  - The Mean Squared Error (MSE) as the loss function.
  - Gradient descent updates for both weights and bias.
- A visualization of the loss decreasing over time.

## 🚀 Files

- `gradient_descent.py` or `notebook.ipynb`: Main script/notebook containing the implementation.
- `README.md`: This file.
- `mse_plot.png` (optional): MSE curve showing convergence.

## 🧠 Concepts covered

- Gradient descent
- Derivatives and backpropagation
- Sigmoid activation
- Loss minimization (MSE)
- Weight and bias updates
- Basic machine learning intuition

## 🛠️ Requirements

This project uses:

- `numpy`
- `matplotlib`

You can install them with:

```bash
pip install numpy matplotlib
