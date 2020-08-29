---
title: "Minimax Optimal Online Stochastic Learning for Sequences of Convex Functions under Sub-Gradient Observation Failures"
collection: publications
permalink: /publications/MOOSL
---
H. Gokcesu, <b>F. Ilhan</b>, O. Karaahmetoglu and S. S. Kozat, "Minimax Optimal Online Stochastic Learning for Sequences of Convex Functions under Sub-Gradient Observation Failures", <i>IEEE Transactions on Signal Processing</i>, 2020.

<i>(draft available with permission of supervisor)</i>


## Abstract
We study online convex optimization under stochastic sub-gradient observation faults, where we introduce adaptive algorithms with minimax optimal regret guarantees.
We specifically study scenarios where our sub-gradient observations can be noisy or even completely missing in a stochastic manner.
To this end, we propose algorithms based on
sub-gradient descent method, which achieve tight minimax optimal regret bounds. When necessary, these algorithms utilize 
properties of the underlying stochastic settings to optimize their learning rates (step sizes). These optimizations are the main factor in providing the minimax optimal performance guarantees, especially when observations are stochastically missing. However, in real world scenarios,
these properties of the underlying stochastic settings may not be revealed to the optimizer. 
For such a scenario, we propose a blind algorithm 
that estimates these properties empirically in a generally applicable manner. Through extensive experiments, we show that this empirical approach is a natural combination of regular stochastic gradient descent and the minimax optimal algorithms (which work best for randomized and adversarial function sequences, respectively).