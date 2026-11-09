# Project 16: Robustness of Responsibility Displacement

**Target journal:** Journal of Business Ethics

This repository contains the proposal, an executed exploratory analysis notebook, and its aggregate figures and tables. The saved outputs are exploratory and should not be represented as publication-ready results. The notebook source has been sanitized: no OSF access token is included.

## Data access

The notebook expects `data/raw/study1.sav` and `data/raw/study2.sav`. These raw files are not included. The article identifies an author OSF project, but unrestricted download and reuse terms have not been confirmed. Obtain the files from the authors/OSF and verify the terms before reproducing or redistributing data.

## Run

Install `pyreadstat`, `numpy`, `pandas`, `scipy`, `statsmodels`, and `matplotlib`; place the two SPSS files in `data/raw/`; then run the notebook from top to bottom.

## Interpretation and limitations

Some negative-binomial bootstrap resamples emitted optimizer convergence warnings. RQ4 intervals are exploratory and require a convergence audit. The supplied SPSS files represent final analytic samples, so screening sensitivity for excluded participants cannot be assessed. Indirect-path estimates are assumption-dependent and are not causal mediation effects.
