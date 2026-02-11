# AI_ML_Internship-Task-11
# SVM Breast Cancer Classification – AI & ML Internship Task

## 📌 Project Overview
This project implements a **Support Vector Machine (SVM)** model to classify breast cancer tumors as **malignant** or **benign** using the Scikit-learn Breast Cancer dataset.

The goal of this task is to understand:
- Kernel-based classification
- Feature scaling
- Model tuning using GridSearchCV
- Performance evaluation using ROC-AUC


## 📊 Dataset
- Source: Scikit-learn built-in dataset (`load_breast_cancer()`)
- Samples: 569
- Features: 30 numerical features
- Target Classes:
  - 0 → Malignant
  - 1 → Benign

## 🛠️ Tools & Technologies Used
- Python
- Scikit-learn
- NumPy
- Pandas
- Matplotlib
- Joblib

## ⚙️ Project Workflow

### 1️⃣ Data Loading & Exploration
- Loaded dataset using sklearn
- Checked class distribution
- Inspected feature structure

### 2️⃣ Data Preprocessing
- Train-Test Split (80-20)
- StandardScaler applied for feature normalization

### 3️⃣ Model Training
- Baseline Linear SVM
- RBF Kernel SVM

### 4️⃣ Hyperparameter Tuning
Used GridSearchCV to optimize:
- C parameter
- Gamma value
- Kernel type

### 5️⃣ Model Evaluation
- Confusion Matrix
- Classification Report
- ROC Curve
- AUC Score

### 6️⃣ Model Saving
- Saved trained pipeline using Joblib

## 📈 Results
- High classification accuracy achieved
- ROC-AUC used to evaluate model performance
- Tuned SVM provided improved generalization
