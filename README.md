# DET-Weibull-R-Analysis
R implementation for the DUS Exponentially Tilted Weibull (DETW) distribution, including probability functions, parameter estimation using 15 non-Bayesian methods, simulation studies, and real-data applications in reliability and actuarial science.
# DETW Distribution: R Scripts & Statistical Analysis

This repository contains R scripts for computing, evaluating, and applying the **DUS Exponentially Tilted Weibull (DETW)** distribution. The codebase supports density/hazard visualization, non-Bayesian parameter estimation across 15 distinct methods, Monte Carlo simulations, and real-world empirical fitting (with Cox-Snell and Quantile residual diagnostics).

---

## 📁 Repository Structure

```text
├── plots of DETW functions.R      # Script to compute & visualize DETW PDF and Hazard functions
├── real data estimation.R        # Parameter estimation across 15 methods (MLE, MPSE, ADE, etc.)
├── real data analysis for DETW.R   # Goodness-of-fit tests, model benchmarking & residual analysis
└── simulation table for DETW.R   # Monte Carlo simulation framework & partial rank analysis
