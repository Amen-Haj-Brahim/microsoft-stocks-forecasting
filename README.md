# Microsoft Stock Forecasting

A time-series forecasting project that predicts Microsoft stock prices using both classical and machine learning methods.

### Exploratory Analysis

- Time-series visualization and decomposition
- Stationarity testing (ADF, KPSS)
- Feature engineering (lags, rolling statistics, seasonality)

### Classical Methods

- **ARIMA**: AutoRegressive Integrated Moving Average
- **SARIMA**: Seasonal ARIMA with trading day seasonality
- **SARIMAX**: SARIMA with exogenous variables (Open, High, Low, Volume)

### Machine Learning Models

- Linear Regression
- Ridge Regression
- Random Forest
- XGBoost (with hyperparameter tuning)

## Metrics

Models are evaluated on an 80-20 train-test split using:

- Mean Absolute Error (MAE)
- Root Mean Squared Error (RMSE)

## Features : Date, Open, High, Low, Close, Volume
"# microsoft-stocks-forecasting" 
