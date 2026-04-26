# 📈 stock-forecasting-yahoo-finance-analysis

Time series-based stock price forecasting for Tesla (TSLA) using Facebook Prophet. This project covers data extraction from Yahoo Finance, exploratory data analysis, feature engineering, model training, forecasting, and performance evaluation.

---

## 📌 Overview
This project applies time series analysis techniques to forecast Tesla (TSLA) stock prices using Facebook Prophet. It includes end-to-end workflow from data collection to model evaluation, highlighting trends, seasonality, and predictive performance.

---

## 📊 Dataset
- Source: Yahoo Finance (via yfinance API)
- Stock: Tesla (TSLA)
- Time Period: 2017 – 2023
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
4. Feature engineering (returns, log transformation)  
5. Time Series modeling using Prophet  
6. Forecasting future stock prices (24 months horizon)  
7. Model evaluation using error metrics  

---

## 📉 Model
- Algorithm: Facebook Prophet  
- Forecast horizon: 24 months  
- Seasonality: Daily enabled  
- Transformation: Log transformation applied to stabilize variance  

---

## 📊 Results

The Prophet model demonstrated strong forecasting performance:

- Mean Absolute Error (MAE): **0.046**
- Root Mean Squared Error (RMSE): **0.057**
- Mean Squared Error (MSE): **1.31**

---

## 📈 Key Insights

- Achieved **low prediction error**, indicating reliable forecasts  
- Model closely tracks actual stock price trends  
- Prophet effectively captures **trend and seasonality**  
- Log transformation improves stability and prediction accuracy  
- Suitable for long-term forecasting with uncertainty intervals  

---

## 📊 Visualizations
The project includes:
- Closing price trends over time  
- Weekly and monthly aggregations  
- Monthly and yearly returns analysis  
- Forecast with confidence intervals  
- Trend and seasonality decomposition

---

## Licence
<span style="font-size:0.9em; white-space:nowrap;">
  <a href="https://github.com/AsrarQassem/stock-forecasting-yahoo-finance-analysis">stock-forecasting-yahoo-finance-analysis</a> © 2024 by 
  <a href="https://github.com/AsrarQassem">Asrar Qassem</a> · 
  <a href="https://creativecommons.org/licenses/by-nc-sa/4.0/">CC BY-NC-SA 4.0</a>

  <img src="https://mirrors.creativecommons.org/presskit/icons/cc.svg" style="width:14px;height:14px;vertical-align:-2px;margin-left:4px;">
  <img src="https://mirrors.creativecommons.org/presskit/icons/by.svg" style="width:14px;height:14px;vertical-align:-2px;">
  <img src="https://mirrors.creativecommons.org/presskit/icons/nc.svg" style="width:14px;height:14px;vertical-align:-2px;">
  <img src="https://mirrors.creativecommons.org/presskit/icons/sa.svg" style="width:14px;height:14px;vertical-align:-2px;">
</span>
