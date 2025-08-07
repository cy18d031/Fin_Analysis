# Credit Default Modeling using First Passage Time in Markov Chains

This project models **credit default risk** using a **discrete-time Markov chain**, estimating **first passage time distributions** to default. It is inspired by techniques in **stochastic chemical kinetics**—particularly enzyme turnover and waiting time analysis—and applies those ideas to credit rating transitions in finance.

---

## 🔍 Objective

To estimate the **likelihood and timing of credit default** for a borrower (e.g., company or bond issuer) by:

- Modeling credit rating transitions as a Markov chain
- Calculating **first-passage time** (FPT) distributions to the absorbing "default" state
- Analyzing how credit quality evolves over time

---

## 🧪 Methodology

- **Markov Chain Construction**: Define states as credit ratings (AAA, AA, A, ..., Default) and assign transition probabilities between them.
- **Transition Matrix Analysis**: Use matrix powers to simulate multiple steps and calculate default probabilities over time.
- **First Passage Time Calculation**: Extract the distribution of times at which the process first hits the "default" state.
- **Visualization**: Plot default probabilities over time and highlight expected default horizons.

This mimics **enzyme state transitions** and **waiting time distributions** in chemical kinetics, applied here to financial credit risk.

---

## 🛠️ Technologies Used

- `NumPy` – Matrix operations and simulations
- `SciPy` – For solving linear systems
- `Matplotlib` – For visualizing default probabilities and trajectories
- Jupyter Notebook – For interactive documentation

---

## 📊 Sample Output

The notebook produces a histogram showing the distribution of default times based on first passage analysis.  
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

