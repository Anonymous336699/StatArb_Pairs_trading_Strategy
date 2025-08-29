# StatArb_Pairs_trading_Strategy
This repo is show Statistical Arbitrage Pairs trading strategy by using optimal pairs and robust system
**Code Correctness and Strengths**
- The code covers fundamental components of pairs trading well: cointegration test (ADF), hedge ratio estimation via OLS, spread and z-score calculation, and multiple threshold signals with position sizing.
- It handles multiple stock pairs, selects the pair with the minimum p-value from ADF test as the best pair, and visualizes important phases (correlation heatmap, z-score, trading signals).
- Portfolio weighting for combined return is included, which is useful for practical strategy evaluation.
- Use of statsmodels and matplotlib/seaborn is appropriate and standard for such analyses.

The code is fundamentally sound and a good starting point for pairs trading research and backtesting. However, for real-time deployment or company-level production use, enhancements in dynamic modeling, risk control, signal robustness, and automated execution are recommended to ensure adaptability, scalability, and profitability.
