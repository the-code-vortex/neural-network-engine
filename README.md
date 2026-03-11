# Neural Network Engine from Scratch

A fully hand-rolled feedforward neural network built using only 
NumPy — no ML frameworks. Trained and evaluated on the MNIST 
handwritten digit dataset, with a live web interface for 
real-time prediction.

## Overview
Most ML practitioners rely on frameworks like PyTorch or 
TensorFlow without understanding what happens underneath. 
This project builds every component from first principles — 
forward pass, backpropagation, optimization, and 
regularization — using only NumPy.

## Tech Stack
Python, NumPy, Matplotlib, Flask, Render

## Key Features
- **Zero framework dependency** — entire network built with NumPy
- **Manual backpropagation** — gradients computed analytically 
  from scratch
- **Mini-batch gradient descent** — implemented without any 
  autograd engine
- **Dropout regularization** — reduces overfitting, implemented 
  manually
- **Learning rate scheduling** — dynamic adjustment during training
- **Live web app** — real-time canvas interface for handwritten 
  digit prediction

## Dataset
Trained on the MNIST dataset — 60,000 training samples and 
10,000 test samples of handwritten digits (0–9).


## Status
🚧 In Progress
