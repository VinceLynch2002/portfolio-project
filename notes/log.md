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