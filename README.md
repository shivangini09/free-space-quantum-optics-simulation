# free-space-quantum-optics-simulation
# 🌌 Distribution of Squeezed Light Through Atmospheric Channels

This project focuses on the **numerical simulation and statistical modeling** of quantum light transmission through atmospheric turbulence, based on the paper:

> *“Distribution of Squeezed States through an Atmospheric Channel”* (Phys. Rev. Lett. 113, 060502)



## 📌 Project Overview

The goal of this project is to:

- Reproduce key results from the reference paper  
- Simulate atmospheric channel effects on optical beams  
- Analyze the **statistical behavior of transmittance**  
- Compare different **Probability Distribution Models (PDTs)**  
- Evaluate model performance using the **Kolmogorov–Smirnov (KS) test**


---

## 🔬 1. Reproduction of Paper Results

**File:**  
`reproduction/Distributionofsqueezedlightreproduction.ipynb`

This notebook reproduces key figures from the paper:

- Transmission-dependent squeezing behavior  
- Verification of theoretical scaling (linear vs quadratic)  
- Wigner function visualization of reconstructed quantum states  

---

## 📊 2. Statistical Modeling of Transmittance

The `pdt_ks_comparison/` folder contains simulations comparing:

### Models:
- **Log-normal distribution**
- **Beta distribution**

### Against:
- Numerically simulated transmittance data

---

## Turbulence Conditions Covered

Each condition is analyzed separately:

### Weak Turbulence
- Focused beam  
- Collimated beam  

### Moderate Turbulence
- Focused beam  
- Collimated beam  

---

## ⚙️ Methodology

### Numerical Simulation
- Monte Carlo simulation of atmospheric turbulence  
- Beam propagation through random phase distortions  
- Aperture-based power collection  
- Computation of transmittance:
  


---

### Statistical Analysis
- Build Probability Distribution of Transmittance (PDT)  
- Fit:
  - Log-normal model  
  - Beta model  

---

### Model Evaluation
- Kolmogorov–Smirnov (KS) test used to compare:
  
  - Empirical distribution  
  - Theoretical models  

- Metrics:
  - KS statistic  
  - p-value  

---

## Key Observations

- **Log-normal model**
  - Works well in weak turbulence  
  - Fails in moderate turbulence due to strong fluctuations  

- **Beta distribution**
  - Provides better fit across all regimes  
  - Captures bounded and skewed nature of transmittance  

- **Moderate turbulence**
  - Leads to sparse and heavy-tailed distributions  
  - Strong impact of beam wandering and aperture clipping  



## Key Concepts Used

- Gaussian quantum states  
- Squeezing and anti-squeezing  
- Atmospheric turbulence modeling  
- Monte Carlo simulation  
- Probability distribution fitting  
- KS statistical testing  





