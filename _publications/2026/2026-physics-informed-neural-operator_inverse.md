---
layout: publication
title: "Physics-Informed Neural Operator for Electromagnetic Inverse Scattering Problems"
cover: /assets/images/covers/PINO_inverse.png
date: 2026-01-01
selected: true
authors:
  - Qi-Chang Dong
  - Zi-Xuan Su
  - Qing Huo Liu
  - Wen Chen
  -  Zhizhang (David) Chen
pub: "arxiv"
abstract: "This paper proposes a physics-informed neural operator (PINO) framework for solving inverse scattering problems, enabling rapid and accurate reconstructions under diverse measurement conditions. In the proposed approach, the dielectric property is represented as a learnable tensor, while a neural operator is employed to predict the induced current distribution. A hybrid loss function, consisting of the state loss, data loss and total-variation (TV) regularization, is constructed to establish a fully differentiable formulation for a joint optimization of network parameters and dielectric property. To demonstrate the framework's generality and flexibility, PINO is implemented using three representative neural operators, i.e., the Fourier Neural Operator (FNO), the enhanced Fourier Neural Operator (U-FNO) and the Factorized Fourier Neural Operator (F-FNO). Compared with conventional approaches, the proposed framework offers a simpler formulation and universal modeling capability, making it readily applicable to various measurement scenarios, including multi-frequency and phaseless inversion. Numerical simulations demonstrate that the proposed PINO achieves high accuracy and robust reconstruction across samples with and without phase information, under single-frequency and multi-frequency settings in the presence of noise. The results demonstrate that PINO consistently outperforms conventional contrast-source inversion (CSI) methods and provides an efficient, unified solution to complex electromagnetic inverse-scattering problems."
links:
  DOI: https://doi.org/10.48550/arXiv.2603.25404
---
