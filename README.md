Lending Club Loan Approval – Model Evaluation
📌 Project Overview

This project evaluates machine learning models for loan approval prediction using the Lending Club loan dataset.
The goal is to assess model performance, compare algorithms, and identify the best approach for predicting whether a loan will be Fully Paid or Charged Off.

Problem Statement

Given borrower and loan attributes, predict loan repayment status to help lenders:
 - Reduce default risk
 - Improve approval decisions
 - Understand key factors influencing loan outcomes

Models Evaluated
Logistic Regression
Decision Tree
Random Forest
Gradient Boosting / XGBoost (if applicable)

Models are evaluated using:
Accuracy
Precision
Recall
F1-Score
ROC-AUC

Key Steps in the Notebook
Data loading and inspection
Data cleaning and preprocessing
Feature engineering and encoding
Train-test split
Model training
Model evaluation and comparison
Performance visualization
Confusion Matrix
Special attention is given to Recall for defaulters, as minimizing false approvals is critical in lending decisions.

Libraries Used
Python 3.x
pandas
numpy
scikit-learn
matplotlib / seaborn

Install dependencies:
pip install pandas numpy scikit-learn matplotlib seaborn

Open the notebook:
jupyter notebook lending_club_loan_evaluation.ipynb

Run cells sequentially

Results Summary
Tree-based models generally outperform linear models
Feature importance highlights credit score, loan grade, and debt-to-income ratio as strong predictors
Trade-off observed between precision and recall depending on model choice

