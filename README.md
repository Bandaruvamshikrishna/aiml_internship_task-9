Random Forest – Credit Card Fraud Detection

This project implements fraud detection using machine learning models
on two datasets as part of AI & ML Internship Task 9.

Datasets:
1. creditcard.csv (Kaggle Credit Card Fraud Dataset)
2. fraud_small.csv (alternative small dataset)

Models Used:
Logistic Regression (baseline)
Random Forest Classifier

Steps:
Loaded datasets and checked class imbalance
Separated features and target column
Used stratified train-test split
Trained Logistic Regression baseline model
Trained Random Forest model
Evaluated using precision, recall and F1-score
Plotted feature importance
Saved trained models

Files:
fraud_kaggle.py
small_dataset_code.py
creditcard.csv
fraud_small.csv
rf_model.pkl
rf_small_model.pkl
README.txt

How to Run:
python fraud_kaggle.py
python small_dataset_code.py
