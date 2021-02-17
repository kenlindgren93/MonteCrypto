# **Project1_MonteCrypto**

## Team: 

Cassandra Johnson, Ken Lindgren, Rawad Habib, Antonio Pinkston, Floriane Beyegue, Nigil Jeyashekar 

## Project Description: 

Our group analyzed different investments to see which types of investments gave the greatest return over a 5 year horizon (since January 1, 2015), and which instruments were projected to give the greatest return in the future.  We wanted a diverse portfolio, and compared small portfolios of stocks, crypto currency, metals, agricultural commodities, and also an investment in a index fund tied to the S&P500.  

We also wanted to determine what would be the 'optimal' portfolio mix of all investments, using the sharpe ratio to optimize risk and return.  We also tested if this 'optimal' mix would change when looking at investment performance pre-COVID vs. post-COVID using February 2020 as a cut-off date.  


## Questions 

**Question 1: Assuming investments in the S&P 500, a portfolio of stocks, commodities, metals, and cryptocurrency, from January 1, 2015 through October 31, 2020, which investment type has yielded the highest return??**

*Answer: The Cryptocurrency portfolio (a mix of BTC, ETH, and LTC) had the best historical returns over a five year period.*

![Daily Returns](/Images/Daily_Returns.png)
![Cumulative Returns](/Images/Cumulative_Returns.png)
![Cumulative Returns Without Crypto](/Images/Investments_withoutcrypto.png)



**Question 2: Which type of investment is projected to have the greatest return over the next five years?**

*Answer: Investing in a stock portfolio projected the greatest return over 5 years using a Monte Carlo Simulation, using the S&P500 performance as a benchmark.*  

There is a 95% chance that an pre-COVID initial investment of $100,000 in stocks over the next 5 years will end within in the range of $140212.92 and $437573.29.  This amount changed to a range of $13778.17 and $250966.36 using Post-COVID data.

There is a 95% chance that an pre-COVID initial investment of $100,000 in S&P 500 over the next 5 years will end within in the range of $90638.08 and $299660.57.  This amount changed to a range of $15151.74 and $416304.94 using Post-COVID data.  


S&P500 Pre-COVID
![S&P Pre-COVID](/Images/SP500_pre_covid.png)


S&P500 Post-COVID
![S&P Post-COVID](/Images/SP500_post_covid.png)


**Question 3: What's the ideal portfolio mix of all investments?**
**Question 4: Did COVID impact the ideal optimal portfolio?**

*Answer: The ideal portfolio is a mix of all investments, and changed significantly pre- and post-COVID.  For example the largest 3 investments in the pre-COVID optimal portfolio are: Gold, AAPL, and AMZN.  The 3 largest investments in the post-COVID portfolio are: ETH, Soybeans, and AMZN.*

![Optimum Portfolio](/Images/Optimal_portfolio.png)

Sharpe Total
![S&P Post-COVID](/Images/Sharpe_total.png)


Sharpe Pre-COVID
![S&P Post-COVID](/Images/Sharpe_precovid.png)


Sharpe Post-COVID
![S&P Post-COVID](/Images/Sharpe_postcovid.png)

We were surprised to see that while crypto currency had the best historical returns, it didn't compose a large portion of the optimal portfolio.  We attributed this to the fact that crypto was high return, but it was also high risk with high volatility.  We were also surprised to see items we considered low return, such as soybeans, to be a large holding in the optimal portfolio post-COVID.  After researching soybean performance, we realized this occurred because certain weather and international impacts caused soybean prices to rise significantly in the post-COVID time period. 

