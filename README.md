# Advanced Portfolio Optimization: The Black-Litterman Model

 ## Motivation

 __Problems of Mean-Variance-Optimization (MVO)__

 - can lead to __short__ positions and positions __> 1__ (unbounded)
- will certainly lead to __concentrated__ portfolios (unbounded)
- highly dependent on & sensitive to __inputs/assumptions__ (return forecasts) -> GIGO
- small changes in forecasts (returns) lead to __large changes in weights__ (rebalancing costs!)
- __no guarantee__ that MVO-optimized Portfolio performs better than naive-diversified portfolio

__Biggest Issue: Forecasting Returns__

There are various return forecasting models. But, these models:
- lead to conflicting results...
- require assumptions/inputs (GIGO)...
- don´t guarantee accurate forecasts
- can´t be applied to all asset classes (e.g. Cryptocurrencies)


__Alternative Approach__: Why not starting with (average) __Market Expectations__ (implied returns)?


__Key Learnings__:
- Black-Litterman (BL) more meaningful/reliable if the entire market is included 
- small forecast changes lead to large changes in weights (be careful)
- BL should be combined with additional bounds/constraints
- opinions should be derived from / verified with other forecasting models
