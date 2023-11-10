# CryptoStrats
This project documents a trading strategy and backtesting results using R Markdown.
See the HTML file for project description/results

This Document describes and tests a backtesting strategy which employs the comparison of Moving Average Convergence/Divergence (MACD) of a single asset. MACD calculates the difference between fast and slow exponential moving averages (EMA). For this iteration MACD1 fast EMA is 5 and slow EMA is 50 with a signal of 17 and MACD2 fast EMA is 5 and slow EMA is 50 days with a signal of 30. This strategy is run from 2017-01-01 through 2023-11-10 and the first transaction is a buy. The strategy uses the following buy/sell triggers:

Buy when MACD1 crosses MACD1 Signal and the last transaction was not a buy.

Sell when MACD2 falls below MACD2 Signal and the last transaction was a buy.

This strategy has an ending cumulative return of 106.0349311 and a total of 221 transactions. See figures and tables below for analysis of

