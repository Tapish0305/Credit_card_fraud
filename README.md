# Credit Card Fraud Detection
# Overview
This project implements a Credit Card Fraud Detection model using Logistic Regression and LightGBM Classifier. The dataset is preprocessed, balanced using SMOTE and NearMiss, and evaluated with multiple performance metrics.
# Features
Data Preprocessing & Feature Engineering
Handling Imbalanced Data using SMOTE and NearMiss
Model Training using Logistic Regression and LightGBM
Hyperparameter Tuning using RandomizedSearchCV
Performance Evaluation: Accuracy, Precision, Recall, F1-score, AUC-ROC
# Installation
To run this project, install the required dependencies:
lightgbm, scikit-learn, pandas, numpy, imbalanced-learn, matplotlib, seaborn

# Dataset
The dataset contains transaction details with features like time, amount, and anonymized principal components (V1-V28). The target variable indicates whether a transaction is fraudulent (Class = 1) or not (Class = 0).
# Model Approach
**Data Preprocessing:**
Drop irrelevant columns.
Split data into training and testing sets.
**Balancing Data:**
SMOTE: Over-samples the minority class (fraud cases).
NearMiss: Under-samples the majority class (non-fraud cases).
**Model Selection:**
Logistic Regression (Baseline Model)
LightGBM Classifier (Boosted Model)
**Hyperparameter Tuning:**
Used RandomizedSearchCV to find optimal parameters.
**Evaluation Metrics:**
Accuracy, Precision, Recall, F1-score, AUC-ROC.

# Results
The trained model is evaluated using various metrics. The results, including confusion matrix, precision-recall curve, and ROC curve, are visualized for better understanding.
# Contributing
Contributions are welcome! Feel free to submit a pull request or open an issue.
