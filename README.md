# Meridian Tech Fund: Portfolio Risk Analysis 

A quantitative financial data analysis project evaluating the risk and performance metrics of a 20-stock technology portfolio. This project was built entirely using Python and NumPy, with a strict focus on highly efficient, fully vectorized array operations rather than standard iterative programming.

## 🏢 The Scenario
This project simulates a real-world task for a Junior Portfolio Analyst at a boutique investment firm. The objective is to analyze the daily returns of the **Meridian Tech Fund** (comprising 20 distinct tech equities over 252 trading days) and prepare a comprehensive risk report for the firm's Investment Committee.

## 🛠️ Technical Highlights
To maximize computational efficiency, this analysis avoids standard Python `for` loops and relies exclusively on **NumPy**. Key techniques demonstrated include:
* **Vectorization & Broadcasting:** Applying mathematical operations across multi-dimensional arrays (252 days × 20 stocks) simultaneously.
* **Boolean Masking:** Filtering complex datasets for conditional risk metrics without programmatic iteration.
* **Dimensional Manipulation:** Utilizing the `axis` parameter for precise row-wise (temporal) and column-wise (asset) aggregations.

## 📊 Key Metrics Calculated
The analysis evaluates both individual assets and the aggregate portfolio across several dimensions:
* **Performance:** Annualized Returns, Average Daily Returns, Cumulative Growth.
* **Volatility:** Annualized Volatility (Standard Deviation).
* **Risk-Adjusted Return:** Sharpe Ratio, Sortino Ratio.
* **Downside Risk:** 95% Value at Risk (VaR), Conditional VaR (Expected Shortfall), Downside Deviation, and Maximum Drawdown.

## 🔍 Project Structure & Insights
The Jupyter Notebook is divided into five core analytical stages:

1.  **Individual Stock Analysis:** Profiling the standalone risk/return characteristics of all 20 assets.
2.  **Portfolio Return Analysis:** Calculating the weighted aggregate returns of the fund and mapping its compounding growth over a 1-year period.
3.  **Downside Risk Assessment:** Isolating negative volatility and extreme loss events (VaR, Max Drawdown) to stress-test the portfolio.
4.  **Weight Optimization (Scenario Testing):** Constructing an "Equal-Weight" hypothetical portfolio and cross-analyzing its performance against the fund's active allocation strategy.
5.  **Executive Summary:** A final synthesis of top-performing assets, overarching risk, and actionable recommendations for rebalancing.

## 🚀 Getting Started
To view the code and analysis:
1. Open the file in this repository.
2. The notebook includes all expected outputs, print statements, and executive summaries, so it can be read directly on GitHub without needing to execute the code locally.

### Prerequisites
If you wish to run the notebook locally, you will need:
* Python 3.x
* Jupyter Notebook or Google Colab
* NumPy (`pip install numpy`)
