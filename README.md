# 🕵️‍♂️ Credit Card Fraud Detection using Machine Learning

This project focuses on detecting fraudulent financial transactions using supervised machine learning. It uses anonymized real-world data to build models that can distinguish between fraudulent and legitimate transactions.

---

## 📂 Project Contents

- `fraud_detection.ipynb` – End-to-end Jupyter notebook with data cleaning, EDA, feature engineering, model training, and evaluation
- `README.md` – Project overview and key insights

- ❗ **Dataset not included due to size constraints. See below for access.**

---

## 🧠 Problem Statement

> Given a dataset of financial transactions, build a predictive model that flags fraudulent transactions. The goal is to minimize false positives while capturing the majority of fraudulent activity.

---

## 📊 Dataset Description

The dataset contains millions of transaction records with:
- Transaction metadata (`step`, `amount`, `oldbalanceOrg`, `newbalanceDest`, etc.)
- Transaction type (e.g., `CASH_OUT`, `TRANSFER`)
- Binary label: `isFraud` (1 = fraud, 0 = normal)

---

## ⚠️ Dataset Access

Due to GitHub's file size limits, the dataset is not uploaded here.

🔧 Techniques Used
Exploratory Data Analysis (Boxplots, Heatmaps, Class Imbalance Analysis)

Feature Engineering (handling outliers, correlation filtering)

Class Imbalance Handling (Downsampling + SMOTE)

Model Training:

Random Forest Classifier

Evaluation with classification metrics

Visualization (Confusion matrix, feature importance)

✅ Model Results (Sample)
Metric	Score
Accuracy	98.6%
Precision	97.0%
Recall	99.5%
F1 Score	98.3%

💡 Insights
Fraudulent transactions are highly imbalanced (~1% fraud)

Transaction type and amount are strong predictors of fraud

SMOTE significantly improved recall on minority class

Random Forest was chosen for its performance and interpretability

🚀 Next Steps
Deploy model as a REST API for real-time fraud detection

Use anomaly detection or unsupervised learning for unknown fraud patterns

Explore cost-sensitive learning (to reduce cost of false positives)

👤 Author
Alwin Shaji



