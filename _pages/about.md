---
permalink: /
title: "About Me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I am Hongzhi Zang, a senior student from Yao Class, Tsinghua University. Nice to meet you!

# Publications

## Online Guidance Graph Optimization for Lifelong Multi-Agent Path Finding

**Hongzhi Zang***, Yulun Zhang*, He Jiang, Zhe Chen, Daniel Harabor, Peter J. Stuckey, Jiaoyang Li

[[arxiv](https://arxiv.org/abs/2411.16506)]

We study the problem of optimizing a guidance policy capable of dynamically guiding the agents for lifelong Multi-Agent Path Finding based on real-time traffic patterns. Multi-Agent Path Finding (MAPF) focuses on moving multiple agents from their starts to goals without collisions. Its lifelong variant, LMAPF, continuously assigns new goals to agents. In this work, we focus on improving the solution quality of PIBT, a state-of-the-art rule-based LMAPF algorithm, by optimizing a policy to generate adaptive guidance. We design two pipelines to incorporate guidance in PIBT in two different ways. We demonstrate the superiority of the optimized policy over both static guidance and human-designed policies. Additionally, we explore scenarios where task distribution changes over time, a challenging yet common situation in real-world applications that is rarely explored in the literature.

## Multi-UAV Behavior-based Formation with Static and Dynamic Obstacles Avoidance via Reinforcement Learning 

Yuqing Xie*, Chao Yu*, **Hongzhi Zang***, Feng Gao, Wenhao Tang, Jingyi Huang, Jiayu Chen, Botian Xu, Yi Wu, Yu Wang

[[project website](https://sites.google.com/view/uav-formation-with-avoidance)]

Formation control of multiple Unmanned Aerial Vehicles (UAVs) is vital for practical applications.  This paper tackles the task of behavior-based UAV formation while avoiding static and dynamic obstacles during directed flight. We present a two-stage reinforcement learning (RL) training pipeline to tackle the challenge of multi-objective optimization, large exploration spaces, and the sim-to-real gap. The first stage searches in a simplified scenario for a linear utility function that balances all task objectives simultaneously, whereas the second stage applies the utility function in complex scenarios, utilizing curriculum learning to navigate large exploration spaces. Additionally, we apply an attention-based observation encoder to enhance formation maintenance and manage varying obstacle quantity. Experiments in simulation and real world demonstrate that our method outperforms planning-based and RL-based baselines regarding collision-free rate and formation maintenance in scenarios with static, dynamic, and mixed obstacles.