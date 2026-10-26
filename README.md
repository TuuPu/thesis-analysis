# Thesis Analysis

R code for the master's thesis analysing how technology practitioners perceive
and differentiate the ethical principles of the ARISE Middleware framework.

## Contents
- `.ma_thesis.rmd` — full analysis: data preparation, MICE imputation,
  descriptive statistics, Wilcoxon tests, and hierarchical clustering.

## Data
The survey data is not included in this repository for confidentiality
reasons and is available on request.

## Reproducibility
Results were produced with R 4.6.1 and the `mice` package version 3.19.0.
Imputation uses a fixed seed, though different package versions may yield slightly
different imputed values.
