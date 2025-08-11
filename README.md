# MNIST Handwritten Digit Classification using Neural Network - Keras

## 📌 Project Overview
This project builds and trains a simple **feed-forward neural network** using the Keras API to classify handwritten digits from the MNIST dataset.

The MNIST dataset contains **60,000 training images** and **10,000 testing images** of digits (0–9), each of size 28×28 pixels.

---

## 📂 Dataset
- **Source:** [MNIST Dataset](http://yann.lecun.com/exdb/mnist/)
- **Shape before preprocessing:** `(60000, 28, 28)` for training and `(10000, 28, 28)` for testing.
- **Classes:** Digits 0–9 (10 classes in total).

---

## 🔄 Preprocessing Steps
1. **Flatten images**: Convert from `(28, 28)` to a 1D array `(784,)`.
2. **Convert to float32**: For TensorFlow compatibility and reduced memory usage.
3. **Normalize pixel values**: Scale from range `0–255` to `0–1`.
4. **One-hot encode labels**: Convert digit labels to binary class vectors.

---
