# chest-xray-pneumonia-classifier

# 🩺 Pneumonia Detection using CNN

This project uses a Convolutional Neural Network (CNN) to detect pneumonia from chest X-ray images. It is a deep learning-based image classification model built using TensorFlow and Keras.

---

## 📌 Project Overview

Pneumonia is a serious respiratory disease that can be detected through chest X-rays. This project aims to automate the detection process using deep learning, helping in faster and more accurate diagnosis.

The model is trained on a labeled dataset of chest X-ray images and classifies them into:
- Normal
- Pneumonia

---

## 🧠 Model Architecture

The model is a Sequential CNN consisting of:
- Convolutional layers (Conv2D)
- Batch Normalization
- Max Pooling layers
- Fully connected (Dense) layers

Key features:
- Activation: ReLU
- Loss function: Binary Crossentropy
- Optimizer: Adam
- Metrics: Accuracy and Recall

---

## 📂 Dataset

Dataset used:
- Chest X-Ray Pneumonia dataset from Kaggle

It includes:
- Training set
- Validation set
- Test set

Images are preprocessed using:
- Rescaling
- Rotation
- Zoom
- Horizontal flipping

---

## ⚙️ Technologies Used

- Python
- TensorFlow / Keras
- NumPy
- KaggleHub

---

## 🚀 How to Run

Download kagglehub by writing (pip install kagglehub) in terminal 
