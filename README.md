# income-prediction

# Income Prediction using Machine Learning

This project focuses on predicting whether an individual’s annual income exceeds $50,000 using demographic and employment-related data. The analysis is based on the **Adult dataset** from the UCI Machine Learning Repository.

The project demonstrates a complete data science workflow, including data preprocessing, modeling, evaluation, and interpretation.

---

## Dataset
- Source: UCI Machine Learning Repository – Adult Dataset
- Target variable: income (<=50K, >50K)
- Each observation represents one individual

---

## Methods
- Data preprocessing (standardization, One-Hot Encoding)
- Logistic Regression implemented with a Pipeline
- Hyperparameter tuning using GridSearchCV
- Model evaluation with F1-score, confusion matrix, and ROC–AUC
- Interpretation using odds ratios

---

## Results
- Accuracy: ~0.80
- F1-score (class >50K): ~0.68
- ROC–AUC: ~0.90

---

## Project Status
This project is a work in progress and will be extended with additional models such as decision trees and neural networks to compare model performance and improve the results.

---

## Technologies
Python, pandas, numpy, scikit-learn, matplotlib, seaborn
