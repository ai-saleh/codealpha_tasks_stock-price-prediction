# Microsoft Stock Price Prediction using LSTM

## Project Overview
This project attempts to predict Microsoft's stock prices using Long Short-Term Memory (LSTM) neural networks. It demonstrates the process of data collection, preprocessing, model building, and evaluation in the context of financial time series forecasting.

## Key Features
- Data collection using yfinance API
- Time series to supervised learning conversion
- LSTM model implementation with TensorFlow/Keras
- Model retraining with recent data
- Recursive prediction for future forecasting
- Comprehensive visualization of results

## Installation
```
pip install yfinance pandas numpy matplotlib tensorflow
```

## Usage
1. Run the Jupyter notebook or Python script to execute the entire pipeline.
2. The script will download Microsoft stock data, preprocess it, train the LSTM model, and generate predictions.
3. Visualizations will be displayed showing the model's performance on training, validation, and test sets, as well as recursive predictions.

## Key Findings
- LSTM models struggle with long-term stock price prediction.
- Using recent data (last year) improved model performance slightly.
- The model showed limitations in capturing market trends and volatility.
- Recursive predictions quickly converged to a constant value, highlighting the challenge of long-term forecasting.

## Future Work
- Incorporate additional features (e.g., financial indicators, sentiment analysis)
- Explore alternative models and ensemble methods
- Focus on short-term predictions or price movement direction instead of exact prices