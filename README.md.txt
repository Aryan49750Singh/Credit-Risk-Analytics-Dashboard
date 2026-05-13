# Credit Risk Analytics & Default Prediction Dashboard

## Overview
This project focuses on predicting customer default risk using machine learning and financial risk analytics techniques. The analysis was performed on a dataset containing 30,000+ customer financial records.

The objective was to identify high-risk customers, analyze repayment behavior, and improve risk monitoring using predictive analytics.

---

## Problem Statement
Financial institutions face significant losses due to customer defaults. This project aims to:
- Predict customer default probability
- Identify key financial risk indicators
- Analyze repayment behavior patterns
- Improve minority-risk detection using machine learning

---

## Dataset Information
- Dataset: UCI Credit Card Default Dataset
- Total Records: 30,000+
- Features: Customer demographics, billing history, repayment history, payment amounts, credit limits
- Target Variable: 'default.payment.next.month'

---

## Tech Stack
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- XGBoost
- Imbalanced-learn (SMOTE)

---

## Project Workflow

### 1. Data Cleaning & Preprocessing
- Removed unnecessary columns
- Checked missing values
- Prepared structured dataset for analysis

### 2. Exploratory Data Analysis
- Default distribution analysis
- Correlation heatmap
- Repayment behavior analysis
- Feature relationship visualization

### 3. Class Imbalance Handling
- Applied SMOTE (Synthetic Minority Oversampling Technique)
- Improved minority-risk detection capability

### 4. Model Building
Models used:
- Random Forest Classifier
- XGBoost Classifier

### 5. Model Evaluation
Evaluation metrics used:
- Accuracy
- Precision
- Recall
- F1-Score
- ROC-AUC Score

---

## Results

### Random Forest Performance
- Accuracy: 79%
- ROC-AUC Score: 0.679

### XGBoost Performance
- Accuracy: 77%
- ROC-AUC Score: 0.678

---

## Key Insights
- Payment delay variables (`PAY_0` to `PAY_6`) were among the strongest predictors of customer default risk.
- Customers with delayed repayment history showed significantly higher default probability.
- Financial repayment behavior strongly influences customer risk profiles.
- SMOTE improved minority-risk detection and helped balance the dataset.

---

## Feature Importance Analysis
Feature importance analysis showed that repayment history and billing behavior were major indicators of customer default risk.

---

## Project Structure

```bash
Credit-Risk-Analytics-Dashboard/
│
├── Credit_Risk_Analytics.ipynb
├── credit_risk_cleaned.csv
├── requirements.txt
├── README.md
└── screenshots/
```

---

## Screenshots

### Default Distribution

### Correlation Heatmap

### Feature Importance

### Classification Report

---

## Future Improvements
- Hyperparameter tuning
- Streamlit deployment
- Real-time risk monitoring dashboard
- Advanced ensemble modeling
- Explainable AI techniques

---

## Author
Aryan Singh
