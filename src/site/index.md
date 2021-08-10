---
title: Tsang-Kai Chang
subtitle: 
layout: layouts/base.njk
---

<div class="image-cropper">
    <img src="/images/profile-pic.jpeg" alt="my profile picture" class="profile-pic">
</div>


I am a PhD candidate in the Department of Electrical and Computer Engineering, UCLA.

Here is my cv.

## research interests

My research focuses on SLAM, multiagent systems, directional statistics and reinforcement learning.


<!--
<ul class="feature-icons">
    <li class="far fa-eye">SLAM</li>
    <li class="far fa-comments">reinforcement learning</li>
    <li class="far fa-map">navigation</li>    
    <li class="fas fa-kiwi-bird">localization in brains</li>
    <li class="fas fa-users">multirobot/multiagent systems</li>
</ul>
-->

## news

<ul class="listing">
    {% for piece in news.slice(0,6) -%}
    <li>
        [{{ piece.date  | dateFormat() | dateDisplay() }}] 
          {{ piece.event | safe }}
    </li>
    {% endfor -%}
</ul>


## contact me

tsangkaichang [at] ucla [dot] edu
