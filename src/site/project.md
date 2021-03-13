---
title: projects
layout: layouts/base.njk
subtitle: 
---

<div class="image-cropper">
    <img src="/images/project/maze.png" alt="avatar" class="highlight-pic">
</div>

## computational spatial autonomy and SLAM

Robots rely on the spatial autonomy to establish the spatial awareness, and then they can perform various high-level tasks with the spatial awareness. This problem is partially coined as the simultaneous localization and mapping (SLAM) in robotics, and has been actively studied for several decades. To address this problem, I propose a super efficient SLAM algorithm based on block online EM (BOEM) algorithm to improve the SLAM efficiency.



<div class="image-cropper">
    <img src="/images/project/bird.png" alt="avatar" class="highlight-pic">
</div>

## robots vs animals

The principles of spatial autonomy must be applicable for both artificial and biological agents. Therefore, the discovery in neuroscience may be insightful for understanding and designing robots. For example, I apply the circular representation of grid cells in brains to avoid the linearization inconsistency problem in traditional Kalman filter-based methods. As this initial work suggests, there are more opportunity for intergrating robotics and neuroscience, and I am working towards this direction to understand the spatial autonomy more thoroughly.



<div class="image-cropper">
    <img src="/images/project/learning.png" alt="avatar" class="highlight-pic">
</div>

## reinforcement learning and navigation

Traditionally, navigation is often considered as a planning problem on top of the localization and the mapping in robotic research. The introduction of deep neural network revolutionizes this view. In particular, without any prior knowledge, a robot is able to navigate the environment with the deep reinforcement learning algorithm. However, it often takes several rounds for the robot to learn such capability, which is not preferable in real scenarios. I am interested in combining the traditional robotic approaches and the deep reinforcement learning techniques to build an efficient navigation methods for autonomous robots.



<div class="image-cropper">
    <img src="/images/project/city.png" alt="avatar" class="highlight-pic">
</div>

## multirobot/multiagent systems

By cooperation, multiple robots provide more flexibility and robustness over a single robot. However, the information management among robots is of great importance to the success of the multirobot system. First of all, the communication of information should be optimized in terms of the estimation performance as well as the power consumption. Furthermore, the fusion of information is not trivial in distributed system. Unlike centralized systems, if robots are operated in a distributed way, the fusion of information becomes challenging due to the information availability. I investigate the information fusion scheme without the explicit correlation, and apply it on the multirobot localization.