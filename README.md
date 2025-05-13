# Fraud-detection
# 🧠 Fraud Detection in Python

This repository contains a complete end-to-end project on fraud detection using machine learning, built as part of a course-style learning experience.

---

## 📂 Files

- `Complete_Fraud_Detection_Notebook.ipynb`  
  A structured Jupyter notebook that walks through every phase of a fraud detection pipeline, including model building, evaluation, interpretation, and cost-sensitive decision making.

- `app.py`  
  A Streamlit app that allows users to interactively adjust the fraud detection threshold and observe the impact on total fraud cost.

---

## 🚀 Notebook Overview

The notebook covers the following sections:

### 🔹 Section 1–2: Data Preparation & Imbalance Handling
- Simulated fraud transaction dataset
- Class imbalance analysis
- SMOTE (Synthetic Minority Oversampling Technique)

### 🔹 Section 3: Model Training
- Logistic Regression
- XGBoost Classifier

### 🔹 Section 4: Performance Metrics
- Confusion matrix
- ROC and Precision-Recall Curves
- Accuracy Paradox explanation

### 🔹 Section 5: Optimal Threshold Selection
- Custom cost function for fraud vs. false alarm
- Threshold vs. cost simulation

### 🔹 Section 6: Model Interpretability
- SHAP explanations for XGBoost
- Coefficients and odds ratios for Logistic Regression

---

## 🛠 How to Use

1. Clone the repository:
   ```bash
   git clone https://github.com/Mohsenselseleh/Fraud-detection.git
   cd Fraud-detection
