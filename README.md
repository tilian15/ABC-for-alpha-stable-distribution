# ABC for Alpha-Stable Distributions

This repository contains code and analysis for a project exploring **Approximate Bayesian Computation (ABC)** techniques applied to **alpha-stable distributions**, which are well known for their heavy tails and intractable likelihood functions.

---

## 🧠 Project Overview

The objectives of this project are to:

- Simulate data from alpha-stable distributions using the **Chambers-Mallows-Stuck (CMS)** algorithm
- Estimate expectations using **Monte Carlo (MC)** and **Randomized Quasi-Monte Carlo (RQMC)**
- Approximate the posterior distribution of parameters using three ABC algorithms:
  - ABC Rejection
  - MCMC-ABC (Metropolis-Hastings)
  - SMC-ABC (Sequential Monte Carlo)

---

## 📚 References

This project is inspired by and builds upon the methods described in the following research papers:

1. **Sisson, S. A., Fan, Y., & Beaumont, M. A. (2011).**  
   “Overview of ABC.”  
   *Computational Statistics & Data Analysis*, 55(1), 1–3.  
   [https://www.sciencedirect.com/science/article/abs/pii/S0167947310003786](https://www.sciencedirect.com/science/article/abs/pii/S0167947310003786)

2. **Chambers, J. M., Mallows, C. L., & Stuck, B. W. (1976).**  
   “A Method for Simulating Stable Random Variables.”  
   *Journal of the American Statistical Association*, 71(354), 340–344.  
   [https://www.jstor.org/stable/2285312](https://www.jstor.org/stable/2285312)

---

## 📂 Project Structure

- `Montecarlo alpha-stable x ABC.ipynb` : Main Jupyter notebook containing all simulations and ABC implementations


---

## ⚙️ Dependencies

This project uses:

- Python 3.8+
- NumPy
- SciPy
- Matplotlib

To install the required packages:

```bash
pip install numpy scipy matplotlib
