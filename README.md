# Call vs Put Implied Volatility Correlation Analyzer
## Project Overview
This project analyzes the correlation between call and put implied volatilities (IVs) at identical strikes and expiration dates. 

We pull live options chain data using Yahoo Finance, merge the data on strike price, and calculate the correlation across multiple expirations. 

Finally, we visualize the relationship both at single expirations and over multiple expirations.

## Technologies
- Python
- yfinance
- pandas
- matplotlib
- seaborn

## Installation
pip install yfinance pandas matplotlib seaborn
