# Project Log

## 2026-10-30: Project setup

**Goal:** Mixed portfolio in Python + Excel with backtesting, then options/derivatives overlays

- Created project folder with notebooks/, src/, tests/, data/
- Set up virtual environment (.venv) and installed packages
- Saved package versions to requirements.txt
    - Records the exact version of each package, so the project can be rebuilt the same way later with `pip install -r requirements.txt`
- Added .gitignore to keep .venv and junk files off GitHub
- Created GitHub repo `portfolio-project` and pushed
- Started this log under notes/

## 2026-10-30: First code
- Picked 11 ETFs across stocks, bonds, and real assets (plus BIL as cash-equivalent)
    - BIL holds T-Bills which aren't cash but behaves like it with its short maturity and liquidity
- Stored tickers and weights together in a dictionary
- Downloaded adjusted prices from 2015 with yfinance
- Checked data shape and missing values

## 2026-11-02: Practice files
- Added 3 practice files for numpy, pandas, and yfinance based off what their source documents say. Reason?... knowing what it goes is good but why it does what it does (each library) is great.

## 2026-11-03/04: NumPy
- continued to work through NumPy source documents and lectures to deepen understanding from what to why.

## 2026-11-05: Continuation of learning and committing
- updating previous last few days work to GitHub

## 2026-11-09: Risk and Returns
- updating any previous work to GitHub
- worked on returns and risks of stock, portfolios, and indices
- calculated a very rough sharpe ratio using arrays
- plotted normalized returns to see growth of stocks compared to each other as well as specific stocks compared to market
- all work on data.ipynb
## 2026-11-10: Covariance and Correlation start
- worked on covariance and correlation of Apple and Microsoft using the risk data returns
