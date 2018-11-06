# MovingAverageAlgoTrader

This script uses information provided by the AlphaVantage API (alphavantage.co) to create trade signals.
The strategy represented here is a simple momentum-based strategy, where trade signals are based on the crossover
of a faster moving average value and a slower one. This strategy is often used as an introduction into algorithmic trading
similar to how Hello World is used as an introduction to programming.

In the future, I would like to expand the AlphaVantage class and include functions to access more of the data available
via their API and expand the Trader class to allow different strategies to be used.
