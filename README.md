# Algorithmic-Trading
 A few notebooks that I published to help anyone who wants to get started with how to write python code for backtesting, running live trading strategies and how to manage risk and return of a portfolio. 
 1) 0920_ATM notebook has code for selling BankNifty ATM straddle at 9:20 AM and the code is connected to run live with symphony XTS trading platform.
 2) For portfolio management I used efficient frontier concept from Modern Portfolio Theory. I used 4 instruments bonds, commodities, equities and cryptocurrency and found optimal weights. The optimal risky portfolio gave annualized returns of 20.05% with a volatility of 16.83% and a sharpe ratio of 1.042
 3) For statistical arbitrage I backtested pairs that I found using pearson correlation coefficient and hurst coefficient. You can also use cointegration. The pair trading backtests are based on selling when pair ratio reaches +2 SD, squaring-off when they revert to mean and buying when pair ratio reaches -2 SD, squaring-off when they revert to mean. You can also tweak this strategy to get better results.
 
