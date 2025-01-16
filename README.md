# JSS-Stock-Predictor-ML-Bot
This project aims to create a Moving Average Stock Prediction Web App using Machine Learning techniques. The site will utilize historical stock data to generate predictions based on moving average crossover strategies.

VaR (Value-at-Risk) Calculator
Calculate VaR using the Interactive Dashboard: https://var-calculator.streamlit.app

This module provides an easy-to-use Python class, VaR, for calculating Value-at-Risk (VaR) using three different methods: Historical, Parametric, and Monte Carlo simulation.

🚀 Features:
Historical VaR Calculation: This method uses the actual distribution of historical returns to estimate VaR.
Parametric VaR Calculation: Also known as the variance-covariance method. It assumes returns are normally distributed.
Monte Carlo Simulation: Generates a large number of random portfolio returns and then determines an empirical distribution.
📦 Dependencies:
yfinance: To fetch historical stock data.
numpy: For numerical operations.
matplotlib: For visualization.
📖 How to Use:
Initialize the VaR class with the following parameters:

ticker: List of tickers of assets in the portfolio.
start_date, end_date: Start and end dates for historical data fetch.
rolling_window: Rolling window size for historical VaR.
confidence_level: Confidence level for VaR calculation (e.g., 0.95 for 95%).
portfolio_val: Total portfolio value.
simulations: Number of simulations for Monte Carlo.
