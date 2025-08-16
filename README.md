# Forecasting with GSTAR and GSTAR-Poisson  

This repository contains a collection of code implementations for **forecasting count data** using the **Generalized Space Time Autoregressive (GSTAR)** and **GSTAR-Poisson** methods.  

These methods are designed to handle **spatio-temporal data**, especially count data commonly found in health, social, and economic fields.  

---

## Repository Structure  

- **`R/`** → R (R-Studio) scripts for parameter estimation, model validation, and visualization.  
- **`MATLAB/`** → MATLAB codes for numerical simulation and alternative GSTAR implementations.  
- **`SAS/`** → SAS Studio codes for additional analysis, significance testing, and large data handling.  
- **`Data/`** → (optional) example datasets for experiments.  
- **`Docs/`** → technical documentation and theoretical explanation of GSTAR & GSTAR-Poisson.  

---

## Methods  

### 1. GSTAR (Generalized Space Time Autoregressive)  
- Handles multivariate time series data with spatial influence.  
- Combines location information (spatial weighting matrix) with temporal dynamics.  

### 2. GSTAR-Poisson  
- A GSTAR variant for count data.  
- Uses the Poisson distribution to capture the non-negative and discrete nature of the data.  

---

## Features  

- GSTAR and GSTAR-Poisson implementations across **R, MATLAB, and SAS**.  
- Numerical simulations for model performance evaluation.  
- Forecasting comparison across different software.  
- Visualization of forecasting results (time series and spatial plots).  

---

## Requirements  

- **R-Studio** (≥ 4.0.0) 
- **MATLAB** (≥ R2019) with Statistics & Machine Learning Toolbox  
- **SAS Studio** (≥ 3.8)  
