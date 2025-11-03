---
title: Annealed SMC for Bayesian Logistic Regression
date: 2023-10-26
links:
  - type: site
    url: https://github.com/pytorch/pytorch
tags:
  - Julia
  - Distributions

---

A Julia implementation of Annealed Sequential Monte Carlo (SMC) for Bayesian inference on logistic regression, applied to the Wisconsin Breast Cancer dataset.
This project demonstrates how to use Sequential Monte Carlo with annealing to sample from posterior distributions of logistic regression coefficients. The algorithm gradually transitions from the prior distribution (β=0) to the posterior distribution (β=1), making it particularly effective for complex, multimodal posteriors.

<!--more-->
