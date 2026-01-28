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
- Data preprocessing (handling missing values, standardization, One-Hot Encoding)  
- Train/test split (80/20)  
- Pipeline-based modeling approach  
- Models:
  - Logistic Regression 
  - Random Forest
  - XGBoost
- Hyperparameter tuning using GridSearchCV  
- Model evaluation using F1-score, confusion matrix, and ROC–AUC  
- Feature importance / model interpretation  

---

## Results
- Logistic Regression: Accuracy ~0.80, F1-score (>50K) ~0.68  
- Random Forest: Accuracy ~0.82, F1-score (>50K) ~0.70  
- XGBoost: Accuracy ~0.84, F1-score (>50K) ~0.73  

Tree-based ensemble models outperform the logistic regression baseline.  
XGBoost achieves the best overall performance for predicting high-income individuals.
