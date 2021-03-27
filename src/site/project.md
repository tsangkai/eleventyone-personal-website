---
title: projects
subtitle: 
layout: layouts/base.njk
---

## computational spatial autonomy and SLAM

Robots have to establish the spatial awareness autonomously, and then they can perform various amazing tasks. Therefore, the spatial autonomy is crucial to all robotic applications. This problem is usally coined as the simultaneous localization and mapping (SLAM) in robotics, and has been actively studied for several decades. Most of the SLAM solutions rely on optimization-based approaches, which result in the offline nature. I take advantage of the intrisic hidden Markov model in SLAM problems, and design an online SLAM algorithm. As a result, the proposed algorithm is very efficient compared to the common approaches.


## artificial agents vs biological agents

I am interested in spatial autonomy principles underlying both artificial and biological agents. Even though I normally approach the robotic autonomy from an engineering perspective, the discovery in neuroscience may be also insightful for understanding and designing robots. For example, mammals track a 2D position with only circular representation. I expect to explore the connection among all autonomous agents.


## multiagent systems

By cooperation, multiple agents provide more flexibility and robustness over a single agent. However, the information management in a multiagetn system is essential but challenging. Following this concept, I stuty the cooperative localization in multirobot systems. Our algorithm is the first one that has separate communication step and observation step, which greatly improves the system resilience.


## consensus as barycenter of distributions

Barycenter is an elegant concept to denote the weighted average. By using the KL divergence as the distance measure, we can find the barycenter as the consensus of several probability distributions. The KL barycenter has several interesting properties; for example, the KL barycenter can be considered as an conservative fusion result. I study the KL barycenter of von Mises-Fisher distributions, which are extensively used in directional data. I show that the KL barycenter is nothing but vector addition in the Euclidean space.
