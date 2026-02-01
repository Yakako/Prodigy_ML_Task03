# Prodigy_ML_Task03

## 🐶🐱 Cat vs Dog Image Classification using SVM
---
## 📌 Project Overview
This project implements a Support Vector Machine (SVM) classifier to distinguish between cat and dog images using the Kaggle Dogs vs Cats dataset.

The images are preprocessed and converted into numerical feature vectors before training a linear SVM model.
---
## 🎯 Objectives
- Load and preprocess image data
- Extract features from images
- Train an SVM classifier
- Evaluate classification performance
## 📂 Dataset
- Source: Kaggle – Dogs vs Cats
- Link: https://www.kaggle.com/c/dogs-vs-cats/data
---
## 🛠 Technologies Used
- Python 3
- NumPy
- OpenCV
- Scikit-learn
- TQDM
---
## ⚙️ Methodology
1. Load images from dataset folders
2. Resize images to 64 × 64 pixels
3. Convert images to grayscale
4. Flatten images into 1D feature vectors
5. Split dataset into training and testing sets
6. Apply feature scaling
7. Train a Linear Support Vector Machine
8. Evaluate model using accuracy and classification report
---

## 🧾 Implementation Steps
- 1️⃣ Data Preprocessing
Images are resized to ensure uniform dimensions
Grayscale conversion reduces computational cost
Flattening converts images into numerical feature vectors
- 2️⃣ Model Training
A Linear SVM (LinearSVC) is used
Feature scaling improves model performance
- 3️⃣ Evaluation
Accuracy score
Precision, recall, and F1-score
---

## ✅ Results
The SVM model successfully classifies cat and dog images with reasonable accuracy.
While SVM performs well for this task, Convolutional Neural Networks (CNNs) are more suitable for large-scale image classification problems.

---

## 👤 Author
- Name: PRUONH KIMLIYA
- Email: kimliyapruonh@gmail.com
