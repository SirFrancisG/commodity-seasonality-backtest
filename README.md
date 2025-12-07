# Commodity-seasonality-backtest
Python framework for seasonal commodity futures backtesting using yfinance and walk-forward validation


This repository contains a Python-based framework developed to investigate
seasonal patterns in commodity futures and evaluate their robustness through
statistical testing and walk-forward backtesting.

The project was originally created in the context of the CME Group University
Trading Challenge as part of a broader research effort on systematic
commodity trading strategies.

## Overview

The framework performs the following tasks:

- Data extraction using `yfinance`
- Preprocessing and cleaning of futures historical data
- Computation of seasonal tendencies and statistical significance tests
- Construction of signals based on multi-year seasonal patterns
- Implementation of walk-forward backtests to avoid look-ahead bias
- Basic risk management components (position sizing, stop logic)
- Visualization of results

The goal is to provide a clean, reproducible structure for analyzing whether
seasonality in commodity futures exhibits persistent and tradable behaviour.

## Disclaimer

This repository is intended **solely for educational and research purposes**.

Nothing contained herein constitutes investment advice, trading recommendations,
or an offer to buy or sell any financial instrument.  
The strategies, parameters, and methodologies illustrated are simplified
examples and **do not represent actual trading systems** used in any professional
capacity.

Past performance — whether real, simulated, or hypothetical — is **not**
indicative of future results.  
The author assumes no responsibility for any losses, decisions, or actions taken
by third parties who use, modify, or interpret this code.

By using this repository, you acknowledge that you do so at your own risk.
