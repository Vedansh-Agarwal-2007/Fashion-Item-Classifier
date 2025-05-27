# Fashion-Item-Classifier

# 👗 Fashion Item Classification using CNN

This project demonstrates a Convolutional Neural Network (CNN)-based image classifier built on the Fashion MNIST dataset. The model identifies grayscale images of clothing items into one of 10 predefined categories.

---

## 📂 Dataset Overview

- **Source**: [Fashion MNIST on Kaggle](https://www.kaggle.com/datasets/zalando-research/fashionmnist)  
- **Images**: 70,000 total (28x28 grayscale)
  - 60,000 for training
  - 10,000 for testing
- **Classes**:
  0. T-shirt/top  
  1. Trouser  
  2. Pullover  
  3. Dress  
  4. Coat  
  5. Sandal  
  6. Shirt  
  7. Sneaker  
  8. Bag  
  9. Ankle boot  

---

## 🎯 Objective

Build an accurate deep learning model to classify clothing items from the Fashion MNIST dataset, visualize performance using accuracy plots and a confusion matrix, and analyze misclassifications.

---

## 🛠 Tech Stack

- Python  
- TensorFlow / Keras  
- NumPy  
- Matplotlib, Seaborn  
- Scikit-learn  

---

## 🧠 Model Summary

**CNN Architecture**:
- Input: 28x28x1
- Conv2D (32 filters) + ReLU
- MaxPooling2D (2x2)
- Conv2D (64 filters) + ReLU
- MaxPooling2D (2x2)
- Flatten
- Dense (128 units) + ReLU
- Dense (10 units, Softmax)

**Compilation**:
- Loss: Categorical Crossentropy  
- Optimizer: Adam  
- Metrics: Accuracy  
- Epochs: 10–20  
- Validation Split: 10%  

---

## 📈 Results

- Test Accuracy: ~90–91% (may vary)
- Visualizations:
  - Accuracy/Loss curves
  - Confusion Matrix
  - Sample Predictions

The confusion matrix helps identify which classes are commonly confused (e.g., Shirt vs. T-shirt).

---
