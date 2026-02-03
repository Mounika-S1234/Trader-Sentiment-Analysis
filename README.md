# Trader Sentiment Analysis

## Objective
This project analyzes trader behavior under different market sentiment conditions
(Fear, Extreme Fear, Neutral, Greed, Extreme Greed) using historical trade data
and the Fear & Greed Index.

## Data Sources
- Trader transaction data (price, volume, PnL, timestamps)
- Crypto Fear & Greed Index (daily sentiment scores)

## Methodology
- Parsed and normalized timestamps
- Merged trader data with daily sentiment scores
- Engineered features such as win rate, total volume, and trader cohorts
- Compared Whale vs Retail behavior
- Identified contrarian traders
- Analyzed correlations between sentiment and performance

## Key Findings
- Retail traders perform better during Extreme Fear
- Whale traders increase volume during Extreme Greed
- 17 traders consistently profit in both Extreme Fear and Extreme Greed
- Market sentiment shows weak correlation with win rate and PnL overall

## Files
- `Trader_Sentiment_Analysis.ipynb` – Complete analysis notebook
