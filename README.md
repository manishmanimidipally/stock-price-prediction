Stock Price Prediction Using Machine Learning

Project Overview

This project leverages machine learning techniques to predict stock prices using historical market data. It utilizes a Random Forest Regressor to forecast future stock prices for selected companies, incorporating data from Amazon (AMZN), Domino’s Pizza (DPZ), Bitcoin (BTC), and Netflix (NFLX). The project is built using Streamlit, allowing users to interactively visualize predictions.

Features

Historical Data Processing: Loads and processes stock price data from CSV.

Machine Learning Model: Implements a Random Forest Regressor for price prediction.

Interactive UI with Streamlit:

Users can select the stock to predict.

Adjustable forecast horizon (1 to 30 days).

Dynamic visualization with Plotly.

Synthetic Data Extension: Generated stock data from 2019 to 2025 for complete analysis.

Performance Evaluation: Calculates and displays the Mean Squared Error (MSE) of the model.

Dataset

The dataset contains stock price data from 2013 to 2025, where 2019-2025 data is synthetically generated using a random walk approach based on past trends.

Installation & Usage

Clone the Repository:

git clone https://github.com/manishmanimidipally/stock-price-prediction.git
cd stock-price-prediction

Install Dependencies:

pip install -r requirements.txt

Run the Streamlit App:

streamlit run app.py

Upload Your Own Dataset (Optional): Replace stock_data.csv with your own dataset.

Future Improvements

Incorporate Deep Learning: Use LSTM or Transformer models for better accuracy.

Enhance Feature Engineering: Include technical indicators (SMA, RSI, MACD).

Live Data Fetching: Integrate APIs (e.g., Yahoo Finance, Alpha Vantage).

Hyperparameter Tuning: Optimize the Random Forest model.

Contributing

Contributions are welcome! Feel free to fork this repository, submit issues, or make pull requests.

License

This project is licensed under the MIT License.

Author: MAMIDIPALLY MANISH
Contact:mamidipallymanish6@gmail.com

