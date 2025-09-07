# 📈 Yahoo Stock Price Analysis 

> A time series analysis of Yahoo's historical stock prices. Using a Jupyter Notebook, it performs exploratory data analysis (EDA) on a financial dataset to uncover trends and patterns.

- **Data Handling:** Loads and parses stock price data from a CSV file using Python's built-in csv module.
- **Data Processing:** Converts the raw data into a structured NumPy array for efficient numerical operations and data cleaning.
- **Data Visualisation:** Utilises Matplotlib to create plots that visualise stock price trends and the average closing price by year.

## Screenshots

![](/assets/screenshot.png)

## Table of Contents

1. [Tech Stack and Prerequisites](#1-tech-stack-and-prerequisites)
2. [How to Install and Run the Project](#2-how-to-install-and-run-the-project)
3. [How to Use the Project](#3-how-to-use-the-project)
4. [Future Improvements](#4-future-improvements)
5. [Acknowledgements](#5-acknowledgements)
6. [License](#6-license)
## 1. Tech Stack and Prerequisites

**Prerequisites:** Python, Jupyter Notebook, Kaggle

## 2. How to Install and Run the Project

1. Navigate to [Kaggle](https://www.kaggle.com/) Notebooks.
2. Upload the Jupyter Notebook file: `yahoo-stock-price-analysis.ipynb`.
3. Load the [Yahoo Stock Price](https://www.kaggle.com/datasets/aursalan/yahoo-stock-price) dataset into the Kaggle environment.
4. Run all cells in the notebook to reproduce the analysis and generate the plots.
## 3. How to Use the Project

Once the notebook is executed, you can:

- **View Stock Price Plots:** Analyse the generated line charts to see the daily fluctuations in Yahoo's stock price over the dataset's time span.

- **Observe Yearly Averages:** Examine the bar chart showing the average stock closing price for each year to identify long-term trends.
##  4. Future Improvements

- **Advanced Technical Analysis:** Implement more sophisticated financial indicators like Moving Averages, Bollinger Bands, and Relative Strength Index (RSI).
- **Predictive Modelling:** Develop a time series forecasting model (e.g., ARIMA or LSTM) to predict future stock prices.
- **Interactive Dashboard:** Create a dynamic and interactive dashboard using libraries like Plotly or Dash to allow for more flexible data exploration.
- **API Integration:** Replace the static CSV file with a live data feed from a financial API (e.g., Yahoo Finance API) to perform real-time analysis.
## 5. Acknowledgements

- [NumPy Documentation](https://numpy.org/doc/)
- [Matplotlib Documentation](https://matplotlib.org/stable/index.html)
## 6. License

This project is licensed under the [MIT](LICENSE) License.
