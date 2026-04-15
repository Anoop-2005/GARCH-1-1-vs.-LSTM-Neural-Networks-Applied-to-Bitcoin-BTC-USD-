# Bitcoin (BTC-USD) Volatility Forecasting

This project focuses on analyzing and forecasting the volatility of Bitcoin (BTC-USD) using both statistical and deep learning approaches. It compares traditional GARCH models with Long Short-Term Memory (LSTM) neural networks.

## Features
- **Data Acquisition**: Automatically downloads historical BTC-USD data using `yfinance`.
- **Exploratory Data Analysis (EDA)**: Visualizes closing prices, daily log returns, and 30-day realized volatility.
- **Modeling**:
  - **GARCH**: Statistical modeling for time-series volatility.
  - **LSTM**: Deep learning approach for capturing complex patterns in volatility.
- **Evaluation**: Compares model performance using metrics like Mean Squared Error (MSE) and Mean Absolute Error (MAE).

## Project Structure
- `Code.ipynb`: The main Jupyter Notebook containing the data pipeline, EDA, and model implementations.
- `btc_volatility_data.csv`: Historical dataset including prices, returns, and volatility targets.

## Installation
To run this project, you will need to install the following Python libraries:

```bash
pip install yfinance arch tensorflow scikit-learn scipy matplotlib seaborn
