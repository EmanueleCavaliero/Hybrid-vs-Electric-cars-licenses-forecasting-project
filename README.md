# UK Electric and Hybrid Vehicle Registration Forecasting

This project implements a comprehensive forecasting framework to predict the adoption of electric and hybrid vehicles in the United Kingdom. It compares classical econometric models with modern statistical approaches to identify the most effective architecture for time series analysis in the automotive sector.

## Project Overview
The study focuses on quarterly registration data, evaluating how different modeling techniques handle trend, seasonality, and the impact of macroeconomic shifts.

### Implemented Methods:
* **ARIMA/ARIMAX:** Autoregressive Integrated Moving Average models, including versions with exogenous economic variables (interest rates and exchange rates).
* **Exponential Smoothing (ETS):** State-space models for error, trend, and seasonal decomposition.
* **Generalized Additive Models (GAM):** Semi-parametric approaches for capturing non-linear temporal dynamics.
* **Bass Diffusion Model:** Exploratory implementation to analyze technological adoption lifecycles.

## Dataset and Variables
* **Primary Series:** Quarterly new licenses for electric and hybrid vehicles in the UK.
* **Exogenous Drivers:** Bank of England interest rates and GBP exchange rates.
* **Methodology:** Time series stationarity testing (ADF, KPSS), model selection via AIC/BIC, and out-of-sample performance evaluation using MAE and RMSE.
or the Business, Economic and Financial Data (BEFD) course - University of Padua.*
