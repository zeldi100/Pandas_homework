# Pandas | Introduction to Pandas
## Fintech Bootcamp 
___

### Objective
The objective of this script is to apply quantitative analysis techniques of Python and Pandas to run a comparison of portfolios to determine the best performance considering: volatility, returns, risk and Sharpe ratios.

This is done on the following 2 portfolios which are compared with S&P 500:
 * company's algorithmic portfolio
 * a portfolio that represent some of famous "whale" investors

The last part of the script incorporates 5 stocks which are incorporated into a custom portfolio which are then compared against the Algo- and Whale- portfolios and S&P 500.

### Main tasks:
#### 1. Data preparation
   * Read data from csv into pandas </br>
   * Clean the data (sort data and drop nulls) </br>
   * Convert S&P 500 stock price data to daily returns
   * Combine into a single dataframe </br>

#### 2. Perform quantitative analysis 
   * Calculate performance and plot daily and cumulative returns
   * Determine the risk for each portfolio: </br> 
      * Box plot each portfolio
      * Calculate standard deviation
      * Calculate annualized standard deviation
      * Determine risk over time by plotting rolling standard deviation and rolling Beta
      * Calculate the correlation between S&P500 and other portfolios
      * Calculate a rolling window using the exponentially weighted moving average
      * Calculate annualized Sharpe ratios and visualize on box plot
   
#### 3. Evaluate custom portfolio
   * Import price data from 5 stocks and combine into single portfolio </br>
   * Compare custom portfolio with other portfolios 


### Instructions:
Use the [Jupiter notebook](Portfolio_Analysis.ipynb) to run the analysis. 
The data is located in the following files:
1. [Algo financial returns portfolio](Resources/algo_returns.csv)
2. [Whale investor returns portfolio](Resources/whale_returns.csv)
3. [S&P 500 historical prices](Resources/sp500_history.csv)
4. Custom portfolio stock price files:
   * [Royal Bank of Canada](Resources/rbc_hist.csv)
   * [Tesla](Resources/tsla_hist.csv)
   * [Shopify](Resources/shop_hist.csv)
   * [Open Text](Resources/opentext_hist.csv)
   * [Canadian Rail](Resources/cnr_hist.csv)
   
### Outcome:
Algo1 and the Custom portfolio outperforms the S&P 500. The Custom Portfolio has the highest standard devitation between the 3, indicating that it is a riskier portfolio compared to S&P500 and Algo1. Both Tiger and Berkshire have high returns, but are more volatile and thus higher risk stocks. Considering risk and performance the Algo1 stock is best performing stock with highest return for the lowest volatility and risk.
   
   




