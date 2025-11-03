---
title: Annealed SMC for Bayesian Logistic Regression
date: 2025-10-14
image:
  preview_only: true  # This hides the image from the detail page
links:
  - type: site
    url: https://github.com/ravleenbajaj/smc-breastcancer
tags:
  - Julia
  - Distributions

---

A Julia implementation of Annealed Sequential Monte Carlo (SMC) for Bayesian inference on logistic regression, applied to the Wisconsin Breast Cancer dataset.
This project demonstrates how to use Sequential Monte Carlo with annealing to sample from posterior distributions of logistic regression coefficients. The algorithm gradually transitions from the prior distribution (β=0) to the posterior distribution (β=1), making it particularly effective for complex, multimodal posteriors.

<!--more-->
