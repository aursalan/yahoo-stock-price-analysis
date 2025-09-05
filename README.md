# Yahoo Stock Price Analysis (1999-2023)

## Project Description

This project provides an analysis of Yahoo's historical stock prices from November 1999 to September 2023. The primary objective is to process raw time-series data to calculate the average closing price for each year and visualize the resulting trend.

The analysis is conducted using Python, with a strong emphasis on numerical computation using the **NumPy** library. It demonstrates an efficient, vectorized approach to data aggregation by using `np.bincount` to calculate the yearly averages, which is significantly faster than traditional looping methods. The final visualization is a line chart generated with **Matplotlib** that clearly illustrates the fluctuations in Yahoo's average stock price over more than two decades.

## Installation and Setup

To run this analysis, you will need Python 3 and a few standard data science libraries.

### Prerequisites
* Python 3.x
* NumPy
* Matplotlib
* Jupyter Notebook or JupyterLab

### Installation
1.  Install the required Python libraries using pip:
    ```bash
    pip install numpy matplotlib jupyterlab
    ```
2.  Download the project files, including the `yahoo-stock-price-analysis.ipynb` notebook.
3.  Obtain the dataset, `yahoo_stock_price.csv`. The notebook expects this file to be in a specific path (`/kaggle/input/yahoo-stock-price/yahoo_stock_price.csv`). If running locally, you must update this path in the second code cell to point to the location of your CSV file.

## Usage

1.  Launch the Jupyter environment:
    ```bash
    jupyter lab
    ```
2.  Open the `yahoo-stock-price-analysis.ipynb` notebook.
3.  Ensure the file path to `yahoo_stock_price.csv` is correct.
4.  Run the cells in the notebook from top to bottom.

The final cell will execute the analysis and render a line chart titled **"Average Stock Closing Price by Year"**, showing the trend from 1999 to 2023.

## License

This project is licensed under the MIT License.