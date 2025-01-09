# Credit Card Fraud Detection Project

## Introduction
This project focuses on detecting fraudulent transactions from a dataset of credit card transactions. Fraud detection is a classification task where the goal is to predict whether a transaction is fraudulent (class 1) or not (class 0).

## Dataset
- **Source:** Kaggle (https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud)
- **Total Transactions:** 284,807
- **Features:**
  - 30 columns, including:
    - 28 anonymized features labeled V1 to V28
    - `Time` and `Amount`
- **Target Variable:**
  - `Class` (1 = Fraud, 0 = Non-Fraud)

## Model Evaluation

### Logistic Regression
- **Accuracy:** 95%
- **Performance Metrics:**
  - Precision: 93%-97%
  - Recall: 92%-97%
  - F1-Score: 95%
- **Confusion Matrix:**
  ```
  [[55434  1429]
   [ 4348 52515]]
  ```
- **ROC-AUC Score:** 0.9899

### Random Forest
- **Accuracy:** 99%
- **Performance Metrics:**
  - Precision: 98%-100%
  - Recall: 98%-100%
  - F1-Score: 99%
- **Confusion Matrix:**
  ```
  [[56761   102]
   [ 1178 55685]]
  ```
- **ROC-AUC Score:** 0.9994

### Summary
- The **Random Forest model** outperformed Logistic Regression:
  - Higher accuracy: 99%
  - Near-perfect ROC-AUC: 0.9994
- It demonstrated better precision, recall, and F1-scores, especially in handling imbalanced data.

---

Feel free to contribute or share feedback for further improvements!
