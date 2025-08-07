# Credit_Card_Anomaly_Detection

This project applies unsupervised machine learning techniques — **Isolation Forest** and **Local Outlier Factor (LOF)** — to detect credit card fraud in an imbalanced dataset. We focus on identifying fraudulent transactions (anomalies) without relying on labeled training data.

---

## Dataset
- **Source:** [Kaggle - Credit Card Fraud Detection](https://www.kaggle.com/mlg-ulb/creditcardfraud)
- **Description:** European credit card transactions in September 2013.
- **Size Used:** 10% sample (≈5,000 transactions).
- **Target Column:** Class
  - 0: Valid transaction
  - 1: Fraudulent transaction

## Methodes Used
- Isolation Forest
- LocalOutlierFactor

## Evaluation Metrics 

| Metric              | Isolation Forest        | Local Outlier Factor   |
|---------------------|-------------------------|-------------------------|
| Accuracy            | 99.93%                  | **99.87%**              |
| Precision (Fraud)   | 1.00                   | **0.50**                |
| Recall (Fraud)      | 0.50                    | **0.50**                |
| F1-Score (Fraud)    | 0.67                    | **0.50**                |

## Tools & Libraries
- Python
- pandas, numpy
- scikit-learn
- matplotlib, seaborn

## How to Run

1. Clone this repository
2. Upload your `kaggle.json` for dataset access
3. Run the Jupyter notebook or Python script
