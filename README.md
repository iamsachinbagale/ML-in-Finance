# ML-in-Finance

# yfinance
yfinance is the most popular open source library to access the financial data available on Yahoo Finance.

Yahoo Finance used to have their own official API, but this was decommissioned 2017.

These days a range of unofficial APIs and libraries exist to access the same data, including of course yfinance.

Note you might know of yfinance under it’s old name- fix-yahoo-finance, since it was re-named on May 26th 2019. To ensure backwards compatibility, fix-yahoo-finance now imports and uses yfinance anyway.

Now, yfinance generally is considered great for prototyping, or doing basic research on historic data.

But if you are building a serious trading system requiring complete confidence and total reliability on the data fed to the system, I’d recommend going with a official and alternative market data provider- preferably one claiming to provide low latency data directly from exchanges.

Like Polygon or IEX

# Extract Stock market Data with yfinance (FY 2022)
    1.Extracted Google Stock Info. of FY 2022
    
    2.Fetching Data of Multiple Stocks and stored in a dataframe(APPLE, GOOGLE, UBER, WALMART)
        2.1Calculated the Daily Returns and plotted the cumulative returns of all the list of stocks.
        2.2Determined market volatility or the spread of asset prices from their average price(Standard Deviation)
        2.3Constructed a Correlation Table 
        2.4Calculated Annualized Sharpe Ratios
        
    3.Fetching Data for all Stock Tickers in S&P 500 Companies
    
    4.Get the key Financial Metrics of Multiple Tickers
    

# PREDICTIVE MODEL BUIDING BASED ON THE HISTORICAL TIME-SERIES DATA OF TESLA
    1.SARIMAX(Seasonal Auto-Regressive Integrated Moving Average with eXogenous factors)
    2.What is a stationary Time Series
    3.Dickey-Fuller test
    4.PREDICTION WITH SARIMAX MODEL
