# Buying Different Tech Stocks, or Buying the Same Risk Repeatedly?

**A quantitative study of diversification, common risk, downside exposure, and portfolio optimization.**

**Author:** Octavio Adolfo Ramos Calderón  
**Institution:** Universidad La Salle, Mexico City  
**Research period:** January 2020 – September 2026

## Overview

Does investing in multiple technology stocks genuinely diversify risk, or does it concentrate exposure to the same underlying market movements?

This project examines eight technology-related equities (AAPL, MSFT, NVDA, META, GOOGL, AMD, TSM, and ASML) using historical daily returns.

The analysis combines correlation analysis, Principal Component Analysis (PCA), volatility risk attribution, historical stress testing, and portfolio optimization.

## Key Findings

- **Average pairwise correlation:** 0.549.
- **First principal component:** 60.67% of standardized-return variance.
- **Risk concentration:** AMD and NVDA represented 25% of invested capital but contributed 35.01% of equal-weight portfolio volatility.
- **Out-of-sample optimization:** The Minimum Variance portfolio achieved 20.4% lower annualized volatility than Equal Weight during the 2024–September 2026 evaluation period.
- **Changing dependence:** PC1 explained 69.06% of variance in 2020–2021, compared with 47.85% in 2024–September 2026.

## Methodology

1. Historical adjusted-price data from Yahoo Finance.
2. Daily simple-return calculations and correlation analysis.
3. PCA on standardized returns.
4. Euler decomposition of portfolio volatility.
5. Historical stress-window analysis.
6. Long-only Minimum Variance and historical Minimum CVaR optimization, with a 35% maximum allocation per security.
7. Out-of-sample portfolio evaluation and benchmark exposure analysis.

Portfolio weights were estimated using 2020–2023 observations and evaluated on 2024–September 2026 data.

## Tools

Python · pandas · NumPy · SciPy · scikit-learn · Matplotlib · yfinance · Google Colab

## Research Limitations

This is a retrospective, exploratory study—not investment advice or a trading strategy. The universe was selected with hindsight, and the backtests exclude trading costs, taxes, slippage, and market impact.

The study uses one training/testing split, and historical performance does not guarantee future results.

## Code

The complete research notebook is available in this repository:

**`tech_stock_diversification.ipynb`**

## Research Report

The full research report, including methodology, empirical results,
portfolio optimization and limitations, is available here:

[Read the full research report]([Buying Different Tech Stocks, or Buying the Same Risk Repeatedly.pdf](https://github.com/OctaRamss/tech-stock-diversification/blob/main/Buying%20Different%20Tech%20Stocks%2C%20or%20Buying%20the%20Same%20Risk%20Repeatedly.pdf)
