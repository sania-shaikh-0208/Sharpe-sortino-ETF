# Sharpe-sortino-ETF
SQIG submission

# 📊 ETF Portfolio Optimization — Sharpe & Sortino Ratio-Based Strategy

This repo features a Python-based ETF portfolio optimizer that uses **Sharpe Ratio** and **Sortino Ratio** to build a risk-adjusted, blended investment strategy. The model evaluates historical return data, normalizes performance scores, assigns portfolio weights, and simulates performance with quarterly rebalancing. 👩‍💻📈

---

## 🚀 Quick Overview

- Calculates **daily returns** of selected ETFs
- Computes **Sharpe & Sortino Ratios** to assess risk-adjusted performance
- Normalizes scores and generates **portfolio weights**
- Simulates **portfolio growth over time** with quarterly rebalancing
- Outputs key metrics like:
  - Final portfolio value
  - Sharpe Ratio
  - Max Drawdown

---

## 🧪 Methods Used

| Metric           | Description |
|------------------|-------------|
| **Sharpe Ratio** | Reward per unit of total risk |
| **Sortino Ratio**| Reward per unit of *downside* risk only |
| **Max Drawdown** | Measures worst loss from peak to trough |
| **Quarterly Rebalancing** | On Jan 1, Apr 1, Jul 1, Oct 1 |

---
