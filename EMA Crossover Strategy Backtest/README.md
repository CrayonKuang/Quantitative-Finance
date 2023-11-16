# EMA Crossover Strategy

Exponential Moving Averages are widely used by traders to measure trend direction over a period of time. EMAs place a higher weight on recent data than on data, thus they are more reactive to the latest price changes as compared to Smooth Moving Averages.

The EMA crossover strategy involves using two EMAs with different timeframes to generate buy and sell signals. For this project, I will be testing with 9-day EMA and 21-day EMA. Feel free to try other timeframes. The stock I will be using is "SPY" and I will be backtesting from '2022-01-01' to '2023-01-01'.

This is how the strategy will work:
* When the 9-day EMA crosses above the 21-day EMA, it generates a buy signal.
* When the 9-day EMA crosses below the 21-day EMA, it generates a sell signal.

I will be comparing this strategy to a simple "buy and hold" strategy and see which strategy gives higher cumulatives returns.
