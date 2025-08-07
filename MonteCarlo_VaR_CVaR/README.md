# 📉 Value at Risk (VaR) and Conditional Value at Risk (CVaR) Simulation

This project estimates **Value at Risk (VaR)** and **Conditional Value at Risk (CVaR)** using historical or simulated financial data. These are key risk metrics used in **quantitative finance** to assess the potential losses in a portfolio under adverse market conditions.

---

## 🔍 Objective

- Calculate the **VaR** of a financial asset or portfolio at different confidence levels.
- Estimate **CVaR (Expected Shortfall)** to understand the average loss beyond the VaR threshold.
- Visualize risk measures and loss distributions for better financial risk management.

---

## 🧪 Methodology

- **Data Source**: Use historical price data or generate returns via simulation (e.g., geometric Brownian motion).
- **Log Returns**: Compute daily log returns from price series.
- **VaR Calculation**: Historical Method
- **CVaR Calculation**: Average of losses exceeding VaR (tail losses)

---

## 🛠️ Technologies Used

- `NumPy` – Matrix operations and simulations
- `SciPy` – For solving linear systems
- `Matplotlib` – For visualizing default probabilities and trajectories
- Jupyter Notebook – For interactive documentation
- `yfinance` or simulated data – For historical asset prices  
---

## 📊 Sample Output

The notebook produces a histogram showing the distribution of the Time series plots of cumulative returns with VaR and CVaR thresholds
Run the notebook to generate the plot and explore the credit risk dynamics.

---

## 🧠 Inspiration 

This project is part of a broader effort to **bridge techniques from stochastic enzyme kinetics and chemical master equations** with real-world problems in **finance and risk modeling**.

---

## 👨‍🔬 Author

Subham Pal  
PhD – Stochastic Kinetics | Financial Modeling | Python

---
**Tags**: Credit Risk · Markov Chain · First Passage Time · Quant Finance · Stochastic Modeling · Python
