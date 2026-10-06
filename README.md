Credit Card Fraud Detection
📌 Project Overview
This project focuses on detecting fraudulent credit card transactions using machine learning classification techniques.

The project compares three machine learning models:

Logistic Regression
Random Forest
XGBoost
The dataset is highly imbalanced, so SMOTE (Synthetic Minority Over-sampling Technique) is used to address the class imbalance in the training data.

🎯 Objectives
The main objectives of this project are:

Analyze credit card transaction data
Understand the class imbalance between normal and fraudulent transactions
Perform exploratory data analysis
Apply feature scaling
Handle class imbalance using SMOTE
Train multiple machine learning classification models
Evaluate and compare model performance
📊 Dataset
The dataset used in this project was obtained from Kaggle and is the Credit Card Fraud Detection dataset.

Dataset Source: Kaggle - Credit Card Fraud Detection

The dataset contains transaction-related features including:

Time
V1 to V28
Amount
Class
The Class column is the target variable:

0 → Normal transaction
1 → Fraudulent transaction
The dataset is not included in this repository because of its large size.

🛠️ Technologies Used
Python
Jupyter Notebook
Pandas
NumPy
Matplotlib
Seaborn
Scikit-learn
XGBoost
Imbalanced-learn
🔄 Project Workflow
Data Loading
     ↓
Data Inspection
     ↓
Exploratory Data Analysis
     ↓
Class Imbalance Analysis
     ↓
Train-Test Split
     ↓
Feature Scaling
     ↓
SMOTE
     ↓
Model Training
     ↓
Model Evaluation
     ↓
Model Comparison
