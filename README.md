# 📈 stock-forecasting-yahoo-finance-analysis

Time series-based stock price forecasting for Tesla (TSLA) using Facebook Prophet. This project covers data extraction from Yahoo Finance, exploratory data analysis, monthly and yearly returns, model training, forecasting, and performance evaluation (MAE: 0.046, RMSE: 0.057).

---

## 📌 Overview
This project focuses on forecasting stock prices using Time Series Analysis and Facebook Prophet.  
The model is applied to Tesla (TSLA) stock data to analyze trends, patterns, and predict future prices.

---

## 📊 Dataset
- Source: Yahoo Finance (via yfinance API)
- Stock: Tesla (TSLA)
- Features:
  - Open
  - High
  - Low
  - Close
  - Volume

---

## ⚙️ Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- yfinance
- Facebook Prophet
- Scikit-learn

---

## 🔍 Project Workflow
1. Data collection from Yahoo Finance  
2. Data preprocessing and cleaning  
3. Exploratory Data Analysis (EDA)  
4. Monthly and yearly returns calculation  
5. Time Series modeling using Prophet  
6. Forecasting future stock prices  
7. Model evaluation using error metrics  

---

## 📉 Model
- Algorithm: Facebook Prophet  
- Forecast horizon: 24 months  
- Seasonality: Daily enabled  

---

## 📈 Results
- Mean Absolute Error (MAE): 0.046  
- Root Mean Squared Error (RMSE): 0.057  

---

## 📊 Visualization
The project includes:
- Closing price trends  
- Monthly averages  
- Forecasted values with confidence intervals  
