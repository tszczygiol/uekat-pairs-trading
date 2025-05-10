# Pitch

The project was developed as part of the **"Rynek Finansowy"** course at the University of Economics in Katowice. It presents an implementation of the **pairs trading strategy** using Python and its libraries. Calculations are performed on historical data of companies listed on the Warsaw Stock Exchange (GPW), but the final selection of stocks is left to the User.

The main purpose of this project is educational. It aims to present the key steps necessary to understand and apply this trading strategy.

---

## Repository Contents

- `pairs_trading_notebook.ipynb` – Jupyter Notebook with code, charts, and results  
- `pairs_trading.py` – Python script exported from the notebook  
- `requirements.txt` – list of required Python libraries

---

## Functionality

- Fetching OHLCV stock data using the **Pandas Datareader API**
- Calculating deviations, generating buy/sell signals, and data storage – **Pandas and NumPy**
- Visualizations: closing prices, spread, signals – **matplotlib, seaborn**
- ADF stationarity test and linear regression – **statsmodels**
- Summary table of strategy results – **tabulate**

---

## Installation

```bash
git clone https://github.com/tszczygiol/uekat-pairs-trading.git
cd uekat-pairs-trading
pip install -r requirements.txt
jupyter notebook pairs_trading_notebook.ipynb
