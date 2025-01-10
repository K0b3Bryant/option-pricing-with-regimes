# **Markov-Modulated Heston Model**

A comprehensive project exploring the **Markov-Modulated Heston Model**, combining stochastic volatility dynamics with regime-switching behavior governed by a Markov process. This project includes analytical derivations, numerical simulations, parameter estimation from historical data, and a trading strategy built on the model's predictions.

## **Project Overview**

This repository provides a detailed implementation and analysis of the Markov-Modulated Heston Model. The key components include:

1. **Theoretical Foundation:**
   - Analytical derivations of the model.
   - Critical review of the Black-Scholes assumptions and motivation for incorporating a Markov process.
   - Explanation of how regime-switching improves modeling of real-world market behavior.

2. **Numerical Implementation:**
   - Simulation of the model using Monte Carlo techniques.
   - Calibration of parameters from historical financial data.

3. **Trading Strategy:**
   - Development of a trading strategy based on the insights from the model.
   - Backtesting the strategy on historical data.

---

## **Model Assumptions and Innovations**

### **Black-Scholes Assumptions:**
- Constant volatility.
- No transaction costs or market frictions.
- Risk-free interest rate is constant.
- Asset prices follow a geometric Brownian motion.
- The market is arbitrage-free.

### **Why Introduce a Markov Process?**
- **Regime-Switching:** Financial markets exhibit distinct regimes (e.g., bull, bear, volatile). A Markov process models these shifts effectively.
- **Dynamic Volatility:** Unlike Black-Scholes' constant volatility, the Markov-modulated Heston Model allows volatility parameters to change based on market states.
- **Improved Realism:** Adds flexibility for real-world phenomena like volatility clustering and sudden market changes.

---

## **Features**

- **Analytical Solutions:** 
  - Analytical exploration of the model's behavior under different assumptions.
  - Derivations for the extended PDE and transition matrix formulation.
  
- **Numerical Implementation:** 
  - Monte Carlo simulations for pricing derivatives.
  - Parameter calibration from historical data.

- **Trading Strategy:** 
  - A regime-aware strategy using insights from the model.
  - Evaluation through backtesting and performance metrics.
