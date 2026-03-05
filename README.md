# Finance & Data Portfolio

Quantitative finance projects using real market data.  
Focus areas: markets, trading, banking, risk, and actuarial-style modeling.

## What you'll find here
- Short, reproducible projects (Python + Jupyter)
- Clear visuals and results-first analysis
- Risk + volatility modeling (VaR, drawdowns, GARCH, etc.)

## Projects

### 01 — S&P 500 Market Risk Analysis
Market risk and volatility dynamics for the S&P 500.

**Key results**
- **Max drawdown:** **-33.9%** on **2020-03-23** (COVID crash)
- **Volatility clustering:** low ACF for returns, high ACF for **|returns|**
  - ACF(|returns|), lags 1–5 ≈ **0.32–0.40**
- Historical **VaR (95% / 99%)** and **Rolling 1Y VaR (95%)**
- **GARCH(1,1)** conditional volatility to capture persistence

**Links**
- Project folder: `projects/01_sp500_market_risk/`
- Notebook: `projects/01_sp500_market_risk/sp500_market_risk_analysis.ipynb`
- Clean view (nbviewer): https://nbviewer.org/github/carlakogoj/finance-data-portfolio/blob/main/projects/01_sp500_market_risk/sp500_market_risk_analysis.ipynb

## Repo structure
- `projects/` → one folder per project
- `data/` → raw/processed data (not tracked if large)
- `src/` → reusable code
- `dashboards/` → Power BI dashboards
- `docs/` → report assets (HTML/PDF/images)

## Tools
Python, pandas, numpy, matplotlib, plotly, statsmodels, yfinance, arch (GARCH)

## About
Carla Kogoj — Actuarial Science student (UBA).  
Interested in markets, banking, quantitative research, and risk modeling.