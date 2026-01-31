# Binomial Option Pricing Model & Market Calibration

![Python](https://img.shields.io/badge/Python-3.8%2B-blue)
![Status](https://img.shields.io/badge/Status-Completed-success)

## 📄 Abstract
This project implements a vectorized Binomial Option Pricing Model in Python to evaluate European and American options. The model is validated against the Black-Scholes analytical benchmark and calibrated to real-world Amazon (AMZN) market data.

## 🚀 Features
- **Vectorized Implementation:** High-performance Numpy implementation of the CRR Binomial Tree.
- **American Options:** Handles early exercise boundary conditions.
- **Market Calibration:** Numerical root-finding (SLSQP) to extract Implied Volatility from market prices.
- **Convergence Analysis:** Visualizes the asymptotic convergence to Black-Scholes as $N \to \infty$.

## 🛠️ Technologies
- **Python:** NumPy, SciPy (Optimization/Stats), Matplotlib
- **LaTeX:** For the mathematical documentation and final report.

## 📊 Results Snapshot
* **Amazon (AMZN) Analysis:** found a significant volatility risk premium, with implied volatility (~41%) exceeding historical volatility.
* **Early Exercise:** Confirmed that American Put premiums are driven by the optimal stopping boundary in deep ITM conditions.

## 📂 Project Structure
- `code/`: Contains the Jupyter Notebook (`.ipynb`) with the pricing engine.
- `report/`: Contains the LaTeX source code and the final PDF report.

## 🔗 How to Run
[Open the notebook in Google Colab](https://colab.research.google.com/drive/1D-bcokEP3_5GjJWSTjUAssWmqsEGSCXe?usp=sharing)
