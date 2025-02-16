# 🛒 Walmart Sales Forecasting

## 📖 Overview
This project analyzes Walmart's sales data using **Time-Series Forecasting** and **Machine Learning Models**. It combines **ARIMA** for time-series predictions and **Random Forest** for sales prediction based on external economic factors.

## 📊 Key Features
- **Exploratory Data Analysis (EDA)**: Visualization of sales trends over time.
- **Time-Series Forecasting**: Uses **Auto-ARIMA** to predict future sales.
- **Machine Learning Model**: Implements **Random Forest** for sales prediction.
- **Feature Engineering**: Incorporates external factors like temperature, fuel prices, CPI, and unemployment.
- **Model Evaluation**: Compares actual vs. predicted sales with **RMSE and MAE**.
- **Business Insights**: Recommendations for improving Walmart's inventory and pricing strategies.

## 📁 Dataset
The project utilizes the following datasets:
- `train.csv` - Weekly sales data for each store.
- `stores.csv` - Store details (size, location, type, etc.).
- `features.csv` - External economic data (CPI, fuel prices, etc.).
- `test.csv` - Used for testing a ML model.

## 🚀 Installation & Setup
### 1️⃣ Prerequisites
Ensure you have R and the required libraries installed.

### 2️⃣ Install Required Libraries
Run the following command in R to install dependencies:
```r
install.packages(c("tidyverse", "lubridate", "forecast", "tseries", "TTR", "randomForest", "caret", "ggplot2", "gridExtra"))

