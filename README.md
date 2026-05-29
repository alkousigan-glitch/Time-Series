# Furniture Sales Forecasting — SARIMA

Forecasting monthly furniture sales for a retail superstore using time series modeling.

---

## Problem Statement
A superstore needs to predict future furniture sales to manage inventory, avoid overstock/understock, and plan procurement effectively.

## Dataset
- **File:** `Super_Store.csv`
- **Period:** January 2014 – December 2017
- **Target:** Monthly Furniture Sales

## Tech Stack
`pandas` · `numpy` · `matplotlib` · `statsmodels` · `pmdarima` · `scikit-learn`

## Model
**SARIMA(0,0,0)(2,1,0,12)** — parameters selected automatically via Auto ARIMA.

## Results
- Clear upward trend with annual seasonality detected
- Seasonal differencing applied after ADF stationarity test
- Model evaluated on 2017 test set using MAPE & MSE
- 12-month forecast generated for 2018
