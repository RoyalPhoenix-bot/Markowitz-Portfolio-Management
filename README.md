# Markowitz Portfolio Management 
Learnt about the **Markowitz theory** to diversify portfolio to earn a particular interest with the smallest amount of risk and implemented the theory in *python* by analysing the Nifty 50 stocks over 4 years.

## [Assignment 1](./Assignment%201)
+ Analyzed the Nifty 50 stocks from 01/01/2016 to 31/11/2020 with `Numpy` and `Pandas`.
+ Calculated the *Volatility* , *Compound Annual Growth Rate*(CAGR) and *Sharpe Ratio* for the stock price series.
+ Indentified the top 15 stocks with highest Sharpe Ratio.

## [Assignment 2](./Assignment%202)
+ Initialized random weights to the 15 stocks (600000 different sets of weights to have a large representative sample) and calculated the expected return, volatility and sharpe ratio corresponding to each of the weights.
+ Identified the maximum sharpe ratio of the weight and plotted the portfolios on a Scatter Plot using `MatPlotLib`.
+ Plotted the Efficient Frontier using SLSQP method.
+ Distributed a total amount of 1,00,00,000 to get the amount of money for each stock and the number of stocks in our portfolio.

## [Assignment 3](./Assignment%203)
+ Tested the Portfolio generated from the observation period(2016-2020). Testing period : 1 Jan'21 - 30 Jun'21.
+ Scraped the data of stocks from Yahoo using the `yfinance` library.
+ Compared the portfolio with the benchmark(Nifty 50) over several metrics:
    1. Total Return on Portfolio
    2. Volatility and Sharpe Ratio
    3. Beta
    4. Jenson's Alpha
    5. Sortino/Teynor Ratio


**Datafile:** [nifty50.csv](nifty50.csv)
