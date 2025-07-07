#  Stock Price Forecasting using Machine Learning (Tesla)

This project focuses on forecasting **Tesla (TSLA)** stock prices using various machine learning and time series models. It explores how well different models can predict future stock trends and evaluates their performance using statistical error metrics.

##  Models Used

- **Facebook Prophet**
- **ARIMA / SARIMA**
- **VARIMA** (using Tesla and Apple stock relationships)

##  Key Features

- Time-series forecasting for **Tesla stock**
- Evaluation of models using:
  -  RMSE (Root Mean Square Error)
  -  MAPE (Mean Absolute Percentage Error)
  -  MAE, MSE, AIC, BIC
- Visual comparison of actual vs predicted prices
- Rolling forecast plots with confidence intervals
- Stationarity tests and data preprocessing
- Data decomposition (trend, seasonality, noise)

##  Tools & Technologies

- **Python**
- **Google Colab**
- **Facebook Prophet**
- **statsmodels**
- **pmdarima**
- **matplotlib / seaborn**
- **yfinance** (for fetching stock data)

##  Dataset

Stock data was sourced using the **Yahoo Finance API** via `yfinance` library. Primary focus was on **Tesla (TSLA)** with multivariate forecasting involving **Apple (AAPL)** in some models.

##  Screenshots

*(Add plots or screenshots here using: `![Alt Text](path-to-image)`)*

## 📌 Objective

To build a machine learning pipeline that forecasts stock prices with reasonable accuracy using time-series data, and to compare classical statistical models with modern ML-based forecasting techniques.
