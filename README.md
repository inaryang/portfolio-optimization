# portfolio-risk-analysis

This project analyzes a simple three-asset portfolio using historical price data from Yahoo Finance. The goal is to measure return, volatility, and risk-adjusted performance, and to test whether diversification reduces risk.

Assets analyzed:
- AAPL
- MSFT
- SPY

## Methods
- Downloaded historical adjusted closing prices using yfinance
- Computed daily simple returns
- Constructed a weighted portfolio
- Calculated annualized return and annualized volatility
- Computed the Sharpe ratio

## Results
The portfolio showed lower volatility than a single-stock allocation, illustrating the benefits of diversification. The Sharpe ratio was used to evaluate return relative to risk.

## How to Run
```bash
pip install -r requirements.txt
python data_analysis.py
