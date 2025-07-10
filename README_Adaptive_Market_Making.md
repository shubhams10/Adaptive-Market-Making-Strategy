# Adaptive Market-Making Strategy

This project involves the development and simulation of an adaptive algorithmic market-making strategy using the Bristol Stock Exchange (BSE) simulator.

## 📌 Overview
The goal was to implement an intelligent market-making agent (AMMT) capable of adjusting bid-ask spreads dynamically based on real-time market signals. It was benchmarked against other agents such as MMM01, MMM02, and MMM03.

## 🔧 Technologies Used
- Python
- Pandas, NumPy
- Matplotlib
- Custom-modified BSE simulator (`BSE.py`)

## ⚙️ Features
- Moving average crossover logic for price trend detection
- Inventory-aware trading restrictions
- Dynamic spread adjustments based on market conditions
- Real-time data tracking and trade decision making

## 📈 Results
- Achieved a **15.2% improvement** in portfolio returns
- Sharpe Ratio of **0.2456**
- Statistically validated performance using **t-tests** and **ANOVA**

## 📊 Strategy Summary
The AMMT trader maintained consistent profitability even under volatile market conditions, outperforming other strategies through smarter risk control and market responsiveness.

## 📁 Files
- `BSE.py`: Modified simulator code
- `AMMT_trader.py`: Adaptive trader logic
- `results/`: Simulation results and performance plots