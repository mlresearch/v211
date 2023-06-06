---
title: Practical Critic Gradient based Actor Critic for On-Policy Reinforcement Learning
openreview: ddl_4qQKFmY
abstract: On-policy reinforcement learning algorithms have been shown to be remarkably
  efficient at learning policies for continuous control robotics tasks. They are highly
  parallelizable and hence have benefited tremendously from the recent rise in GPU
  based parallel simulators. The most widely used on-policy reinforcement learning
  algorithm is proximal policy optimization (PPO) which was introduced in 2017 and
  was designed for a somewhat different setting with CPU based serial or less parallelizable
  simulators. However, suprisingly, it has maintained dominance even on tasks based
  on the highly parallelizable simulators of today. In this paper, we show that a
  different class of on-policy algorithms based on estimating the policy gradient
  using the critic-action gradients are better suited when using highly parallelizable
  simulators. The primary issues for these algorithms arise from the lack of diversity
  of the on-policy experiences used for the updates and the instabilities arising
  from the interaction between the biased critic gradients and the rapidly changing
  policy distribution. We address the former by simply increasing the number of parallel
  simulation runs (thanks to the GPU based simulators) along with an appropriate schedule
  on the policy entropy to ensure diversity of samples. We address the latter by adding
  a policy averaging step and value averaging step (as in off-policy methods). With
  these modifications, we observe that the critic gradient based on-policy method
  (CGAC) consistently achieves higher episode returns compared with existing baselines.
  Furthermore, in environments with high dimensional action space, CGAC also trains
  much faster (in wall-clock time) than the corresponding baselines.
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: gurumurthy23a
month: 0
tex_title: Practical Critic Gradient based Actor Critic for On-Policy Reinforcement
  Learning
firstpage: 625
lastpage: 638
page: 625-638
order: 625
cycles: false
bibtex_author: Gurumurthy, Swaminathan and Manchester, Zachary and Kolter, J Zico
author:
- given: Swaminathan
  family: Gurumurthy
- given: Zachary
  family: Manchester
- given: J Zico
  family: Kolter
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
pdf: https://proceedings.mlr.press/v211/gurumurthy23a/gurumurthy23a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
