# Threshold Models in Time Series Analysis: Advancements and Applications

A seminar paper exploring threshold models as a class of nonlinear time series models,
submitted to the Faculty of Statistics at Technische Universität Dortmund.

**Author:** Madhavi Panchangum  
**Course:** Forecasting with Time Series Analysis  
**Professor:** Dr. Matei Demetrescu  
**Submitted:** January 12, 2025

---

## Overview

Classical linear time series models often fail to capture regime shifts, nonlinearities,
and state-dependent dynamics common in real-world data. This paper introduces and analyzes
**threshold models** — a flexible class of piecewise linear (or time-varying parameter)
models that partition the state space into distinct regimes governed by a threshold variable.

---

## Topics Covered

- **Threshold Autoregressive (TAR) Models** — regime-dependent AR dynamics with
  ergodicity and stationarity conditions
- **Self-Exciting TAR (SETAR)** — lagged values of the series itself drive regime switching
- **Exponential Autoregressive (EAR)** — TAR subclass designed for exponential marginal
  distributions
- **Threshold GARCH (TGARCH)** — asymmetric volatility modeling capturing the leverage
  effect
- **Threshold Volatility Models** — regime-dependent ARCH/GARCH extensions
- **Recent Advances** — LASSO-based estimation, Smooth Transition Regression (STR),
  Threshold VAR (TVAR), and Bayesian approaches

---

## Statistical Analysis

Three empirical analyses are included:

1. **TAR vs. Linear AR Simulation** — comparison of distributional properties and ergodicity
   across 1,000 simulated time points
2. **AirPassengers Dataset** — stationarity (ADF test) and linearity checks
   (RESET + Ljung-Box tests) on log-transformed monthly airline passenger data
3. **Tesla Log Returns (TGARCH)** — volatility modeling of Tesla stock returns with
   diagnostic validation

---

## Key Results

| Test | Statistic | p-value | Conclusion |
|---|---|---|---|
| ADF (AirPassengers) | −1.7176 | 0.4236 | Non-stationary |
| RESET (Linearity) | 0.2265 | 0.7976 | No nonlinearity |
| Ljung-Box (Residuals) | 6.7837 | 0.5613 | No autocorrelation |

---

## Repository Structure
