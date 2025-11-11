# MNIST Handwritten Digit Recognition

This project demonstrates a **Convolutional Neural Network (CNN)** built using **TensorFlow/Keras** to recognize handwritten digits (0–9) from the **MNIST dataset**.  
It also includes a custom image testing pipeline to evaluate your trained model on your own handwritten digit images.

---

## Overview

- **Dataset:** [MNIST](http://yann.lecun.com/exdb/mnist/)
- **Framework:** TensorFlow / Keras
- **Model Type:** Convolutional Neural Network (CNN)
- **Accuracy:** ~98% on test data
- **Custom Image Testing:** Supported via OpenCV preprocessing

---

## Features

- Train a CNN to classify handwritten digits  
- Visualize training accuracy & loss over epochs  
- Test with your own handwritten digit images (in the `samples/` folder)  
- Preprocessing includes adaptive thresholding, denoising, and centering  

---

## Requirements

Make sure you have **Python 3.9+** installed, then install dependencies:

```bash
pip install numpy matplotlib tensorflow opencv-python
