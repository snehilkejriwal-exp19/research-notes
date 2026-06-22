# Econometrics for Finance

Applied econometrics implemented in Python using real Indian market data.
Built as part of a structured quant finance curriculum.

## Notebooks

### econometrics_fundamentals.ipynb
| Section | Concept | Method |
|---------|---------|--------|
| E1 | OLS Foundations | Manual β calculation vs statsmodels, R² interpretation |
| E2 | Heteroskedasticity | Breusch-Pagan test, residual scatter diagnosis |
| E3 | GLS | Robust standard errors vs WLS, three-way comparison table |
| E4 | Panel Data | Poolability F-test with p = 0.8693, fixed effects was not required |
| E5 | Cointegration | Testing pairs via Engle-Granger Test reveals that window length is vital for the p-value |
| E6 | VAR Model | Analyse the effect of NIFTY50 AND S&P500 on each other using Granger casuality test revealing indifferent trading hours|
|E7  | Pairs Trading Strategy | Britannia/Nestle pair due to strong cointegration evealuated via z-score test |

## Capstone Findings — E7 Pairs Trading
- Britannia/Nestle pair chosen due to strong cointegration (p-value = 0.018)
- Strategy returned -13.95% vs buy-and-hold's +67.87% over 2020-2025
- Cointegration confirms a long-run relationship exists, but doesn't guarantee profitability — the relationship's strength can vary across sub-periods, and naive fixed ±2 std-dev thresholds with no transaction costs modeled are a simplified starting signal, not a production-grade strategy

**Stack:** Python, pandas, numpy, statsmodels  
**Data:** Nifty 50, HDFC Bank, ICICI, Bajaj Finance, Bajaj Finserv, Tata Steel, JSW Steel, Sun Pharma, Cipla, UltraCemco, Shree Cement, Maruti, M&M, Britannia, Nestle, BPCL, HINDPETRO, ONGC, OIL India, S&P 500

## Author
Snehil Kejriwal — Economics + B.Tech, BITS Pilani Hyderabad
github.com/snehilkejriwal-exp19