# S&P 500 Market Risk Analysis

This project analyzes market risk and volatility dynamics of the S&P 500 using Python.

## Topics covered
- Daily returns
- Volatility clustering
- Maximum drawdown
- Historical Value at Risk (VaR)
- GARCH volatility model

## Key findings
- The maximum drawdown in the analyzed period occurred during the COVID crash on March 23, 2020, with a decline of approximately **-33.9%**.
- Daily returns exhibit low autocorrelation.
- Absolute returns show strong persistence, confirming volatility clustering.
- Rolling VaR highlights increases in downside risk during crisis periods.
- A GARCH(1,1) model captures volatility persistence.

## Tools
- Python
- Pandas, Numpy
- Matplotlib
- yfinance
- arch (GARCH)
