# Pairs Trading Strategy with Forex
Pairs trading is a market-neutral trading strategy that involves the simultaneous buying and selling of two highly correlated financial instruments, such as two stocks, forex pairs, etc. to profit from the relative price movements between them.

1. Use cointegration test to find two stocks that are cointegrated. Cointegration is a statistical concept that decribes a long-term relationship between 2 or more non-stationary time series variables.

2. Obtain a normal range of historical spread for the pair of cointegrated assets.

3. Compare current spread with historical spreads to assess if the former exceeds a normal range.

4. If short-term fluctuations occurs due to market fluctuations, buy the underperforming asset while short-selling the overperforming asset.

5. When the current spread reverts back to the normal range, exit the positions and lock in a profit.

In this exercise, I will be experimenting this strategy with Major forex pairs.
