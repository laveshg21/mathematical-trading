# Mathematical Trading Strategies

## Week 1-2: Financial Metrics
- Learn about important techniques for evaluating investements:
  - Returns
  - [Cumulative Returns](https://www.investopedia.com/terms/c/cumulativereturn.asp)
  - [Max Drawdowns](https://www.investopedia.com/terms/m/maximum-drawdown-mdd.asp)
  - [The Sharpe Ratio](https://groww.in/p/sharpe-ratio)
  - [The Sortino Ratio](https://groww.in/p/sortino-ratio)
- Selecting five international `indexes` and five `equities`.
- Leverage [`yfinance`](https://pypi.org/project/yfinance/) to access financial data for the chosen indexes and equities.
- Compile and present the aforementioned data (evaluations/ratios) in tabular form.

## Week 2: Lead Lag Relationship
Learnt generating trade signals using Python, let's delve into some basic strategies. First in line is the implementation of moving averages. Have a look at the resources on Simple Moving Average (SMA), Exponential Moving Average (EMA), and the advantages of EMA over SMA. Explore how the crossover of moving averages with different intervals can help in trend identification.

https://www.investopedia.com/terms/e/ema.asp
https://www.investopedia.com/articles/active-trading/052014/how-use-moving-average-buy-stocks.asp
https://www.netpicks.com/three-moving-average-crossover/ 

Assignment 3-4:
The objective of this assignment is to analyze the NASDAQ and NSE indices to identify their correlation and establish potential lead-lag relationships. The next step is to code Keltner Channel, Bollinger Bands, and MACD indicators, determining the optimal parameters for these indicators on one of the indices, and generating buy and sell signals on the other index. 
Note : Utilize the established relationship to determine which index should be used for parameter optimization and which one for trading purposes.

Tasks:

Correlation Analysis:
a) Collect historical data for NASDAQ and NSE indices.
b) Calculate the correlation coefficient between the two indices.
c) Analyze the strength and direction of the relationship.

Lead-Lag Relationship:
a) Identify potential lead-lag relationships between the indices.
b) Analyze data to determine consistent leading or lagging behavior.
c) Use the lead-lag relationship to determine the index to be used for parameter optimization.
d) Provide an explanation for choosing the index for parameter optimization

Indicator Coding:
a) Code Keltner Channel, Bollinger Bands, and MACD indicators.

Parameter Optimization:
a) Optimize parameters for the indicators on one index.
b) Use metrics coded in last assignment to evaluate your strategy.
c) Document the optimized parameters for future reference.

Signal Generation:
a) Apply optimized parameters to the other index.
b) Generate buy and sell signals using the indicators.
c) Record the signals, their respective dates and returns along with other metrics covered before.

## Week 5-6: Stock Chart Pattern
For Assignment 3, please select 10 stocks of your choice and identify the chart patterns mentioned below. If you have an odd roll number, you are assigned patterns with odd index numbers, and if your roll number is even, use patterns with even index numbers. Edit out all the points on the stock's chart where the allotted chart patterns occur. Use your own intuition when identifying these patterns, such as defining roundness or the desired cup shape in the cup and handle pattern. The look-back period is 10 years with a 1-day tick interval.

Chart Patterns:

1) Ascending triangle
2) Descending triangle
3) Bear flag
4) Bull flag
5) Cup and handle
6) Inverse cup and handle
7) Head and shoulder
8) Inverse head and shoulder
9) Rounding top
10) Rounding bottom
When submitting your assignment, make sure to include screenshots of the stock charts with timestamps indicating the start of each pattern. Remember to provide separate screenshots for each of the five chart patterns showcasing your observations.

If you encounter any confusion regarding the definitions of the chart patterns, we recommed referring to Investopedia for clarity.
https://www.investopedia.com/articles/technical/112601.asp

## Week 7-8: Complete Trading Strategy
For the final assignment of this proejct, you need to design and implement an effective trading strategy using a combination of a technical indicator and a chart pattern or candlestick pattern. The objective is to optimize the strategy based on the evaluation criteria of cumulative returns, maximum drawdown, and Sharpe ratio. Along with Jupyter notebook, submit a doc explaining the approach taken to combine these indicators and patterns. You should also provide a logical explanation regarding any limitations in detecting specific price trends. Any additional enhancements to the strategy are encouraged and should be included. The strategy must be tested on a 10 year period, ending on the submission day, using any chosen Indian equity. The document should include the values of the three metrics mentioned and can also discuss other combinations or logics that were explored before finalizing the strategy.
