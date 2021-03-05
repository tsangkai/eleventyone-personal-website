---
title: Tsang-Kai Chang
subtitle: 
layout: layouts/base.njk
---

I am a PhD candidate at the Department of Electrical and Computer Engineering, UCLA.

My primary research topic focuses on the spatial autonomy of robots.

## News

<ul class="listing">
    {% for piece in news -%}
    <li>
        <time datetime="{{ piece.date }}">{{ piece.date  | dateFormat() }} </time>
         - {{ piece.event | safe }}
    </li>
    {% endfor -%}
</ul>


