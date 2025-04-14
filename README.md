# 📉 Loan Default Prediction

A machine learning project focused on predicting loan default risk based on borrower data. The goal is to build a robust classification model that can help financial institutions identify high-risk clients and reduce potential losses.

## 📂 Project Overview

- 🔍 Performed Exploratory Data Analysis (EDA) to understand patterns and distributions
- ⚖️ Addressed class imbalance using the `class_weight` parameter
- 🧠 Used Gradient Boosting as the core model
- 🎯 Applied hyperparameter tuning with `RandomizedSearchCV`
- 📊 Evaluated model performance using multiple classification metrics

## 📊 Dataset

The dataset was sourced from Kaggle:  
[Loan Default Dataset](https://www.kaggle.com/datasets/yasserh/loan-default-dataset/data)

It includes client information such as income, employment status, education level, and loan default labels.

## 🧪 Evaluation Metrics

- **Accuracy**
- **ROC-AUC**
- **Recall**
- **Precision**

## 🛠️ Technologies Used

- `pandas`, `numpy`
- `scikit-learn`
- `matplotlib`, `seaborn`
- `xgboost` 

## 🚀 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/your_username/loan-default-prediction.git
   cd loan-default-prediction
