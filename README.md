# Credit Card Fraud Detection

## Overview
This project focuses on detecting fraudulent credit card transactions using machine learning techniques.  
The goal is to build a model that can accurately identify fraud in a highly imbalanced dataset.

This project demonstrates skills in data preprocessing, exploratory data analysis (EDA), handling class imbalance, and applying classification models.

---

## Dataset
- **Source:** Kaggle – Credit Card Fraud Detection
- **Transactions:** 284,807
- **Fraud Cases:** 492 (≈ 0.17%)
- **Features:**
  - `V1`–`V28`: PCA-transformed features
  - `Time`: Time elapsed between transactions
  - `Amount`: Transaction amount
  - `Class`: Target variable (0 = Legitimate, 1 = Fraud)

---

## Tools & Technologies
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

---

## Approach
1. Data exploration and visualization
2. Data preprocessing and scaling
3. Handling class imbalance
4. Model training and evaluation
5. Performance comparison

---

## Evaluation Metrics
- Precision
- Recall
- F1-score
- ROC-AUC

---

## Results
- High recall achieved for fraudulent transactions
- Demonstrates the importance of using proper metrics for imbalanced datasets

---

## How to Run
1. Clone the repository
   ```bash
   git clone https://github.com/jigarrambhiya1/Kaggle-Credit-Card-Fraud-Detection.git
