# -Handwritten-Digit-Recognition-using-Deep-Learning-MNIST-
 This project demonstrates the use of deep learning, specifically Convolutional Neural Networks (CNNs), to recognize handwritten digits using the famous MNIST dataset. The MNIST dataset consists of 70,000 grayscale images of handwritten digits (0–9), each of size 28x28 pixels. These images are widely used as a benchmark in the fields of machine L.
# 🔢 Handwritten Digit Recognition using Deep Learning (MNIST)

## 📌 Project Overview

This project focuses on recognizing handwritten digits (0–9) using a **Convolutional Neural Network (CNN)** trained on the **MNIST dataset**. The goal is to build an accurate image classification model that takes a 28x28 grayscale image of a digit and correctly identifies it.

---

## 🧠 Objective

To design and train a deep learning model using **TensorFlow/Keras** that can accurately classify digits in the MNIST dataset — a benchmark dataset in computer vision and deep learning.

---

## 🗂️ Dataset Details

- **Dataset Name**: MNIST (Modified National Institute of Standards and Technology)
- **Images**: 70,000 total
  - 60,000 training images
  - 10,000 test images
- **Image Size**: 28x28 pixels
- **Classes**: 10 (Digits 0 to 9)
- **Type**: Grayscale images

---

## 🧰 Tools & Libraries Used

- Python
- TensorFlow / Keras
- NumPy, Matplotlib
- Scikit-learn (for evaluation)
- Jupyter Notebook

---

## 🔧 Project Workflow

1. Import libraries and load MNIST data
2. Preprocess the dataset (normalize, reshape, one-hot encode)
3. Build CNN architecture using Keras Sequential API
4. Train and validate the model
5. Evaluate performance on the test set
6. Visualize training accuracy/loss and predictions

---

## 🧱 CNN Architecture

- **Input Layer**: 28x28 grayscale image
- **Conv2D Layer** (32 filters, 3x3)
- **MaxPooling2D**
- **Conv2D Layer** (64 filters, 3x3)
- **MaxPooling2D**
- **Flatten**
- **Dense Layer (128 neurons, ReLU)**
- **Output Layer (10 neurons, Softmax)**

---

## 📈 Model Accuracy

- **Training Accuracy**: ~99%
- **Test Accuracy**: ~98.5%

> 📌 Achieved excellent performance with a simple CNN, demonstrating the power of deep learning on image data.

---

## 📊 Visualization

- Confusion matrix
- Accuracy/loss curve
- Sample predictions vs. actual labels

---

## ✅ Key Learnings

- Understanding CNN architecture
- Image preprocessing for DL models
- Use of Keras for rapid prototyping
- Evaluating classification performance

--
