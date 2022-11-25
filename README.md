# Simple-Moving-Average-coding-in-Python

- This notebook aims to:
    - read stock data using pandas datareader
    - visualize stock data
    - application of SMA as an indicator
- The strategy used in this example notebook is Simple Moving Average abbreviated as SMA
- SMA is a common indicator in technical analysis though a lagging indicator because it is dependent on past data amd prices
- SMA is a calculation that takes the arithmetic mean of a given set of prices over a specified number of periods.
- SMA helps to uncover the direction (bullish or bearish) of the trend in the data 
- Short term SMA crossing above/ over long term SMA indicates bullish movement of the price data
- The SMA strategy is to enter a buy position when SMA short term is above long term and enter a sell position when short term is below long term.
- While long term SMA crossing above/over the short term SMA indicates  a bearish movement of the price data of the stock (or cryptocurrency)
- Period  = 50 was used for the short term while period = 200 was used for the long term. 
- Period in here is DAY
- The mathematics behind SMA goes thus: 

$$ SMA = \dfrac{(A_1+A_2+A_3+...+A_n)}{n} $$
