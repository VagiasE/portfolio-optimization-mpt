# Portfolio Optimization using Modern Portfolio Theory

This project applies Modern Portfolio Theory (Markowitz framework)
to a four-asset US equity portfolio:

AAPL, MSFT, GOOGL, AMZN.

## Objective

The objective is to compare an equal-weight portfolio with optimized
portfolios obtained through Monte Carlo simulation, focusing on
risk, return, and Sharpe ratio.

## Methodology

- Download daily closing prices from Yahoo Finance
- Compute daily returns
- Estimate annual return and volatility using the covariance matrix
- Generate 5,000 random portfolios
- Identify the Minimum Volatility and Maximum Sharpe portfolios
- Simulate cumulative performance for a 10,000 EUR investment

## Tools & Libraries

- Python
- NumPy
- pandas
- matplotlib
- yfinance

## Notes

Prices are based on daily closing values (Close).
Using adjusted closing prices would account for dividends and splits,
but does not materially affect the comparative comparison.

