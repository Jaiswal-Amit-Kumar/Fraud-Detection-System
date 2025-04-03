# Fraud Detection System using Anomaly Detection

Detects 98% of fraudulent transactions using machine learning anomaly detection techniques.

## Features
- Data preprocessing and visualization
- Handling imbalanced data using SMOTE/ADASYN
- Isolation Forest anomaly detection
- Performance metrics visualization
- Feature importance analysis

## Dataset
Credit Card Fraud Detection dataset from Kaggle:
- Contains 284,807 transactions
- 31 numerical features (V1-V28 are PCA transformed)
- Class imbalance: 0.172% frauds

## Results
- Achieved 98% recall on fraudulent transactions
- Precision-Recall AUC: 0.85
- Isolation Forest outperformed other anomaly detection methods

Download dataset from [Kaggle](https://www.kaggle.com/mlg-ulb/creditcardfraud) and place in `data/` directory


## Installation
```bash
git clone https://github.com/yourusername/fraud-detection-system.git
cd fraud-detection-system
pip install -r requirements.txt
