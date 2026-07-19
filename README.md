## 📂 tsa-for-finance/

- **stylized_facts_of_asset_returns.ipynb**
  - Non-normality: fat tails, skewness, kurtosis (Jarque-Bera, Shapiro-Wilk, Anderson-Darling, Kolmogorov-Smirnov)
  - Linear autocorrelation and weak-form efficiency (Ljung-Box)
  - Volatility clustering and tests for ARCH effects (Engle's LM test)
  - The leverage effect: asymmetric response of volatility to news
  - Cross-asset correlation and its instability
  - Tail dependence measured on the empirical copula, benchmarked against a Gaussian copula of equal correlation

- **ARIMA_engine.ipynb**
  - Unit roots and stationarity (ADF and KPSS, read together)
  - Order identification from the ACF and PACF
  - Model selection by AIC/BIC, estimation, and residual diagnostics
  - Seasonality: testing the premise rather than assuming it (seasonally adjusted vs unadjusted CPI, and when a SARIMA actually helps)
  - Parameter instability under regime change (rolling estimation)
  - Out-of-sample forecasting against naive, random-walk, and mean benchmarks
  - Diebold-Mariano test with the Harvey-Leybourne-Newbold small-sample correction

- **volatility_modeling.ipynb**
  - ARCH effects and the leverage effect, revisited inside a model
  - GARCH(1,1): persistence, half-life, and the long-run variance
  - Student-t innovations: what survives standardizing by the conditional volatility
  - Asymmetric models (EGARCH, GJR-GARCH) and a likelihood-ratio test of whether the asymmetry earns its parameter
  - Out-of-sample volatility forecasting, evaluated on the variance scale with QLIKE (why scoring against |r| is biased)
  - Dynamic Value at Risk and Expected Shortfall
  - VaR backtesting at 95% and 99% (Kupiec, Christoffersen), and why fat tails are invisible at one level and decisive at the other

- **multivariate_time_series.ipynb**
  - VAR models and lag selection
  - Granger causality, and the multiple-testing trap of scanning lags for the smallest p-value
  - Impulse response functions and the identification problem (the Cholesky ordering is an assumption)
  - Cointegration by the Engle-Granger method
  - Pairs trading: hedge ratio, spread z-score, signals, and a P&L computed on the correct capital base
  - Backtesting, performance metrics, and parameter-sensitivity analysis read for stability rather than for its maximum
  - Principal component analysis: the market factor, and how many independent bets a portfolio really contains