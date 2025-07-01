# Lattice QCD Two-Point Function Resampling Study

This repository contains Python code and Jupyter notebooks associated with the paper: **"Statistical Resampling Techniques for Uncertainty Quantification in Lattice QCD Two-Point Function Analysis"**

---

## Description

This project simulates synthetic two-point correlation functions (inspired by lattice QCD pion correlators), adds short-range AR(1) correlated noise, and analyzes the uncertainty using three common resampling techniques:

- Jackknife
- Bootstrap (with variable sample sizes)
- Blocking resampling (with variable block sizes)

Plots, error ratio comparisons, and insights into the behavior of resampling techniques under correlation are included.

---

## Folder Structure

- `main_analysis.ipynb`: Main Jupyter notebook (generate data, apply resampling, plot results)
- `plots/`: Saved plots

---
