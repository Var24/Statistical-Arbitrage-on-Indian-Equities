# Statistical-Arbitrage-on-Indian-Equities
Project for the Executive Program for Algorithmic Trading

## Abstract
This project attempts to build and back-test a very simple statistical arbitrage strategy on equity futures listed on the NSE. The equity futures are selected amongst the biggest firms in India by market capitalization from six different sectors. Thirty-two names across various sectors are selected to maximize any chances of catching a mean reverting spread between them. The strategy consists of trading a portfolio of cointegrating pairs. 
The code will serve as an excellent starting point to trade pairs trading strategy on the Indian Equity Futures market. At present, holding a short position overnight for many days is not allowed in the Indian markets. Therefore, this strategy is only suitable for futures contracts on stocks for which the positions can be rolled over into new months upon contract expiration. Mean reversion strategies such as this one are simple and robust to implement for retail traders because of their superior returns with respect to the risk even in highly volatile markets such as the first quarter of 2020 as demonstrated in the attached document of this git named "Statistical Arbitrage of Equity Futures on the NSE".
The entire dataset ranges from 1st January 2018 till 22nd October 2020.The dataset is split into training set to find the cointegrated pairs, bollinger band parameters and standard deviation amongst the pairs exhibiting highest cointegration with t_stat values lower than -2.87 or 95% confidence that the pair is cointegrated.
The test set is used to capture the actual strategy performance. The test set strategy performance is summarised in the image capture below:

![image](https://github.com/user-attachments/assets/5601f164-4505-4a0c-a663-bc47e8bfaf6f)





