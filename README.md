Trader Sentiment Analysis
Overview

This project analyzes how market sentiment (Fear vs Greed) affects trader behavior and performance using Hyperliquid historical trading data and Bitcoin Fear & Greed index data.
The goal is to understand whether trader decisions and outcomes change based on market sentiment and to derive simple strategy ideas from the analysis.

Dataset

Two datasets were used:

Historical Trader Data

Account

Trade size (USD)

Side (BUY / SELL)

Closed PnL

Timestamp

Bitcoin Fear & Greed Index

Date

Market classification (Fear / Greed)

The datasets were merged using daily dates.

Methodology

Loaded and inspected datasets.

Checked missing values and duplicates.

Converted timestamps into daily dates.

Merged trading data with sentiment data.

Created key metrics:

daily pnl per trader

win rate

average trade size

trades per day

long/short ratio

Since leverage was not available, trade size (USD) was used as a proxy for risk exposure.

Created trader segments:

high vs low position size

frequent vs infrequent traders

Compared trader behavior across fear and greed market conditions using charts and tables.

Key Insights

Traders show higher average pnl and win rate during greed market conditions.

Trading activity increases during fear periods, indicating stronger reactions in uncertain markets.

Traders take larger position sizes during greed phases, suggesting higher confidence.

Strategy Recommendations

During fear periods, reduce position size and avoid excessive trading to manage risk.

During greed periods, traders may increase exposure slightly while maintaining risk control.
