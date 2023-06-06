---
title: Deep Off-Policy Iterative Learning Control
openreview: Bi0E3lbvnU
abstract: Reinforcement learning has emerged as a powerful paradigm to learn control
  policies while making few assumptions about the environment. However, this lack
  of assumptions in popular RL algorithms also leads to sample inefficiency. Furthermore,
  we often have access to a simulator that can provide approximate gradients for the
  rewards and dynamics of the environment. Iterative learning control (ILC) approaches
  have been shown to be very efficient at learning policies by using approximate simulator
  gradients to speed up optimization. However, they lack the generality of reinforcement
  learning approaches. In this paper, we take inspiration from ILC and propose an
  update equation for the value-function gradients (computed using the dynamics Jacobians
  and reward gradient obtained from an approximate simulator) to speed up value-function
  and policy optimization. We add this update to an off-the-shelf off-policy reinforcement
  learning algorithm and demonstrate that using the value-gradient update leads to
  a significant improvement in sample efficiency (and sometimes better performance)
  both when learning from scratch in a new environment and while fine-tuning a pre-trained
  policy in a new environment. Moreover, we observe that policies pretrained in the
  simulator using the simulator jacobians obtain better zero-shot transfer performance
  and adapt much faster in a new environment.
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: gurumurthy23b
month: 0
tex_title: Deep Off-Policy Iterative Learning Control
firstpage: 639
lastpage: 652
page: 639-652
order: 639
cycles: false
bibtex_author: Gurumurthy, Swaminathan and Kolter, J Zico and Manchester, Zachary
author:
- given: Swaminathan
  family: Gurumurthy
- given: J Zico
  family: Kolter
- given: Zachary
  family: Manchester
date: 2023-06-06
address:
container-title: Proceedings of The 5th Annual Learning for Dynamics and Control Conference
volume: '211'
genre: inproceedings
issued:
  date-parts:
  - 2023
  - 6
  - 6
pdf: https://proceedings.mlr.press/v211/gurumurthy23b/gurumurthy23b.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
