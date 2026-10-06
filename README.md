# Credit Card Fraud Detection

## 📌 Project Overview

This project focuses on detecting fraudulent credit card transactions using machine learning classification techniques.

The project compares three machine learning models:

- Logistic Regression
- Random Forest
- XGBoost

The dataset is highly imbalanced, so **SMOTE (Synthetic Minority Over-sampling Technique)** is used to address class imbalance in the training data.

---

## 🎯 Objectives

The main objectives of this project are:

- Analyze credit card transaction data.
- Understand the class imbalance between normal and fraudulent transactions.
- Perform Exploratory Data Analysis (EDA).
- Apply feature scaling.
- Handle class imbalance using SMOTE.
- Train multiple machine learning classification models.
- Evaluate and compare model performance.

---

## 📊 Dataset

The dataset used in this project is the **Credit Card Fraud Detection dataset** obtained from Kaggle.

### Dataset Source

**Kaggle – Credit Card Fraud Detection**

### Dataset Features

The dataset contains transaction-related features including:

- V1 to V28
- Amount
- Class

### Target Variable

The `Class` column is the target variable:

- `0` → Normal transaction
- `1` → Fraudulent transaction

> The dataset is not included in this repository because of its large size.

---

## ⚖️ Class Imbalance

Credit card fraud datasets are highly imbalanced because fraudulent transactions represent only a small proportion of all transactions.

To handle this problem, **SMOTE** is applied to the training data to generate synthetic samples for the minority class.

---

## 🤖 Machine Learning Models

Three classification models are used:

### 1. Logistic Regression

Used as a baseline classification model for detecting fraudulent transactions.

### 2. Random Forest

An ensemble learning algorithm used to improve classification performance and capture complex relationships.

### 3. XGBoost

A powerful gradient-boosting algorithm used for high-performance classification.

---

## ⚙️ Project Workflow

```text
Data Loading
     ↓
Data Inspection
     ↓
Exploratory Data Analysis
     ↓
Class Imbalance Analysis
     ↓
Feature Scaling
     ↓
Train-Test Split
     ↓
SMOTE
     ↓
Model Training
     ↓
Model Evaluation
     ↓
Model Comparison
