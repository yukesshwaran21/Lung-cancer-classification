# 🧠 Lung Cancer Classification using Hybrid Deep Learning + ML

## 📌 Overview
This project presents a hybrid framework combining CNN (EfficientNet) with Machine Learning (SVM, LR, RF) to classify lung cancer from CT scans.

## 🚀 Key Features
- Transfer Learning (EfficientNet, SqueezeNet)
- Hybrid Model (CNN + ML)
- Hyperparameter tuning using GridSearchCV
- Grad-CAM visualization
- Achieved **97.32% accuracy**

## 🧪 Dataset
- IQ-OTH/NCCD Lung Cancer Dataset
- 3 Classes:
  - Benign
  - Malignant
  - Normal

## 🏗️ Architecture
1. Image Preprocessing
2. Feature Extraction (CNN)
3. ML Classification (SVM, LR, RF)
4. Optimization (GridSearchCV)

## 📊 Results
- Best Model: EfficientNet-B1 + SVM
- Accuracy: 97.32%
- F1 Score: 0.9465

## 📁 Project Structure
(Explain folders)

## ▶️ How to Run
```bash
pip install -r requirements.txt
jupyter notebook
