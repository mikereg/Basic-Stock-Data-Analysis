# Basic-Stock-Data-Analysis

This repository contains a Jupyter notebook demonstrating fundamental concepts of stock data analysis, implemented from first principles using Python, **NumPy**, and **pandas**. The goal is to showcase how essential financial metrics and techniques can be applied in a clear, reproducible way, without relying on advanced financial libraries.

## Purpose

The notebook is designed for beginners and intermediate users who want to understand the core components of stock data analysis. It emphasizes:
- **Raw data handling**: Fetching and cleaning financial data.
- **Calculating key performance metrics**: Returns, volatility, and risk-adjusted performance.
- **Using technical indicators**: Applying moving averages and rolling calculations.
- **Exploring visualizations**: Creating insightful plots for data-driven decisions.

## Key Features

The notebook covers a variety of fundamental financial concepts and techniques, implemented in a straightforward manner:
1. **Data Collection**: Fetching stock price data from Yahoo Finance.
2. **Preprocessing**: Cleaning and structuring data for analysis, including handling missing values.
3. **Performance Metrics**:
   - **Daily and Logarithmic Returns**: Calculate both simple and logarithmic daily returns.
   - **Rolling Metrics**: Implement rolling calculations to capture time-varying metrics like volatility and Sharpe ratio.
   - **Sharpe Ratios**: Measure risk-adjusted returns, highlighting periods of higher risk.
4. **Technical Indicators**:
   - **Moving Averages**: Calculate simple and exponential moving averages to identify trends.
   - **Rolling Sharpe Ratio**: Showcase a rolling Sharpe ratio to evaluate risk-adjusted returns over time.
5. **Data Visualization**:
   - Plotting stock prices, returns, volatility, and other metrics to gain a visual understanding of trends and performance.

## Notebook Structure

- **Section 1: Data Collection** – Download historical stock data for selected tickers.
- **Section 2: Data Cleaning and Preprocessing** – Prepare data by handling missing values and adding new features.
- **Section 3: Fundamental Performance Metrics** – Calculate basic financial metrics like returns and volatility.
- **Section 4: Technical Indicators** – Implement simple moving averages and a rolling Sharpe ratio.
- **Section 5: Visual Analysis** – Create plots to explore stock price trends, returns distributions, and correlation.

## Getting Started

To run the notebook, you’ll need:
- **Python 3.8+**
- **Jupyter Notebook**
- Libraries: **NumPy**, **pandas**, **matplotlib**, **seaborn**, **yfinance**

### Installation

```bash
# Clone the repository
git clone https://github.com/yourusername/basic-stock-data-analysis.git

# Navigate into the directory
cd basic-stock-data-analysis

# Install dependencies
pip install numpy pandas matplotlib seaborn yfinance
