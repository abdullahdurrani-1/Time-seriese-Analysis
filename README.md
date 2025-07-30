# Time-seriese-Analysis
# 🌦️ Weather Forecasting Using Machine Learning (Random Forest Regression)

## 🔍 Project Overview

This project predicts future temperature using historical weather data (humidity, wind speed, solar radiation, etc.) by training a **RandomForestRegressor**. It also includes **feature engineering**, **data visualization**, and **model evaluation**.

## 📁 Dataset

- Combined multiple CSV files with hourly weather data.
- Columns include: `Temperature`, `Humidity`, `Dew`, `Solar Radiation`, `Wind Speed`, `Pressure`, and time-based features (`hour`, `day`, `month`, etc.).

## 🧪 ML Model

- Model: `RandomForestRegressor`
- Features used:
  - Weather: Humidity, Wind Speed, Solar Radiation, Dew, etc.
  - Time: hour, day, month, dayofweek
- Target: **Temperature (°C)**

## 📊 Results

| Metric | Score |
|--------|-------|
| MAE    | 0.096 |
| MSE    | 0.080 |
| R²     | 0.998 ✅ |

## 📈 Visuals

- Actual vs Predicted plot
- Residual error trends
- Feature importance chart

## 🧠 Key Insights

- Model captured temperature trends with near-perfect accuracy.
- Time features and solar radiation were most important.


