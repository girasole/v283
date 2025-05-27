---
title: Fast and Reliable $N - k$ Contingency Screening with Input-Convex Neural Networks
abstract: Power system operators must ensure that dispatch decisions remain feasible
  in case of grid outages or contingencies to prevent cascading failures and ensure
  reliable operation. However, checking the feasibility of all $N - k$ contingencies
  – every possible simultaneous failure of $k$ grid components – is computationally
  intractable even for small $k$, requiring system operators to resort to heuristic
  screening methods. Because of the increase in uncertainty and changes in system
  behaviors, heuristic lists might not include all relevant contingencies, generating
  false negatives in which unsafe scenarios are misclassified as safe. In this work,
  we propose to use input-convex neural networks (ICNNs) for contingency screening.
  We show that ICNN reliability can be determined by solving a convex optimization
  problem, and by scaling model weights using this problem as a differentiable optimization
  layer during training, we can learn an ICNN classifier that is both data-driven
  and has provably guaranteed reliability. That is, our method can ensure a zero false
  negative rate. We empirically validate this methodology in a case study on the IEEE
  39-bus test network, observing that it yields substantial (10-20x) speedups while
  having excellent classification accuracy.
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: christianson25a
month: 0
tex_title: Fast and Reliable $N - k$ Contingency Screening with Input-Convex Neural
  Networks
firstpage: 527
lastpage: 539
page: 527-539
order: 527
cycles: false
bibtex_author: Christianson, Nicolas and Cui, Wenqi and Low, Steven and Yang, Weiwei
  and Zhang, Baosen
author:
- given: Nicolas
  family: Christianson
- given: Wenqi
  family: Cui
- given: Steven
  family: Low
- given: Weiwei
  family: Yang
- given: Baosen
  family: Zhang
date: 2025-05-22
address:
container-title: Proceedings of the 7th Annual Learning for Dynamics \& Control Conference
volume: '283'
genre: inproceedings
issued:
  date-parts:
  - 2025
  - 5
  - 22
pdf: https://raw.githubusercontent.com/mlresearch/v283/main/assets/christianson25a/christianson25a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
