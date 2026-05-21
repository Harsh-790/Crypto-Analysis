# Trader Behavior Analysis using Fear & Greed Index

## Project Overview
This project analyzes cryptocurrency trader behavior using historical trading data combined with the Fear & Greed Index. The goal was to understand how market sentiment affects trading activity, profitability, trade size, and trader behavior patterns.


# Objectives
Clean and preprocess trading and sentiment datasets.
Align both datasets using date information.
Analyze trader performance during Fear and Greed periods.
Identify behavioral patterns among traders.
Generate actionable trading insights.
Build a simple predictive model for profitability prediction.

# Dataset Information

## 1. Historical Trading Data
Contains:
 Account details
 Coin traded
 Trade execution price
 Trade size
 Profit and loss information
 Trade timestamps

## 2. Fear & Greed Index Data
Contains:
- Market sentiment classification
- Sentiment value
- Date information

---

# Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

---

# Data Preparation Steps
1. Loaded both datasets
2. Checked missing values and duplicates
3. Converted timestamp columns into datetime format
4. Extracted date from timestamps
5. Merged datasets using the date column
6. Created additional analysis features

---

# Analysis Performed

## Sentiment-Based Analysis
- Average PnL by sentiment
- Win rate analysis
- Trade size comparison
- Long vs Short behavior analysis

## Trader Segmentation
- Frequent vs Infrequent traders
- Top profitable traders
- Trading activity comparison

## Predictive Modeling
A lightweight Random Forest model was trained to predict profitable trades using:
- Trade size
- Sentiment value

---

# Key Insights
1. Extreme Greed periods showed higher trading activity and larger trade sizes.

2. Frequent traders generated more trades but did not always achieve higher profitability.

3. Market sentiment significantly influenced trading behavior and overall trading activity.

4. Traders showed more aggressive market participation during Greed conditions.

---

# Strategy Recommendations
1. Avoid emotional overtrading during Extreme Greed periods.

2. Maintain disciplined position sizing during volatile market sentiment conditions.

3. Use sentiment indicators alongside risk management strategies.

---

# Model Performance
The predictive model achieved approximately 66% accuracy in identifying profitable trades.

---

# How to Run the Project

## Install Dependencies
```bash
pip install pandas numpy matplotlib seaborn scikit-learn