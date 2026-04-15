# Bitcoin (BTC-USD) Volatility Forecasting

This project focuses on analyzing and forecasting the volatility of Bitcoin (BTC-USD) using both statistical and deep learning approaches. It compares traditional GARCH models with Long Short-Term Memory (LSTM) neural networks.

## Features
- [cite_start]**Data Acquisition**: Automatically downloads historical BTC-USD data using `yfinance`[cite: 20, 22].
- [cite_start]**Exploratory Data Analysis (EDA)**: Visualizes closing prices, daily log returns, and 30-day realized volatility[cite: 22, 23].
- **Modeling**:
  - [cite_start]**GARCH**: Statistical modeling for time-series volatility[cite: 20, 21].
  - [cite_start]**LSTM**: Deep learning approach for capturing complex patterns in volatility[cite: 20, 21].
- [cite_start]**Evaluation**: Compares model performance using metrics like Mean Squared Error (MSE) and Mean Absolute Error (MAE)[cite: 21].

## Project Structure
- [cite_start]`Code.ipynb`: The main Jupyter Notebook containing the data pipeline, EDA, and model implementations[cite: 20].
- [cite_start]`btc_volatility_data.csv`: Historical dataset including prices, returns, and volatility targets[cite: 20].

## Installation
To run this project, you will need to install the following Python libraries:

```bash
pip install yfinance arch tensorflow scikit-learn scipy matplotlib seaborn
