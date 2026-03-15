# AMDOX-INTERNSHIP-PROJECT2
# Credit Card Fraud Detection

## 📌 Project Overview
Credit card fraud costs financial institutions billions of dollars annually. This project implements a Machine Learning pipeline to identify fraudulent transactions based on historical data. Using a Random Forest Classifier, the model analyzes patterns in transaction amounts, locations, and types to flag suspicious activity.

## 📊 Dataset Description
The model uses `credit_card_fraud_dataset.csv`, which contains the following features:

| Feature | Description |
| :--- | :--- |
| **TransactionID** | Unique identifier for each transaction |
| **TransactionDate** | Date and time of the transaction |
| **Amount** | The monetary value of the transaction |
| **MerchantID** | Identifier for the merchant involved |
| **TransactionType** | Category of transaction (e.g., Purchase, Refund) |
| **Location** | The city where the transaction occurred |
| **IsFraud** | Target variable (1 for Fraud, 0 for Legitimate) |
