# Multi-Asset Portfolio Optimization & Volatility Engine

## Executive Summary
This project constructs an institutional market risk engine on 5 blue-chip equities using Markowitz Modern Portfolio Theory, GARCH(1,1) dynamic volatility modeling, and Monte Carlo Value at Risk (VaR) simulations under a $10M portfolio baseline.

## Key Outcomes & Risk Metrics
* **Tangency Portfolio:** Optimal Sharpe Ratio allocation of **15.65% Return** at **22.17% Volatility** (Sharpe = 0.4125, $R_f = 6.5\%$).
* **Asset Allocation:** HDFCBANK (47.15%), TCS (34.14%), INFY (18.72%).
* **1-Day 99% Value at Risk (VaR):** **$212,262** (Monte Carlo) / **$212,808** (Parametric GARCH).
* **1-Day 99% Expected Shortfall (CVaR):** **$247,689** (Monte Carlo).

## Tech Stack
* **Languages & Libraries:** Python (`yfinance`, `scipy`, `arch`, `pandas`, `numpy`, `seaborn`)
* **Models:** Markowitz Efficient Frontier, GARCH(1,1), Monte Carlo Simulation (10,000 paths)
