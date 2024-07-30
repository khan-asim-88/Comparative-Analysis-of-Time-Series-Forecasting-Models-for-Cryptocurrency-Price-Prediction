# Comparative Analysis of Time Series Forecasting Models for Cryptocurrency Price Prediction

This repository contains the implementation of the project "Comparative Analysis of Time Series Forecasting Models for Cryptocurrency Price Prediction." The project aims to compare the performance of various time series forecasting models (LSTM, GRU, SARIMAX, and Prophet) in predicting Bitcoin prices.

## Project Structure

- **Code.ipynb**: Jupyter notebook containing the implementation of data fetching, exploration, preparation, modeling, evaluation, and forecasting using LSTM, GRU, SARIMAX, and Prophet models.
- **Fetched_BTC_Data_V1.xlsx**: Excel file containing the fetched Bitcoin price data from Yahoo Finance.
- **README.md**: This file is the information file of the repository.

## Project Objectives

- Develop and train LSTM, GRU, SARIMAX, and Prophet models for Bitcoin price forecasting.
- Evaluate the performance of each model using various metrics (MAE, MSE, RMSE, R-squared).
- Compare the forecasting accuracy of the models and identify the most effective model for Bitcoin price prediction.

## Data Collection

Historical Bitcoin price data has been collected from Yahoo Finance using the `yfinance` Python library. The dataset includes daily Bitcoin price data from October 2014 to May 2024.

## Models Implemented

### 1. Long Short-Term Memory (LSTM)

LSTM models are a type of Recurrent Neural Network (RNN) specifically designed for sequence prediction problems. They can handle long-term dependencies in data, making them well-suited for forecasting tasks.

### 2. Gated Recurrent Unit (GRU)

GRUs are a variant of LSTMs known for their computational efficiency. They are adept at handling sequence data and long-term dependencies with a simpler architecture compared to LSTMs.

### 3. SARIMAX

SARIMAX is a statistical forecasting model that builds upon the popular ARIMA model. It is a powerful tool for forecasting stationary time series data, capturing both seasonal effects and exogenous factors.

### 4. Prophet

Developed by Facebook, Prophet is a forecasting model specifically designed for time series data. It excels at capturing trends, seasonality, and the impact of holidays on the data.

## Evaluation Metrics

- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)
- R-squared (R2) score

## How to Use

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/khan-asim-88/Comparative-Analysis-of-Time-Series-Forecasting-Models-for-Cryptocurrency-Price-Prediction.git
   ```

2. **Navigate to the Repository Directory**:
   ```bash
   cd Comparative-Analysis-of-Time-Series-Forecasting-Models-for-Cryptocurrency-Price-Prediction
   ```

3. **Open the Jupyter Notebook**:
   ```bash
   jupyter notebook Code.ipynb
   ```

4. **Run the Notebook Cells**: Follow the steps in the notebook to fetch data, preprocess, train models, evaluate, and make forecasts.

## Results

The notebook contains detailed analysis, plots, and comparisons of the forecasting models. The results demonstrate the effectiveness of each model in predicting Bitcoin prices.
