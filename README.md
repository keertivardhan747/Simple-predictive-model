# Trader Behavior Analytics & Sentiment Dashboard

## Overview
This project analyzes trader behavior using historical trade data and market sentiment indicators. 
It combines behavioral feature engineering, machine learning, clustering, and interactive visualization 
to identify trader segments and evaluate performance patterns.

## Methodology
1. Merged trade data with sentiment index.
2. Engineered behavioral features:
   - Win rate
   - Trade frequency
   - Position sizing
3. Built a Random Forest classifier to predict next-day profitability.
4. Applied KMeans clustering to segment traders based on behavior.
5. Created an interactive dashboard using Plotly.

## Key Insights
- Traders with moderate position sizing showed higher win consistency.
- Extreme position sizes correlated with higher variance in win rates.
- Market sentiment positively influenced trader performance in specific clusters.

## Strategy Recommendations
- Encourage position size normalization.
- Apply sentiment-based risk scaling.
- Segment traders for tailored risk management.

## How to Run

Install dependencies:

pip install -r requirements.txt

Run notebook:

Open Trader_Behavior_Dashboard.ipynb in Jupyter/Colab and run all cells.
