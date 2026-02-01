# Proactive Fraud Detection System

## Overview
This project builds a machine learning–based system to proactively detect fraudulent financial transactions. The solution handles severe class imbalance and provides both technical and business-level insights.

## Problem Statement
Fraudulent transactions are rare but highly costly. The goal is to accurately detect fraud while minimizing false negatives and maintaining model interpretability.

## Dataset
- Binary target: isFraud
- Highly imbalanced dataset (~0.13% fraud cases)

## Approach
- Data cleaning (missing values, outliers, multicollinearity)
- Feature engineering and selection
- Machine learning classification model
- Threshold tuning for business requirements
- Model evaluation using industry-standard metrics

## Model Performance
- ROC-AUC: ~0.99
- High recall for fraud cases
- Threshold optimization performed

## Key Fraud Indicators
- Unusual transaction amounts
- High-risk transaction patterns
- Abnormal account balance changes

## Business Recommendations
- Real-time fraud monitoring
- Hybrid rule-based and ML detection
- Periodic model retraining
- Automated alerts for high-risk transactions

## Limitations
- Extreme class imbalance affects precision
- Requires regular retraining

## Tech Stack
- Python
- Pandas, NumPy
- Scikit-learn

## Outcome
A scalable and interpretable fraud detection solution suitable for real-world deployment.
