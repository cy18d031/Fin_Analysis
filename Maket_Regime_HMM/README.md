# 📊 Market Regime Detection using Hidden Markov Models (HMM)

This project applies a **Hidden Markov Model (HMM)** to detect **market regimes** in the **NIFTY 50 index** based on historical price data. Using `hmmlearn`, the model identifies latent market states (e.g., bull, bear, volatile) based on daily log returns.

---

## 🔍 Objective

- Detect **market regimes** from price behavior using an unsupervised machine learning approach.
- Estimate characteristics (mean return, volatility) of each hidden regime.
- Visualize how market states evolve over time and their transitions.

---

## 🧪 Methodology

- **Data Source**: NIFTY 50 historical data downloaded using `yfinance`
- **Preprocessing**: Compute daily **log returns**
- **Modeling**: Fit a **Gaussian HMM** with 3 hidden states to the return series
---

## 🛠️ Technologies Used

- `Python` – Core language
- `yfinance` – Downloading historical price data
- `NumPy`, `Pandas` – Data manipulation and return calculation
- `hmmlearn` – Fitting Hidden Markov Model
- `Matplotlib` – Plotting market regimes

---

## 📊 Sample Output

The notebook produces a color-coded scatter plot of **NIFTY 50 prices** by regime helping in understanding which periods correspond to which type of market behavior.
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
