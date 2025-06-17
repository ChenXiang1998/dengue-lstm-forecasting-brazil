# Dengue Forecasting and Outbreak Detection in Brazil Using LSTM

This repository contains the code, data processing scripts, and model implementation for the study:

**"Dengue forecasting and outbreak detection in Brazil using LSTM: integrating human mobility and climate factors"**

## 📘 Overview

This project develops a deep learning framework to forecast dengue incidence and detect outbreaks across selected Brazilian cities. The approach combines:

- Historical dengue case data
- Climate variables (temperature, humidity)
- Intercity human mobility data
- LSTM-based time series modeling
- Adaptive Conformal Prediction (AgACI) for uncertainty estimation

## 🧠 Key Features

- Multi-horizon forecasting (1–4 weeks ahead)
- Outbreak detection using threshold-based strategies
- Integration of mobility-adjusted dengue importation risk
- Quantified prediction uncertainty with AgACI
- Evaluation metrics include RMSE, MAE, CRPS, and outbreak classification scores

## 🛠️ Requirements

- Python 3.8+
- TensorFlow 2.11
- NumPy, Pandas, Matplotlib, Scikit-learn

Install dependencies:
```bash
pip install -r requirements.txt
