# Bovespa stocks portfolio


## Getting the data

There are separated *Jupyter notebooks* explaining how to download and prepare the datasets.

*Main texts are in Portuguese but codes/comments are in English.*

**Data preparation**
 - Obtaining *Yahoo! Finance* historical quotes
   - [Jupyter notebook: downloading Bovespa stocks](./bovespa_stocks_download.ipynb) 
 - Data cleansing 
   - pre-processing [Jupyter notebook: pre-processing](./bovespa_stocks_preprocessing.ipynb)


## Portfolio via convex optimization of expected Sharpe Ratio

The objective is to elaborate a portfolio with good performance using a reduced number of stocks from the available list.

For each month, a stock portfolio is elaborated based on the Sharpe Ratio of log-return from the previous months. Portfolio performance is compared with three benchmarks:
- iBovespa: the official Index of Bovespa (composed of +60 stocks)
- Avg. BVSP: the simple average of all available stocks of iBovespa
- Dolar: The current value of USD Dolars in Brazilian Reais
	    

*Expected results:*
- Improved (average) performance on the long run
- High volatility due to small number of stocks composing the portfolio


**See the [Jupyter notebook](./bovespa_stocks_portfolio.ipynb) presenting the whole procedure.**


## Portfolio optimization based on supervised-learning

*In preparation.*



















