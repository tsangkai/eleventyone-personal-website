---
title: Tsang-Kai Chang
subtitle: A project scaffold for getting building with Eleventy quickly.<br /> Made by <a href="https://twitter.com/philhawksworth">Phil</a> for <a href="https://twitter.com/philhawksworth">Phil</a>, but perhaps you might also find it useful.
layout: layouts/base.njk
---

## News

<ul class="listing">
    {% for piece in news -%}
    <li>
        <time datetime="{{ piece.date }}">{{ piece.date  | dateFormat() }} </time>
         - {{ piece.event | safe }}
    </li>
    {% endfor -%}
</ul>


## Post pages

The pages found in in the posts

<ul class="listing">
{%- for page in collections.post -%}
  <li>
    <time datetime="{{ page.date }}">{{ page.date | dateDisplay() }}</time> - 
    <a href="{{ page.url }}">{{ page.data.title }}</a>
  </li>
{%- endfor -%}
</ul>

