## [coinmarketcappy](https://github.com/saporitigianni/coinmarketcappy)
- Makes API calls or scrapes data from [coinmarketcap.com](https://coinmarketcap.com/) which according to their [FAQ](https://coinmarketcap.com/faq/) is free to use as long as you cite them as the source. 
- Allows saving data to JSON or CSV formats.
- Install with `pip install coinmarketcappy` and use `help()` on any method to view basic documentation.

## [fixerio3](https://github.com/saporitigianni/fixerio3)
- Interacts with the [fixer.io](https://fixer.io/) JSON API to retrieve currency exchange rates.
- Caches the results locally to limit the number of API calls made to the service and speed up subsequent access times.
- Work in progress, they recently changed their API so it might need some adjustments.

## Single Level FTSE Russell Capping
- Takes in a set of JSON formatted financial information for a given set of assets and returns the market cap weighted version of the data capped at the specified percentage using the single-level method.

## CCArbitrage
- Private, automated cryptocurrency arbitrage system integrated with about 10 exchanges that searches and automatically executes arbitrage opportunities.
- Needs some work handling asymmetrically stale and failed order pairs.

## onestop_financial
- Takes in a JSON formatted set of financial data for a given asset or fund and runs several metrics on the data such as Sharpe ratio, Sortino ratio, etc.
- For funds it can also evaluate different strategies/timeframes/weights and return a comparison.
