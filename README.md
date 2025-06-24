# 📈 LSTM Time Series Forecasting with Optuna (Regression)

This project demonstrates how to build an **Automated LSTM model** for time series regression using **Keras** and **Optuna** for hyperparameter tuning.

## 🚀 Features
- Dynamic input reshaping based on time steps
- Custom LSTM model builder with flexible architecture
- Optuna integration for tuning:
  - Lookback window
  - Number of LSTM layers and units
  - Dropout rate
  - Batch size
  - Learning rate
- Automated training loop and evaluation

## 🧠 Technologies Used
- Python  
- TensorFlow / Keras  
- Optuna  
- Numpy / Pandas  
- Scikit-learn  

## 📊 Objective
To predict future values in a time series by building a flexible, tunable LSTM model. The model dynamically adjusts to different time steps and uses Optuna to find the optimal hyperparameters for performance.

## 🧪 Workflow
1. Load and preprocess time series data
2. Automatically reshape data based on lookback
3. Build LSTM model using dynamic architecture
4. Use Optuna for hyperparameter tuning
5. Train and evaluate the model

## ▶️ How to Use
Clone the repo and run the Jupyter notebook:

```bash
git clone https://github.com/Muzammil550/lstm-optuna-timeseries.git
cd lstm-optuna-timeseries
