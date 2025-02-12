# Twitter Sentiment-Based Investment Strategy

## Overview

This project implements a sentiment-based investment strategy that leverages Twitter sentiment data to select and manage a portfolio of stocks. The strategy aims to identify promising stocks by analyzing social media activity and sentiment and compare its performance against the NASDAQ index.

## Key Features

- **Sentiment Analysis**: Twitter data is used to gauge public sentiment towards various stocks, which is then used to inform investment decisions.
- **Portfolio Management**: A dynamic portfolio is created by selecting stocks based on sentiment scores, and the portfolio is automatically rebalanced every month.
- **Engagement Metrics**: Sentiment metrics and engagement ratios are aggregated to rank stocks based on social media activity and potential.
- **Performance Evaluation**: The strategy's performance is compared to the NASDAQ index, with visualizations to demonstrate the strategy’s effectiveness.
  
## Technologies Used

- **Python**
- **yfinance** - For retrieving historical stock price data from Yahoo Finance.
- **pandas** - For data manipulation and analysis.
- **numpy** - For numerical computations.
- **matplotlib** - For visualizations of performance comparisons and results.
