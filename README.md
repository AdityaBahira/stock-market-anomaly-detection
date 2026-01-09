# Stock Market Anomaly Detection

## Overview
This project detects unusual stock and market behavior using historical price and volume data.
It is an unsupervised anomaly detection system developed as an MSc Data Science capstone project.

## Key Features
- Leakage-safe rolling feature engineering
- Rule-based anomaly detection
- K-Means and DBSCAN based anomaly detection
- Market-level stress indicators
- Date query and monthly mini-report

## Dataset
- Daily OHLCV stock market data (Kaggle)
- Adjusted Close used for return calculations
- Train: 2018 | Validation: 2019 | Test: 2020 Q1

## Anomaly Types
- Crash
- Price Spike
- Volume Shock

## Outputs
- Daily anomaly card (CSV)
- Market-day summary table
- Date-based anomaly query
- Monthly mini-report

## Technologies Used
- Python
- Pandas, NumPy
- Scikit-learn
- Matplotlib

## Academic Note
This project is for educational purposes only and does not constitute investment advice.
