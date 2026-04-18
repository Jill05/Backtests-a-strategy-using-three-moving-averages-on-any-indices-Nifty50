# Backtests-a-strategy-using-three-moving-averages-on-any-indices-Nifty50

1. Compute three moving averages of 20, 40, and 80.
2. Go long when the price crosses above all three moving averages.
3. Exit the long position when the price crosses below any of the three moving
averages.
4. Go short when the price crosses below all three moving averages.
5. Exit the short position when the price crosses above any of the three moving
averages.
6. Optional: Optimise all three moving averages
II. Buy and sell the next day
1. Buy the stock on the fourth day open, if the stock closes down consecutively for
three days.
2. Exit on the next day open.
3. Optional: Optimise the strategy by exiting the long position on the same day close.
Also, you can optimise the number of down days. There are high chances that the
number of down days would be different for each stock.
III. Strategy based on RSI indicator.
1. Buy the instrument such as Nifty or SPY when the RSI is less than 15
2. Exit conditions:
a. Take profit of 5% or RSI > 75
b. Stop loss of - 2%

