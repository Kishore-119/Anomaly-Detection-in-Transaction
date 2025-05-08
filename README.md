# 🕵️ Anomaly Detection in Transactions using Python

This project demonstrates how to detect anomalies in financial transaction data using machine learning. It involves exploratory data analysis, statistical thresholding, and the Isolation Forest algorithm to identify suspicious transactions.

---

## 📌 Features

- Cleaned and analyzed a transaction dataset
- Visualized transaction patterns using Plotly
- Identified anomalies with statistical thresholds
- Trained an Isolation Forest model to detect anomalies
- Evaluated model performance using precision, recall, and F1-score
- Built an interactive input system for real-time anomaly prediction

---

## 🧰 Tools & Libraries

- Python
- Pandas, NumPy
- Plotly (for visualizations)
- Scikit-learn (for modeling)

---

## 📊 Dataset

A synthetic dataset simulating transaction behaviors. It includes:
- Transaction Amounts
- Average and Frequency Metrics
- Temporal data (Time, Day)
- Demographic info (Age, Gender, Income)
- Account Type

---

## 🚀 How to Run

1. Clone the repo:
   ```bash
   git clone https://github.com/your-username/transaction-anomaly-detection.git
   cd transaction-anomaly-detection

## 🔍 Results
- Achieved 100% precision and recall on test data (with 2% contamination).

- Successfully flagged outliers based on transaction behavior.

- Enabled real-time anomaly checks via user input.


##📈 Example Use Case
- Input
Enter the value for 'Transaction_Amount': 10000  
Enter the value for 'Average_Transaction_Amount': 900  
Enter the value for 'Frequency_of_Transactions': 6  
- Output
> Anomaly detected: This transaction is flagged as an anomaly.
