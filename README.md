# 📈 XAUUSD Trading Strategy (RSI + EMA on Heikin Ashi)

This project showcases an algorithmic trading strategy developed using Python for XAUUSD (Gold/USD) on the MT5 platform. It was built and deployed as part of our Undergraduate Project.

## 📌 Strategy Overview

- **Instrument**: XAUUSD
- **Indicators Used**:
  - **RSI**: To detect overbought/oversold conditions
  - **EMA of Heikin Ashi candles**: For trend confirmation
- **Risk Management**:
  - Fixed stop-loss in dollars
  - No fixed take-profit; trail-based or timed exits
- **Trade Direction**:
  - Buy conditions depend on candle momentum + RSI crossover logic

## 🚀 Deployment

- Implemented using MetaTrader5 API in Python
- Backtested and forward-tested on live data during April–May 2025
- Strategy performed well in trending markets, struggled in sideways phases

## 🧠 Key Learnings

- Challenges in adapting strategies to market regimes
- Importance of risk management even with indicator-based systems
- Automation of trade execution using MT5 + Python

## 📂 Files

- `UG.ipynb`: Full strategy code + backtest
- `requirements.txt`: (add libraries like `pandas`, `numpy`, `MetaTrader5`, etc.)
- `strategy_summary.png`: Optional — equity curve or PnL chart

## 📄 Authors
Developed by Manish Choudhary as part of undergraduate final year project.
