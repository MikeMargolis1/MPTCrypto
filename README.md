# MPTCrypto


In this project I will be applying Modern Portfolio Theory to cryptocurrencies. I will be using the Markowitz Optimal Portfolio solution to determine portfolio weights for various cryptocurrencies. These portfolios will take returns and risk into consideration. The data used in this analysis is from Kaggle and a link to the dataset can be found in the HTML file above.

To simplify the Markowitz optimal portfolio solution, I look at two coins Bitcoin (BTC) and Ethereum (ETH) to start. I first observe the mean and standard deviation for each coin’s monthly returns, using the logged closed price for each coin. I then calculate the correlation matrix between the two coins to see how they are correlated.

I then plot the Markowitz frontier for these two assets where I have assumed that the annualized 1-month risk-free rate is 0.05%. This analysis will determine what the optimal portfolio weights are if you were to only invest in BTC and ETH. I found that the optimal portfolio consists of 70% BTC and 30% ETH.

I then see what an optimal portfolio would look like with a lot of coins, 9 to be exact.

For these 9 coins I computed the correlation matrix to see how each coin’s price change is correlated. 

Next, I computed the Sharp Ratios for each coin.

I then plotted the Markowitz frontier for these assets, where I again have assumed that the annualized 1-month risk-free rate is 0.05%. This provides me with the optimal portfolio balance if someone was to invest in 9 of these coins. I found that you should invest 65% in BTC, 10% in ETH, and 15% in BNB, ignoring all the other coins available. 


