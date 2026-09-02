# Simple Trading Strategies

A collection of simple, classic trading strategies implemented and backtested in Python (pandas, numpy, matplotlib), built to apply my programming skills to finance before starting my Bachelor's in Statistics, Finance & Actuarial Science.

## Approach
Historical price data is pulled via yfinance. Each strategy is backtested on this data and evaluated against a buy-and-hold benchmark, looking at metrics like cumulative return, Sharpe ratio, and max drawdown.

## Strategies
- [x] Moving Average Crossover — in progress
- [ ] Mean Reversion
- [ ] Bollinger Bands Breakout
- [ ] Momentum
- [ ] Grid Trading

## How to run
```bash
pip install -r requirements.txt
python moving_average_crossover.py
```

## Tech stack
Python, pandas, numpy, matplotlib, yfinance
