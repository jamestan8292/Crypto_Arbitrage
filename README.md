# Crypto_Arbitrage

This application identifies arbitrage opportunities in Bitcoin and other cryptocurrencies. As Bitcoin trades on markets across the globe, there may be opportunities to capitalize on simultaneous price dislocations in those markets by using Pandas.

This application sorts through historical trade data for Bitcoin (other cryptocurrencies) on two exchanges: named Bitstamp and Coinbase in this application. Data is provided to the application in the same directory as the application under a folder "Resources". The crytocurrency data with the higher trading prices is in file "coinbase.csv" and the crytocurrency data with the lower trading prices is in the file "bitstamp.csv")

This application works through 3 phases.

   1. Collect the data.

   2. Prepare the data.

   3. Analyze the data.


---

## Technologies

This application is written for use with Jupyter Lab and it uses the following package:

* [Pandas](https://github.com/pandas-dev/pandas) - For the command line interface, help page, and entry-point.


---



## Usage

In Windows GitBash or Mac Terminal app, enter "Jupyter Lab". Then open and run "crypto_arbitrage.ipynb" Data must be provided to the application in the same directory as the application under a folder "Resources". The crytocurrency data with the higher trading prices must be in file "coinbase.csv" and the crytocurrency data with the lower trading prices must in the file "bitstamp.csv"). The datafile must consist of at least the "Timestamp" and 'Close' columns.

---

## Contributors

This application is written by James Tan, with code snippets provided UBC Extension.

---

## License

MIT.

