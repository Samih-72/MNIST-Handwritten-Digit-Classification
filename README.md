# Handwritten Digit Classification using CNN

A Deep Learning project that classifies handwritten digits (0–9) using a Convolutional Neural Network (CNN) built with TensorFlow and Keras.

---

## Project Overview

This project uses the famous MNIST dataset containing 70,000 grayscale images of handwritten digits.

The goal is to train a CNN model capable of recognizing digits with high accuracy.

---

## Dataset

Dataset: MNIST

- 60,000 Training Images
- 10,000 Testing Images
- Image Size: 28 × 28 pixels
- Classes: 10 (Digits 0–9)

---

## Technologies Used

- Python
- TensorFlow
- Keras
- NumPy
- Matplotlib
- Jupyter Notebook

---

## CNN Architecture

Input (28×28×1)

↓

Conv2D (32 Filters)

↓

MaxPooling2D

↓

Conv2D (64 Filters)

↓

MaxPooling2D

↓

Flatten

↓

Dense (128, ReLU)

↓

Dropout (0.5)

↓

Dense (10, Softmax)

---

## Training Results

Training Accuracy: XX%

Validation Accuracy: XX%

Test Accuracy: XX%

(Update these after training)

---

## Sample Predictions

Model successfully predicts handwritten digits from the MNIST dataset.

---

## Output Images

### Accuracy Graph

![Accuracy](images/accuracy.png)

### Loss Graph

![Loss](images/loss.png)

### Sample Predictions

![Prediction](images/prediction.png)

---

## Future Improvements

- Hyperparameter tuning
- Batch Normalization
- Data Augmentation
- Deploy using Streamlit
- Convert to TensorFlow Lite

---

## Author

Your Name

Aspiring AI Engineer

LinkedIn:
GitHub:
