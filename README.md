# 📈 Bitcoin Volatility & Price Forecasting

This project analyzes the **volatility** and **returns** of Bitcoin using time series models. The goal is to explore historical data and implement predictive methods to understand market behavior and forecast future trends.

## 🧠 Project Objectives

- Analyze daily BTC price data over the past 4 years
- Evaluate returns and volatility patterns
- Implement and compare:
  - **ARIMA** models for trend forecasting
  - **GARCH** models for volatility prediction
  - **Monte Carlo simulations** for scenario modeling
  - **Conditional Value at Risk (CVaR)** estimation

## 🗂️ Dataset

- Source: Yahoo Finance (`BTC-USD`)
- Frequency: Daily
- Period: 4 years (2021–2025)

## 📊 Methods Used

- Time series decomposition
- Stationarity tests (ADF)
- ARIMA modeling
- GARCH volatility modeling
- Log-returns and CVaR computation
- Monte Carlo simulations
- Visualizations using `matplotlib` and `seaborn`

## 📌 Key Insights

- Bitcoin returns show high volatility with clustering effects
- ARIMA performed well in short-term trend forecasting
- GARCH captured volatility bursts and fat tails
- Monte Carlo allowed for probabilistic scenario generation
- CVaR gave more robust risk assessment than standard VaR

## 🛠️ Requirements

Install libraries using:

```bash
pip install -r requirements.txt
