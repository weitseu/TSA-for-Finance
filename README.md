## 📂 tsa-for-finance/

- **stylized_facts_of_asset_returns.ipynb**
  - Non-normality (fat tails, skewness, kurtosis, Jarque-Bera test)
  - Linear autocorrelation patterns (Ljung-Box test)
  - Volatility clustering and test for ARCH effects
  - Leverage effect analysis (asymmetric volatility)

- **ARIMA_engine.ipynb**
  - Unit-root nonstationarity (augmented Dickey-Fuller test)
  - AR/MA order determination
  - ARIMA model selection (AIC/BIC) and fitting
  - Residual diagnostics and model validation
  - Parameter instability via rolling estimation
  - Out-of-sample forecasting
  - Forecast accuracy comparison

- **volatility_modeling.ipynb**
  - ARCH effect and leverage effect revisited
  - GARCH(1,1) model estimation
  - Asymmetric EGARCH and GJR-GARCH models
  - Standardized residuals diagnostics
  - Model comparison (conditional volatilities)
  - Volatility forecasting
  - Value at Risk with dynamic volatility

- **multivariate_time_series.ipynb**
  - VAR models and Granger's causality test
  - Impulse response function computation
  - Cointegration analysis (Engle-Granger's method)
  - Pairs trading strategy: hedge ratio estimation, spread deviation and trading signals
  - Paris trading strategy: backtesting framework and performance metrics
  - Principal component analysis