# Ridge Regularized Local Linear Estimator for Functional Conditional Density

This repository contains the complete R code for the simulation study presented in the paper:

**"Local Linear Conditional Density Estimation for Quasi-Associated Functional Data: Theory, Numerical Instability, and Practical Remedies"**
*Imed Bouaker*, Babylonian Journal of Mathematics, 2026.

## Overview

The code implements:
- Nadaraya–Watson (NW) kernel estimator
- Standard Local Linear (LL) estimator (which fails numerically)
- Ridge‑regularised Local Linear (ridge LL) estimator that restores numerical stability

## Requirements

- R (version 3.6 or higher)
- No additional packages required (uses only base R)

## Files

- `simulation_LL_NW_ridge.R` – main simulation script
- `density_plot.png` – example density plot
- `boxplot_ise.png` – boxplot of ISE results

## Usage

Run the script in R:

```r
source("simulation_LL_NW_ridge.R")
