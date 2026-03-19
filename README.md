# 📈 Stock Market Backtesting Engine (NumPy)

## 📌 Overview

This project implements a **stock market backtesting engine** using only NumPy.
It simulates a **moving average crossover trading strategy** on historical price data and evaluates performance based on portfolio returns.

---

## 🚀 Features

* Data cleaning and preprocessing from raw CSV
* Moving Average (MA) calculation using NumPy
* Signal generation (Buy/Sell) using MA crossover
* Backtesting engine for trade simulation
* Portfolio value tracking over time
* Final performance evaluation (profit & returns)

---

## 🧠 Strategy Used

### Moving Average Crossover

* **Short-term MA (10 days)**
* **Long-term MA (50 days)**

### Signal Logic:

* `MA_short > MA_long` → **Buy (1)**
* `MA_short < MA_long` → **Sell (-1)**

---

## ⚙️ How It Works

1. Load and clean stock price data
2. Convert data into NumPy arrays
3. Compute moving averages using convolution
4. Generate trading signals
5. Simulate trades using a backtesting loop
6. Track portfolio value over time

---

## 📊 Output

* Final Portfolio Value
* Total Profit / Loss
* Return Percentage
* Number of Trades (optional)

---

## 🛠️ Tech Stack

* Python
* NumPy

---

## 📂 Project Structure

```
moving_average_backtest.ipynb
data.csv
README.md
```

---

## 💡 Key Learnings

* Vectorized computations using NumPy
* Time-series data handling
* Financial strategy simulation
* Building logic without high-level libraries

---

## 🔥 Future Improvements

* Add multiple strategies
* Include transaction costs
* Support multi-stock backtesting
* Visualize results using plots

---

## 📄 Resume Description

Built a stock market backtesting engine using NumPy, implementing a moving average crossover strategy with vectorized signal generation and portfolio simulation. Evaluated trading performance using return-based metrics.

---
