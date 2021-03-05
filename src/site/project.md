---
title: project
layout: layouts/base.njk
subtitle: 
---

## Computational Spatial Autonomy and SLAM

Autonomy is essential for successfully applying robots. While the autonomy can be performed in different forms, the spatial autonomy can be considered as the most basic one. Robots rely on the spatial autonomy to establish the spatial awareness, or its spatial relationship with the world, then they can perform various high-level tasks with the spatial awareness.

This problem is partially coined as the simultaneous localization and mapping (SLAM) in robotic research, which has been actively studied for the past few decades. To address this problem, I propose a super efficient SLAM algorithm based on online EM algorithm that only scales linearly with the number of landmarks.

I am also interested in integrating the principles of spatial autonomy across artificial agents and biological agents. The advance of neuroscience actually suggests various novel ideas for designing robots. For example, I apply the circular representation of grid cells in brains to solve the linearization inconsistency problem in traditional Kalman filter-based localization methods. As this initial work suggests, there are more opportunity for intergrating robotics and neuroscience, and I am working towards this direction to understand the spatial autonomy more thoroughly.

To summarize the ongoing reserach focus:
   - to build robots with full spatial autonomy
   - to improve the robot performance by integrating the computation principles from neuroscience 



## Reinforcement Learning and Navigation

Traditionally, navigation is often considered as a planning problem on top of the localization and the mapping in robotic research. However, the introduction of deep neural network revolutionizes this view. In particular, without any prior knowledge, a robot is able to navigate the environment (including mapping and localization) with the deep reinforcement learning algorithm. However, it often takes several rounds for the robot to learn such capability, which is not preferable in real scenarios. I am interested in combining the traditional robotic approaches and the deep reinforcement learning techniques to build an efficient navigation methods for autonomous robots.

To summarize the ongoing reserach focus:
   - to combine model-based approach and learning-based approach for a novel navigation algorithm


## Multirobot/multiagent Systems

By cooperation, multiple robots provide more flexibility and robustness over a single robot. However, the information management among robots is of great importance to the success of the multirobot system. First of all, the transmission of information should be optimized in terms of the performance as well as the power consumption. Furthermore, the fusion of information is not trivial in distributed system. Unlike centralized systems, if robots are operated in a distributed way, the fusion of information becomes challenging due to the information availability. I address these two aspects in multirobot system in my early publication.