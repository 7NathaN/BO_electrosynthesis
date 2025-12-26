# Bayesian Optimization with Gaussian Processes for Reaction Optimization

This repository provides a Bayesian Optimization (BO) workflow based on Gaussian Process (GP) regression for optimizing chemical reaction outcomes from experimental data. The approach is designed to efficiently explore a mixed parameter space (continuous and discrete) while balancing exploration vs. exploitation, making it well suited for data-limited experimental settings.
The core implementation is provided as a Jupyter notebook that demonstrates data preprocessing, feature engineering, GP modeling, and Bayesian Optimization using real reaction data.

## Features

Gaussian Process regression with customizable kernels
Bayesian Optimization using acquisition functions
Support for numerical and encoded categorical variables
Feature engineering for chemically meaningful parameters (e.g. computed properties)
Partial dependence analysis for model interpretability
Designed for small-data experimental optimization

## Requirements

The notebook relies on standard scientific Python libraries:
Python ≥ 3.8
NumPy
Pandas
SciPy
scikit-learn
bayesian-optimization

## License

This project is provided for research and educational purposes under a MIT license
