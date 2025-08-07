# 📊 Fintech Risk Modeling Projects

This repository contains a collection of **quantitative finance simulations and models** focused on risk assessment, market behavior, and credit analysis. The tools used are rooted in **probability theory**, **stochastic modeling**, and **machine learning**, and are implemented using Python in Jupyter Notebooks.

---

## 🔗 Projects Overview

### 1. Credit Default Modeling using Markov Chains

- **Objective**: Estimate time to credit default using first passage time in a discrete Markov chain.
- **Approach**: Transition matrix analysis and simulation of rating migration to default.
- **Outputs**: Default probabilities over time, expected default horizon.
- **Notebook**: `CreditDefault_FirstPassage.ipynb`

---

### 2. Trade Arrival Simulation using Hawkes Process

- **Objective**: Model self-exciting trade arrival times (event clustering).
- **Algorithm**: Ogata's thinning method to simulate a Hawkes process.
- **Outputs**: Simulated timestamps, event plot showing trade bursts.
- **Notebook**: `HighFreqTrading_Hawkes.ipynb`

---

### 3. Market Regime Detection using Hidden Markov Models (HMM)

- **Objective**: Identify hidden market states (e.g., bull, bear, volatile) from price returns.
- **Data**: NIFTY 50 historical prices via `yfinance`.
- **Model**: Gaussian HMM (`hmmlearn`) with 3 latent regimes.
- **Outputs**: Regime-labeled scatter plot, transition matrix, return stats.
- **Notebook**: `Market_Regime_HMM.ipynb`

---

### 4. Value at Risk (VaR) and Conditional Value at Risk (CVaR)

- **Objective**: Quantify downside risk of an asset or portfolio.
- **Methods**: Historical and parametric (Gaussian) approaches.
- **Outputs**: Numerical VaR/CVaR estimates, return histograms, and confidence intervals.
- **Notebook**: `MonteCarlo_VaR_CVaR.ipynb`

---

## Technologies Used

- Python (3.8+)
- `NumPy`, `Pandas` – Data handling and numerical computation
- `Matplotlib`, `Seaborn` – Visualization
- `yfinance` – Market data (NIFTY 50)
- `hmmlearn` – Hidden Markov Model
- Jupyter Notebook – Interactive environment

---

