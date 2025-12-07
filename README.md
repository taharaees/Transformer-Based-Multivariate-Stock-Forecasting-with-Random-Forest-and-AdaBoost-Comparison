# Transformer-Based Multivariate Stock Forecasting  
Transformer vs Random Forest vs AdaBoost

## Project Overview
This project implements a simple version of the Transformer architecture for multivariate stock forecasting. The goal is to predict one-step-ahead log percent change of a target stock using a multivariate sequence of related stocks.

The project also trains:
- **Random Forest Regressor**
- **AdaBoost Regressor**

A comparison of forecasting performance is provided through MSE, MAE, and cumulative predicted return visualizations.

---

## Features
- Yahoo Finance data collection
- Log percent change preprocessing
- Transformer architecture (PyTorch)
- Ensemble baselines (scikit-learn)
- Train/validation/test split without leakage
- Simple backtest visualization

