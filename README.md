# Stock-Price-Prediction-LSTM-Deep-Learning
A high-precision Stock Price Prediction model for Alphabet Inc. (GOOGL) built using LSTM Neural Networks and Python.
# 📈 Stock Price Prediction using LSTM (Deep Learning)

![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![TensorFlow](https://img.shields.io/badge/TensorFlow-%23FF6F00.svg?style=for-the-badge&logo=TensorFlow&logoColor=white)
![Keras](https://img.shields.io/badge/Keras-%23D00000.svg?style=for-the-badge&logo=Keras&logoColor=white)

## 🎯 Overview
This project focuses on predicting the future stock prices of **Alphabet Inc. (GOOGL)** using historical market data. By leveraging **Long Short-Term Memory (LSTM)** networks, the model identifies long-term dependencies and patterns in time-series data to forecast market trends.

## 🚀 Key Features
- **Real-time Data:** Fetches live historical data using `yfinance`.
- **Advanced Preprocessing:** Implementation of `MinMaxScaler` and sliding window techniques (60-day lookback).
- **Deep Learning Model:** A stacked LSTM architecture with Dropout layers to prevent overfitting.
- **Interactive Visualizations:** Professional-grade charts using `Matplotlib` and `Plotly`.

## 📊 Performance Metrics
The model was evaluated on unseen test data, achieving high accuracy:
- **Root Mean Squared Error (RMSE):** 4.01
- **Loss Function:** Mean Squared Error (MSE)

## 🛠️ Tech Stack
- **Languages:** Python
- **Libraries:** TensorFlow, Keras, Pandas, NumPy, Scikit-Learn
- **Visualization:** Matplotlib, Plotly, Seaborn

## 📈 Visual Results
### Actual vs Predicted Trend
*(Insert your Final Graph Screenshot here)*

### Detailed Prediction Analysis
*(Insert your Zoomed-In Graph Screenshot here)*

## 📂 Project Structure
- `data_fetching.py` - Script to fetch data from yfinance.
- `preprocessing.py` - Scaling and windowing logic.
- `model_training.ipynb` - The main notebook containing the LSTM architecture.
- `visualizations.py` - Code for Plotly and Matplotlib charts.

## ✍️ Author
**HASHIR QURESHI** *Computer Science Student | AI Enthusiast* [LinkedIn](Aapka-LinkedIn-Link-Yahan) | [Branding: Code with Hashir]
