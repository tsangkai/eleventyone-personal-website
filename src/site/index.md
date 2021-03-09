---
title: Tsang-Kai Chang
subtitle: 
layout: layouts/base.njk
---

<div class="image-cropper">
  <img src="images/profile-pic.png" alt="avatar" class="profile-pic">
</div>


I am a PhD candidate at the Department of Electrical and Computer Engineering, UCLA.

My primary research topic focuses on the spatial autonomy of robots.

## news

<ul class="listing">
    {% for piece in news -%}
    <li>
        {{ piece.date  | dateFormat() | dateDisplay() }} 
         - {{ piece.event | safe }}
    </li>
    {% endfor -%}
</ul>


## contact me

tsangkaichang [at] ucla [dot] edu