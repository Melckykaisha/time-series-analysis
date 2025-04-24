# Tesla Stock Time Series Forecasting

This project involves time series analysis of **Tesla (TSLA)** stock prices using ARIMA and GARCH models. The analysis is part of a course assignment, and it demonstrates key steps in forecasting and volatility modeling using Python.

## 📊 Contents

- Download of historical stock prices using `yfinance`
- Stationarity checks using the Augmented Dickey-Fuller (ADF) test
- Autocorrelation analysis using ACF and PACF plots
- ARIMA modeling for forecasting
- GARCH modeling for volatility analysis
- Interpretation of results and model comparison

## 📈 Models Used

- **ARIMA(1,1,0)**: Based on differencing and ACF/PACF diagnostics
- **GARCH(1,1)**: Applied to model volatility clustering in returns

## 📦 Libraries Used

- `pandas`, `numpy`, `matplotlib`, `seaborn`
- `yfinance` for data fetching
- `statsmodels` for ARIMA modeling
- `arch` for GARCH modeling
