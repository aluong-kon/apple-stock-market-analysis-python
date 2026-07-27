# apple-stock-market-analysis-python
# 📈 Apple Stock Market Analysis Using Python

## Project Overview

This project analyzes historical Apple Inc. (AAPL) stock market data using Python. The objective is to apply advanced data transformation techniques, perform time-series analysis, engineer meaningful features, and generate business insights from historical stock prices.

The analysis was completed as part of the AnalystLab Africa Data Analytics Program.

---

## Objectives

- Perform data cleaning and preprocessing
- Apply advanced Pandas data transformation techniques
- Conduct time-series analysis
- Engineer new financial features
- Create insightful visualizations
- Generate business insights and recommendations

---

## Dataset

**Source:** Yahoo Finance

Apple Inc. (AAPL) Historical Stock Data

Features include:

- Date
- Open Price
- High Price
- Low Price
- Close Price
- Adjusted Close Price
- Trading Volume

Data was downloaded using the `yfinance` Python package.

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- yfinance
- Jupyter Notebook

---

## Project Workflow

### 1. Data Collection

- Downloaded historical Apple stock data using yfinance.

### 2. Data Exploration

- Dataset overview
- Summary statistics
- Missing value analysis
- Duplicate detection

### 3. Data Cleaning

- Removed duplicate records
- Handled missing values
- Converted Date to datetime
- Indexed the dataset by date

### 4. Data Transformation

Applied several Pandas operations including:

- Filtering
- Sorting
- Aggregation
- Resampling
- Grouping
- Feature creation

### 5. Time-Series Analysis

Performed:

- Trend analysis
- Daily performance analysis
- Monthly performance analysis
- Rolling averages
- Percentage change analysis
- Volatility analysis

### 6. Feature Engineering

Created new features including:

- Daily Price Change
- Percentage Change
- Daily Return
- Monthly Return
- Price Range
- 7-Day Moving Average
- 30-Day Moving Average
- Rolling Volatility
- Volume Change
- Lagged Closing Price

---

## Exploratory Data Analysis

The project answers the following questions:

- How has Apple's stock price changed over time?
- How has trading volume evolved?
- What does the moving average reveal?
- Which months performed best?
- How volatile is Apple stock?
- Are there unusual price movements?
- Which variables are highly correlated?

---

## Visualizations

The notebook includes:

- Closing Price Trend
- Trading Volume Trend
- Moving Average Analysis
- Monthly Returns
- Daily Returns Distribution
- Rolling Volatility
- Correlation Heatmap
- Boxplot of Closing Prices
- Scatter Plot (Volume vs Closing Price)

---

## Key Insights

- Apple stock demonstrated strong long-term growth despite periodic market corrections.
- Trading volume spikes aligned with periods of heightened investor activity.
- Moving averages highlighted both short-term fluctuations and long-term trends.
- Monthly returns reflected normal market cycles with alternating gains and losses.
- Rolling volatility increased during periods of market uncertainty.
- Feature engineering improved the dataset for advanced analysis and future predictive modeling.

---

## Recommendations

- Focus on long-term investment trends rather than short-term price fluctuations.
- Use moving averages together with additional technical indicators for market analysis.
- Incorporate volatility measures into investment decisions to manage risk.
- Combine trading volume with price action and market news for more informed analysis.
- Leverage engineered features when developing machine learning models for stock price forecasting.

---

## Repository Structure

```
apple-stock-market-analysis-python
│
├── data/
│   └── aapl_stock.csv
│
├── notebooks/
│   └── Apple_Stock_Analysis.ipynb
│
├── images/
│   ├── closing_price.png
│   ├── trading_volume.png
│   ├── moving_average.png
│   ├── monthly_returns.png
│   ├── volatility.png
│   └── correlation_heatmap.png
│
├── report/
│   └── Insight_Report.pdf
│
├── requirements.txt
│
└── README.md
```

---

## Installation

```bash
pip install pandas numpy matplotlib seaborn yfinance
```

---

## Author

**Aluong Yak Kon**

Aspiring Data Analyst | Python | SQL | Power BI | Data Visualization


---

## Acknowledgements

- Yahoo Finance
- AnalystLab Africa
- Python Open Source Community
