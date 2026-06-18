# JPMorgan Chase — Quantitative Research (Virtual Experience)

End-to-end solutions to the JPMorgan Chase & Co. Quantitative Research job simulation (Forage), spanning commodity derivatives pricing and credit risk modeling. Built in Python with pandas, NumPy, scikit-learn, and matplotlib.

## Overview

Four tasks covering two real quant-desk workflows — commodities pricing (Tasks 1–2) and credit risk (Tasks 3–4).

| Task | Notebook | What it does | Key techniques |
|------|----------|--------------|----------------|
| 1 | `task1_gas_price_model.ipynb` | Estimates natural gas prices on any date, including a 12-month forecast | Time-series decomposition, linear regression, sinusoidal seasonality |
| 2 | `task2_storage_contract_pricing.ipynb` | Prices a gas storage contract from its cash flows | Cash-flow valuation, cost of carry, path-dependent state simulation |
| 3 | `task3_credit_risk_expected_loss.ipynb` | Predicts probability of default and expected loss on a loan | Logistic regression, train/test split, ROC-AUC, PD × LGD × EAD |
| 4 | `task4_fico_bucketing.ipynb` | Maps FICO scores into optimal risk buckets for a categorical model | Discretization, maximum-likelihood objective, dynamic programming |

## Highlights

- Hand-built a **dynamic program** that finds globally optimal FICO bucket boundaries by maximizing binomial log-likelihood.
- Compared logistic regression against decision-tree and random-forest models on ROC-AUC, with feature-importance analysis.
- Modeled commodity seasonality as a one-term Fourier series fitted via least squares, handling both interpolation and 12-month extrapolation.

## Tech stack

Python · pandas · NumPy · scikit-learn · matplotlib

## Notes

Datasets are those provided by the Forage simulation. Each notebook runs top-to-bottom from a clean kernel.

---

**Satvik Agarwal** — B.E. Mathematics & Computing, BITS Pilani (Dubai) · [LinkedIn](https://www.linkedin.com/in/satvik1007)