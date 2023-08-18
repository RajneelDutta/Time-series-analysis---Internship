# Time-series-analysis---Internship

This repository contains the work done during my internship on time series analysis.

## Project Description

This project involves the analysis of marketing data from USA-based clients of Prodevan Technologies. The goal of the analysis was to extract meaningful insights and patterns from the data to inform marketing strategies and decision-making. The main file in this repository is `Prodev.ipynb`, which contains the code and analysis.

### Data
The data used in this project was provided by various companies and had been pre-processed to remove any personally identifiable information (PII). The dataset includes both monthly and quarterly sales data.

### Data Preprocessing
Extensive data preprocessing was performed to clean and prepare the data for analysis. This included handling missing values, outliers, and any other data quality issues.

### Trend and Seasonality Analysis
The data was analyzed to identify any underlying trends and seasonality patterns. This helped in understanding the cyclic nature of the sales data and identifying any recurring patterns.

### Time Series Forecasting
Time series forecasting was performed using several methods:

ACF and PACF plots: Autocorrelation Function (ACF) and Partial Autocorrelation Function (PACF) plots were used to identify the order of the ARIMA model for forecasting.
ARIMA: The Autoregressive Integrated Moving Average (ARIMA) model was used to forecast future sales data based on historical data.
Moving Average Model: Moving average models were used to smooth out the data and make predictions based on the average of previous data points.
Prophet: The Prophet model, developed by Facebook, was used for forecasting. This model is particularly well-suited for data with strong seasonal patterns and multiple seasonality.

### Results
The results of the analysis were presented in a separate presentation, which is not included in this repository. The insights and patterns discovered from the analysis were used to inform marketing strategies and decision-making for Prodevan Technologies and its clients.

## Getting Started

To get started with this project, clone the repository to your local machine and open the `Prodev.ipynb` file in a Jupyter Notebook.

### Prerequisites

- Python
- Jupyter Notebook
- Pandas
- Numpy
- Matplotlib

## Usage

1. Clone the repository to your local machine.
2. Open the `Prodev.ipynb` file in a Jupyter Notebook.
3. Run the cells in the notebook to see the analysis and results.

## Author

Rajneel Dutta

