# Time Series Forecasting - ARIMA, SARIMA, and Auto-ARIMA

## Project Overview

This project explores time series forecasting techniques using ARIMA, SARIMA, and Auto-ARIMA models. The goal is to predict stock prices and evaluate the performance of different forecasting methods. The dataset used for this project is the TSLA (Tesla, Inc.) stock price data.

## Dataset

The dataset used in this project is the TSLA stock price data, which includes various features such as the closing price of Tesla's stock. The data is sourced from [Yahoo Finance, Kaggle].

## Forecasting Models

1. **ARIMA (AutoRegressive Integrated Moving Average)**
   - ARIMA models are used to capture the underlying patterns in the time series data for forecasting future values.
   - We use the `ARIMA` class from the `statsmodels` library to implement this model.

2. **SARIMA (Seasonal AutoRegressive Integrated Moving Average)**
   - SARIMA extends ARIMA by adding seasonal components to handle seasonality in the data.
   - We use the `SARIMAX` class from the `statsmodels` library to implement SARIMA.

3. **Auto-ARIMA**
   - Auto-ARIMA automatically selects the best ARIMA model by searching through different hyperparameters.
   - We use the `auto_arima` function from the `pmdarima` library for this purpose.

## Project Structure

- `data/`: Directory containing the dataset file (`TSLA.csv`).
- `ipynb/`: Main code of this project, it contains requirements, model training, dataset preprocessing
- `README.md`: Project overview and instructions.

## Requirements

To run the code in this project, you'll need to install the following Python packages. You can install them using `pip`:

pip install pandas numpy matplotlib statsmodels pmdarima

## Acknowledgements

- **Dataset**: The TSLA stock price data used in this project is sourced from Kaggle, which provides comprehensive historical financial data. For access to the dataset, visit https://www.kaggle.com/datasets/varpit94/tesla-stock-data-updated-till-28jun2021.

- **Libraries and Tools**:
  - **pandas**: Used for data manipulation and analysis.
  - **numpy**: Used for numerical operations and mathematical computations.
  - **matplotlib**: Used for plotting and visualizing data.
  - **statsmodels**: Provides the ARIMA and SARIMA models used for time series forecasting.
  - **pmdarima**: Utilized for the Auto-ARIMA model, which automatically selects the best ARIMA parameters.

- **Community Support**:
  - Thanks to the broader data science and machine learning community for sharing knowledge and resources that facilitated this project.
