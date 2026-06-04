# Portfolio Risk Management and Optimization

### Forecasting Volatility, Measuring Risk, and Constructing Optimal Portfolios with GARCH Models

![R](https://img.shields.io/badge/R-276DC3?style=for-the-badge&logo=r&logoColor=white)
![Finance](https://img.shields.io/badge/Finance-0A66C2?style=for-the-badge)
![Risk Analytics](https://img.shields.io/badge/Risk%20Analytics-8E44AD?style=for-the-badge)
![Time Series](https://img.shields.io/badge/Time%20Series-16A085?style=for-the-badge)
![Portfolio Optimization](https://img.shields.io/badge/Portfolio%20Optimization-E67E22?style=for-the-badge)

> Built as part of advanced coursework in Financial Econometrics and Time Series Analysis at the University of Toronto.

## Quick Links


💼 [LinkedIn](https://www.linkedin.com/in/danielpuente/)

🌐 [Personal Website](https://cudapuca.base44.app)

🏃 [Running Account](https://www.instagram.com/dandrunner)

---

## Why I Built This Project

Most people look at a stock chart and ask:

**"Will it go up or down?"**

I became more interested in a different question:

**"How risky is it?"**

This project was my introduction to the world of quantitative finance. Using volatility models, risk measures, and portfolio optimization techniques, I explored how investors can better understand uncertainty rather than simply chase returns.

Along the way, I discovered that managing risk is often just as important as finding opportunities, a lesson that continues to shape how I think about finance, analytics, and decision-making.

---

## Project Overview

This project applies modern financial econometric techniques to forecast market volatility, estimate downside risk, and construct an optimal portfolio using real financial data.

The project consists of two major components:

### Univariate Risk Modeling

Using NASDAQ returns, I estimated future volatility and calculated:

- Value at Risk (VaR)
- Expected Shortfall (ES)

### Portfolio Optimization

Using a portfolio of pharmaceutical companies, I estimated dynamic correlations between assets and constructed an optimal tangency portfolio.

The analysis demonstrates how statistical models can be used to support risk management and investment decisions.

---

## Mathematical Framework

### Log Returns

Financial returns were calculated using:

`rₜ = 100 × (ln(Pₜ) − ln(Pₜ₋₁))`

where:

- Pₜ = asset price at time t
- rₜ = percentage return

### Volatility Forecasting

Volatility was modeled using an ARMA-GARCH framework to capture volatility clustering, one of the most common characteristics of financial markets.

### Value at Risk (VaR)

`VaR = V × |μ − 2.33σ|`

where:

- V = portfolio value
- μ = expected return
- σ = forecast volatility

### Expected Shortfall (ES)

`ES = V × |μ − 2.64σ|`

Expected Shortfall measures the average loss once losses exceed the VaR threshold.

### Tangency Portfolio

The portfolio maximizes the Sharpe Ratio:

`Sharpe Ratio = (Expected Return − Risk-Free Rate) / Portfolio Volatility`

using forecasted returns and covariance matrices.

---

## Portfolio Assets

- Pfizer
- AstraZeneca
- Johnson & Johnson
- Merck
- Eli Lilly
- Bristol-Myers Squibb

These assets were selected to demonstrate covariance estimation and portfolio optimization within the healthcare sector.

---

## Methodology

### Risk Modeling

- ARMA-GARCH Volatility Forecasting
- Value at Risk (VaR)
- Expected Shortfall (ES)

### Portfolio Analytics

- DCC-GARCH Correlation Modeling
- Covariance Matrix Forecasting
- Tangency Portfolio Optimization
- Risk-Adjusted Portfolio Construction

---

## Key Findings

### Volatility Matters

The GARCH model successfully captured volatility clustering and produced forecasts of future market risk.

### Risk Changes Over Time

Both Value at Risk and Expected Shortfall increased during periods of higher forecast volatility, highlighting the importance of dynamic risk measurement.

### Correlations Are Not Constant

The DCC-GARCH model revealed that asset correlations evolve through time. Accounting for these changing relationships can lead to more informed portfolio allocation decisions.

---

## What I Learned

This project taught me that risk is much more complex than simply measuring returns.

Two assets can appear attractive individually, but their relationship with each other can dramatically change the overall risk of a portfolio. Understanding volatility and correlations is often just as important as understanding expected returns.

Most importantly, I learned how statistical models can support investment decisions by providing a structured framework for measuring uncertainty.

---

## Skills Demonstrated

### Quantitative Finance

- Portfolio Optimization
- Risk Analytics
- Value at Risk (VaR)
- Expected Shortfall (ES)
- Sharpe Ratio Optimization

### Econometrics & Statistics

- ARMA Models
- GARCH Models
- DCC-GARCH
- Volatility Forecasting
- Covariance Forecasting

### Data Science

- Time Series Analysis
- Financial Data Analysis
- Statistical Modeling
- Data Visualization

### Tools

- R
- Quantmod
- rugarch
- rmgarch
- ggplot2
- Git
- GitHub

---

## Repository Structure

```text
portfolio-risk-management-and-optimization/
│
├── README.md
├── Project_Report.pdf
├── Volatility, VaR, Expected Shortfall & Portfolio Optimization.Rmd
```

---

## About Me

I'm **Daniel Puente**, a Statistics and Economics graduate from the University of Toronto and an incoming Master of Management in Analytics student at McGill University.
