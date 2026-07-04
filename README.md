# Bitcoin Trader Analysis Using Market Sentiment

## Project Overview

This project analyzes the relationship between Bitcoin market sentiment and trader performance by combining historical trading data with the Bitcoin Fear & Greed Index. The objective is to understand how different market sentiment conditions influence trading activity, profitability, and trader behavior through data analysis and visualization.

---

## Objective

- Analyze historical Bitcoin trader performance.
- Merge trading data with the Fear & Greed Index.
- Perform data cleaning and preprocessing.
- Conduct Exploratory Data Analysis (EDA).
- Identify patterns in trading activity and profitability.
- Generate insights to support better trading decisions.

---

## Dataset

The project uses two datasets:

1. **Historical Trader Data**
   - Contains trade details such as coin, side, execution price, leverage, trade size, fees, and Closed PnL.

2. **Bitcoin Fear & Greed Index**
   - Contains daily market sentiment classified as:
     - Extreme Fear
     - Fear
     - Neutral
     - Greed
     - Extreme Greed

The datasets are merged using the trading date to analyze trader performance under different market conditions.

---

## Project Workflow

1. Data Loading
2. Data Cleaning
3. Data Type Conversion
4. Dataset Merging
5. Exploratory Data Analysis (EDA)
6. Data Visualization
7. Insight Generation
8. Report Preparation

---

## Exploratory Data Analysis

The analysis includes:

- Distribution of Market Sentiment
- Average Closed PnL by Market Sentiment
- Trading Volume by Market Sentiment
- Buy vs Sell Trades
- Top Traded Cryptocurrencies
- Closed PnL Distribution
- Hourly Trading Activity
- Profit vs Loss Distribution
- Correlation Heatmap
- Relationship between Market Sentiment and Trader Performance

---

## Key Findings

- Fear was the most common market sentiment and recorded the highest trading activity.
- Extreme Greed generated the highest average Closed PnL.
- Fear market conditions had the highest trading volume.
- Loss-making trades were more frequent than profitable trades.
- Trading activity was concentrated in a few cryptocurrencies such as HYPE, BTC, and ETH.
- Market sentiment influenced trader behavior and profitability, but effective risk management remained essential for consistent performance.

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## Project Structure

```
Bitcoin-Trader-Analysis/
│
├── data/
│   ├── historical_data.csv
│   └── fear_greed_index.csv
│
├── graphs/
│   ├── graph1.png
│   ├── graph2.png
│   └── ...
│
├── notebook.ipynb
├── report.pdf
├── README.md
├── requirements.txt
└── .gitignore
---

## Author

Archita Verma
