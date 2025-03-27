# Stock Price Prediction – Microsoft (2010–2024)

This project applies machine learning models to forecast daily percentage changes in Microsoft (MSFT) stock prices using historical data from 2010 to 2024.

## 🔍 Overview
- Models: Linear Regression, Random Forest, Gradient Boosting
- Features: High/Low difference, Close/Open difference, Lag_1 to Lag_10
- Target: Adjusted Close Percentage Change
- Tools: scikit-learn, RandomizedSearchCV, yfinance

## 📈 Results
- Gradient Boosting achieved best performance: R² ≈ 0.43
- Feature importance: Close-Open difference and lagged returns were most predictive
- Models significantly outperformed baseline (Lag_1)

## 📊 Evaluation
- Metrics: MSE, MAE, R²
- TimeSeriesSplit used to avoid data leakage
- Residual analysis and feature importance visualizations included

## 🧰 Tech Stack
- Python, Pandas, NumPy, scikit-learn
- Matplotlib, seaborn
- Yahoo Finance API (via `yfinance`)

## 📄 Full Report
See [Full_Report.pdf](Full_Report.pdf) for full methodology, results, and visualizations.

## Author
**Alen Šahinpašić**  
alensahinpasic@gmail.com
