---
title: "Accelerating Min-Max Optimization with Application to Minimal Bounding Sphere"
collection: publications
permalink: /publications/MBS
---
H. Gokcesu, <b>F. Ilhan</b>, K. Gokcesu and S. S. Kozat, "Accelerating Min-Max Optimization with Application to Minimal Bounding Sphere", <i>IEEE Transactions on Signal Processing</i>, 2020.

<i>(draft available with permission of supervisor)</i>

## Abstract

We study the min-max optimization problem where each function contributing to the max operation is strongly convex
and smooth with bounded gradient in the search domain. By smoothing the max operator, we show the
ability to achieve an arbitrarily small positive optimality gap of $\delta$ in $\tilde{O}(\frac{1}{\sqrt{\delta}})$ 
computational complexity (up to logarithmic factors) as opposed to the state-of-the-art strong-convexity computational 
requirement of $O(\frac{1}{\delta})$. We
apply this important result to the well-known minimal bounding sphere problem and demonstrate that we can achieve
a $(1+\epsilon)$-approximation of the minimal bounding sphere, i.e. identify an hypersphere enclosing a total of $n$ 
given
points in the $d$ dimensional unbounded space $\mathbb{R}^d$ with a radius at most $(1+\epsilon)$ times the actual minimal bounding
sphere radius for an arbitrarily small positive $\epsilon$, in $\tilde{O}(\frac{nd}{\sqrt{\epsilon}})$ 
computational time as opposed to the state-of-the-art
approach of core-set methodology, which needs $O(\frac{nd}{\epsilon})$ computational time.