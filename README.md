# Bitcoin Market Sentiment vs Trader Performance Analysis

## Overview

This project analyzes the relationship between Bitcoin market sentiment and trader performance using:

* Bitcoin Fear & Greed Index Dataset
* Hyperliquid Historical Trader Dataset (211,224 trades)

The objective is to identify how different market sentiment conditions influence trading profitability, win rates, trade sizes, and trading behavior.

---

## Datasets

### 1. Fear & Greed Index Dataset

Columns:

* Date
* Sentiment Classification (Extreme Fear, Fear, Neutral, Greed, Extreme Greed)

### 2. Hyperliquid Historical Trading Dataset

Key Columns:

* Account
* Coin
* Side
* Size USD
* Execution Price
* Closed PnL
* Timestamp

---

## Methodology

1. Data cleaning and preprocessing
2. Date alignment between datasets
3. Dataset merging using trade date
4. Exploratory Data Analysis (EDA)
5. Sentiment-based performance analysis
6. Visualization and insight generation

---

## Key Findings

* Extreme Greed generated the highest average profit per trade (67.89).
* Fear periods generated the highest total profit (3.36M).
* Extreme Greed achieved the highest win rate (46.49%).
* Fear periods had the largest average trade sizes (~7816 USD).
* Extreme Fear produced the lowest win rate (37.06%).
* SELL trades significantly outperformed BUY trades during Greed and Extreme Greed conditions.
* Extreme Greed delivered the strongest profitability despite having the smallest average trade size.

---

## Repository Structure

├── Primetrade_AI_Assignment.ipynb

├── report.pdf

└── README.md

---

## Conclusion

Market sentiment has a measurable impact on trader performance. The analysis suggests that trader profitability, win rates, and trade behavior vary significantly across sentiment regimes, providing useful signals for risk management and strategy development.
