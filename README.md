
# 🛒 E-Commerce Fraud Detection System

![Python](https://img.shields.io/badge/Python-3.9+-blue)
![XGBoost](https://img.shields.io/badge/XGBoost-Latest-green)
![Scikit-Learn](https://img.shields.io/badge/ScikitLearn-Latest-orange)
![Status](https://img.shields.io/badge/Status-Active-brightgreen)

## 📌 Project Overview

This project builds an **end-to-end Machine Learning pipeline** to detect fraudulent 
e-commerce transactions. It uses real-world transaction data to identify fraud patterns 
using supervised learning techniques including **XGBoost**, **Random Forest**, and 
**Logistic Regression**.

The project directly addresses the challenge of **class imbalance** (fraud is rare — 
only ~0.17% of transactions) using **SMOTE** and evaluates models using fraud-specific 
metrics like **Precision**, **Recall**, **F1 Score**, and **AUC**.

---

## 🎯 Problem Statement

E-commerce fraud costs businesses billions of dollars every year. 
Fraudsters use stolen credit cards, fake accounts, and automated bots 
to make unauthorized purchases.

**Goal:** Build a machine learning model that:
- Detects fraud with **high Recall** (catch as many fraudsters as possible)
- Minimizes **False Positives** (don't block innocent customers)
- Runs efficiently at **scale** (millions of transactions per day)

---

## 📊 Dataset

- **Source:** [Kaggle Credit Card Fraud Detection](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud)
- **Size:** 284,807 transactions
- **Fraud Cases:** 492 (0.17%) ← Classic class imbalance!
- **Features:** 30 anonymized transaction features + Amount + Time

  ## 🚀 ML Pipeline
Raw Transaction Data

↓

Exploratory Data Analysis

↓

Feature Engineering

↓

Handle Class Imbalance (SMOTE)

↓

Train Models (Logistic Regression, Random Forest, XGBoost)

↓

Evaluate (Confusion Matrix, Precision, Recall, F1, AUC)

↓

Deploy Best Model
