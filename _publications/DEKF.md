---
title: "Stability of the Decoupled Extended Kalman Filter in LSTM-Based Online Learning"
collection: publications
permalink: /publications/DEKF
---
N. M. Vural, <b>F. Ilhan</b> and S. S. Kozat, "Stability of the Decoupled Extended Kalman Filter in LSTM-Based Online Learning", <i>Digital Signal Processing</i>, 2020.

[[arXiv]](https://arxiv.org/abs/1911.12258)


## Abstract
We investigate the convergence and stability properties of the decoupled extended Kalman filter learning algorithm 
(DEKF) within the long-short term memory network (LSTM) based online learning framework. For this purpose, we model DEKF 
as a perturbed extended Kalman filter and derive sufficient conditions for its stability during LSTM training. 
We show that if the perturbations -- introduced due to decoupling -- stay bounded, DEKF learns LSTM parameters 
with similar convergence and stability properties of the global extended Kalman filter learning algorithm. 
We verify our results with several numerical simulations and compare DEKF with other LSTM training methods. 
In our simulations, we also observe that the well-known hyper-parameter selection approaches used for DEKF in the 
literature satisfy our conditions.