# 📈 Egyptian Stock Price Prediction using ARIMA & LSTM

This notebook demonstrates time-series forecasting of Egyptian stock prices using both statistical and deep learning models. The project explores ARIMA for traditional modeling and LSTM (Long Short-Term Memory) for capturing temporal dependencies in stock market trends.

---

## Project Features

- Load and analyze real Egyptian stock price data
- Apply statistical modeling (ARIMA)
- Apply deep learning (LSTM) using Keras/TensorFlow
- Preprocess time-series data with normalization and reshaping
- Evaluate models using error metrics
- Visualize predictions against actual prices

---

## Models Used

### 🔹 ARIMA (AutoRegressive Integrated Moving Average)
- Suitable for univariate time-series forecasting
- Captures trend and seasonality using lag-based regression

### 🔹 LSTM (Long Short-Term Memory)
- Type of RNN ideal for sequences
- Learns long-term dependencies from stock price patterns
- Trained using past windowed sequences

---

## Workflow Overview

1. **Data Loading**
   - Load stock data from a CSV file or from Google Drive

2. **Preprocessing**
   - Normalize values (MinMaxScaler)
   - Reshape for LSTM compatibility (3D)

3. **Model Training**
   - Train ARIMA model on selected time series
   - Build and train LSTM using Keras with stacked layers

4. **Evaluation**
   - Compare predicted vs. actual values
   - Use Mean Squared Error (MSE), RMSE, and visual plots
