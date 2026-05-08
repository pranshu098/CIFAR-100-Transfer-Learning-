# CIFAR-100-Transfer-Learning-
CIFAR-100 Image Classification using Transfer Learning with ResNet50, VGG16, and MobileNetV2


A Deep Learning project that applies Transfer Learning techniques using ResNet50, VGG16, and MobileNetV2 on the CIFAR-100 dataset for multi-class image classification.

---

# Project Overview
This project focuses on comparing the performance of multiple pre-trained Convolutional Neural Network (CNN) architectures on the CIFAR-100 dataset.

The models are trained using Transfer Learning and Fine-Tuning techniques with TensorFlow and Keras.

Implemented Models:
- ResNet50
- VGG16
- MobileNetV2

---

# Dataset
## CIFAR-100 Dataset
The CIFAR-100 dataset contains:

- 60,000 RGB images
- 100 image classes
- Image size: 32×32
- 50,000 training images
- 10,000 testing images

Dataset is loaded directly using TensorFlow/Keras.

---

# Technologies Used
- Python
- TensorFlow
- Keras
- NumPy
- Matplotlib

---

# Deep Learning Concepts Used
- Transfer Learning
- Fine-Tuning
- CNN Architectures
- Feature Extraction
- Image Classification
- Model Evaluation

---

# Models Implemented

## 1. ResNet50
- Residual Network Architecture
- Better gradient flow using skip connections
- Fine-tuned on CIFAR-100 dataset

## 2. VGG16
- Deep sequential CNN architecture
- Strong feature extraction capability

## 3. MobileNetV2
- Lightweight and efficient CNN
- Optimized for faster inference
- Suitable for mobile/edge deployment

---

# Project Features
- Transfer learning implementation
- Fine-tuning of pre-trained models
- Training and validation visualization
- Accuracy comparison
- Loss comparison
- Saved trained models
- Clean TensorFlow/Keras workflow

---

# Training Details
## Optimizer
```python
Adam
