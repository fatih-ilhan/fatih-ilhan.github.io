---
title: "Modeling of Spatio-Temporal Hawkes Processes with Randomized Kernels"
collection: publications
permalink: /publications/STHP
---
**F. Ilhan** and S. S. Kozat, "Modeling of Spatio-Temporal Hawkes Processes with Randomized Kernels", <i>IEEE Transactions on Signal Processing</i>, 2020.

[[PDF]](https://ieeexplore.ieee.org/document/9177186) [[code]](https://github.com/fatih-ilhan/sthawkes)


## Abstract
<img align="right" src="https://fatih-ilhan.github.io/images/profile.png" style="width: 450px;">
We investigate spatio-temporal event analysis using point processes. 
Inferring the dynamics of event sequences spatiotemporally has many 
practical applications including crime prediction, social media analysis, and traffic forecasting. 
In particular, we focus on spatio-temporal Hawkes processes that are commonly used 
due to their capability to capture excitations between event occurrences. 
We introduce a novel inference framework based on randomized transformations 
and gradient descent to learn the process. We replace the spatial kernel calculations by randomized 
Fourier feature-based transformations. The introduced randomization by this representation 
provides flexibility while modeling the spatial excitation between events. 
Moreover, the system described by the process is expressed within closed-form 
in terms of scalable matrix operations. During the optimization, we use maximum 
likelihood estimation approach and gradient descent while properly handling positivity 
and orthonormality constraints. The experiment results show the improvements 
achieved by the introduced method in terms of fitting capability in synthetic and real datasets 
with respect to the conventional inference methods in the spatio-temporal Hawkes process literature. 
We also analyze the triggering interactions between event types and how their dynamics change in 
space and time through the interpretation of learned parameters.

