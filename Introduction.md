---
marp: true
---

# Binary Classification for Credit Card Fraud Detection

Rafał Leja 
Hanna Makowska

---

# Introduction

- Credit card fraud detection is a binary classification problem
- The dataset contains transactions made by credit cards in September 2013 by European cardholders
- The dataset is highly unbalanced, the positive class (frauds) account for 0.172% of all transactions
- The dataset contains only numerical input variables which are the result of a PCA transformation

---

# Data

- The dataset contains 284,807 transactions and only of them are fraudulent
- The dataset contains 30 features:
  - Time
  - Amount
  - V1, V2, ..., V28 - PCA transformed features
- V1, V2, ..., V28 are:
  - Linearly uncorrelated
  - Decrementally ordered by the percentage of variance they explain

---

# Goals

- Train multiple models on the dataset
- Evaluate and compare the models
- Choose the best model using AUC-ROC score

---

# Tasks

- Data preprocessing e.g. scaling, splitting
- Model selection e.g. Logistic Regression, K-Nearest Neighbors and others
- Model training
- Model evaluation
- Model comparison

---

# Tools and libraries
- scikit-learn
- pandas
- numpy
- matplotlib
- seaborn