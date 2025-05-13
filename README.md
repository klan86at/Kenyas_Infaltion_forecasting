# Kenya Inflation Forecasting with ARIMA

Welcome to the **Kenya Inflation Forecasting** project! This repository contains a Jupyter Notebook that analyzes historical inflation data for Kenya (1960-2023) sourced from the World Bank and implements an ARIMA model to forecast future inflation rates up to 2028. The project leverages Python libraries for data processing, visualization, and time series analysis, offering insights into Kenya's economic trends.

## Features
- **Data Extraction**: Processes raw World Bank CPI data into a clean dataset.
- **Time Series Analysis**: Applies ARIMA modeling with automated parameter selection using `pmdarima`.
- **Visualization**: Generates plots to compare historical data with forecasted trends.
- **Extensibility**: Easily adaptable for other countries or economic indicators.

## Technologies Used
- **Python**: Core programming language.
- **Pandas & NumPy**: Data manipulation and numerical operations.
- **Matplotlib & Seaborn**: Data visualization.
- **Statsmodels**: ARIMA modeling and statistical tests.
- **pmdarima**: Automated ARIMA parameter tuning.
- **Jupyter Notebook**: Interactive development and documentation.

## Getting Started

### Prerequisites
- Python 3.12 or later
- Install required libraries via pip:
  ```bash
  pip install pandas numpy matplotlib seaborn statsmodels pmdarima jupyter
