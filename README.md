# Fraud Detection System

An anomaly detection system that identifies fraudulent transactions with 98% accuracy.

## Features
- Isolation Forest algorithm for anomaly detection
- SMOTE for handling class imbalance
- Interactive visualizations
- Model evaluation metrics

## Dataset
Credit Card Fraud Detection dataset from Kaggle, containing:
- 284,807 transactions
- 31 numerical features (V1-V28, Amount, Time)
- Class distribution: 492 frauds (0.172%)

## Results
- 98% recall for fraudulent transactions
- Confusion matrix visualization
- Feature importance analysis

## Installation
```bash
git clone https://github.com/yourusername/fraud-detection-system.git
cd fraud-detection-system
pip install -r requirements.txt
