# Daily Retail Sales Time Series Analysis

This project focuses on analyzing daily retail sales data using time series analysis techniques in Python. The goal is to understand sales trends, seasonal patterns, stationarity, and temporal dependencies to support forecasting and business insights.

---

## 📊 Features

- Daily sales visualization over time
- Handling missing dates using fixed daily frequency
- Trend, seasonality, and residual decomposition
- Stationarity testing using Augmented Dickey-Fuller (ADF) test
- Rolling mean and rolling standard deviation analysis
- Autocorrelation (ACF) and Partial Autocorrelation (PACF) plots

---

## 🛠️ Technologies Used

- Python
- Pandas
- Matplotlib
- Statsmodels
- Scikit-learn (for preprocessing support)

---


---

## 📈 Time Series Analysis Steps

### 1. Data Preparation
- Sales data indexed by date
- Sorted chronologically
- Converted to daily frequency using `asfreq('D')`

### 2. Visualization
- Line plot showing daily retail sales over time

### 3. Decomposition
- Additive decomposition into:
  - Trend
  - Seasonality (30-day cycle)
  - Residual noise

### 4. Stationarity Check
- Augmented Dickey-Fuller (ADF) test
- Rolling mean and rolling standard deviation visualization

### 5. Autocorrelation Analysis
- ACF plot to observe overall lag correlation
- PACF plot to observe direct lag influence

---

## 📌 Key Learnings

- How to preprocess and structure time series data
- Identifying trends and seasonal patterns in sales
- Understanding stationarity and its importance in forecasting
- Using ACF and PACF for model selection (ARIMA)

---




