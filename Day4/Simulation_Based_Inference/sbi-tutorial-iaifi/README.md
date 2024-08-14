# SBI Lecture/Tutorial

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/jessimic/sbi-tutorial-iaifi/blob/main/Tutorial1_Basic_NRE_NPE.ipynb)
[![License: MIT](https://img.shields.io/badge/License-MIT-red.svg)](https://opensource.org/licenses/MIT)

A gentle introduction to some neural simulation-based inference methods. Jupyter notebook to go along with IAIFI Summer School Lecture on Simulation-Based Inference and Uncertainty Quantification

## Simulation-based inference

Simulation-based inference (SBI) is a powerful class of methods for performing inference in settings where the likelihood is computationally intractable, but simulations can be done via forward modeling. 

In this lecture we will
- Introduce implicit likelihood and how to leverage it to perform inference;
- Build up two common modern _neural_ SBI techniques: neural likelihood-ratio estimation (NRE) and neural posterior estimation (NPE);
- Apply SBI techniques on multiple simulations/datasets
- Introduce the concept of statistical coverage testing and calibration.

As examples, we will look at a simple Gaussian-signal-on-power-law-background ("bump hunt"), where the likelihood is tractable, and a more complicated example of inferring a distribution of point sources, where the likelihood is computationally intractable.
