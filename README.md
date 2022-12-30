# ML-in-Finance

# yfinance
yfinance is the most popular open source library to access the financial data available on Yahoo Finance.

Yahoo Finance used to have their own official API, but this was decommissioned 2017.

These days a range of unofficial APIs and libraries exist to access the same data, including of course yfinance.

Note you might know of yfinance under it’s old name- fix-yahoo-finance, since it was re-named on May 26th 2019. To ensure backwards compatibility, fix-yahoo-finance now imports and uses yfinance anyway.

Now, yfinance generally is considered great for prototyping, or doing basic research on historic data.

But if you are building a serious trading system requiring complete confidence and total reliability on the data fed to the system, I’d recommend going with a official and alternative market data provider- preferably one claiming to provide low latency data directly from exchanges.

Like Polygon or IEX
