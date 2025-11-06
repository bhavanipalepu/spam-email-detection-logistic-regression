# Spam Email Detection Using Logistic Regression

This project focuses on detecting spam emails using **Logistic Regression** with data preprocessing, feature selection, and model optimization techniques.

## What I Did
- Cleaned and preprocessed the UCI Spambase dataset.  
- Performed feature selection using **Recursive Feature Elimination (RFE)**.  
- Built and trained a **Logistic Regression model** for spam classification.  
- Tuned hyperparameters using **GridSearchCV** and evaluated results using metrics like Accuracy, Precision, Recall, F1, and ROC-AUC.

## How I Did It
- Tools: **Python, Jupyter Notebook**  
- Libraries: **Pandas, NumPy, Scikit-learn, Matplotlib**  
- Implemented in two main steps:
  1. `data_preprocessing.ipynb` – handled missing values, normalization, and encoding  
  2. `model_development.ipynb` – trained and optimized the logistic regression model  

## Outcome
Achieved ~93% accuracy with balanced precision and recall.  
Validated model stability through optimization and performance metrics.

---

*This repository contains only code notebooks — dataset link:*  
[UCI Machine Learning Repository – Spambase Dataset](https://archive.ics.uci.edu/dataset/94/spambase)
