---
title: publication
layout: layouts/base.njk
subtitle:
---



## Journal Papers

<ul class="listing">
    {% for paper in publication.articles -%}
    <li>
        {% for name in paper.authors -%}
            {% if loop.last == true -%}
               and
            {% endif -%}
            {% if name == "T.-K. Chang" -%}
                <u>{{ name }}</u>,
            {% else -%}
                {{ name }},
            {% endif -%}
        {% endfor -%}
        "<a href="{{ paper.url | safe}}" target="_blank" rel="noopener">{{ paper.title }}</a>", 
        <i>{{ paper.journal }}</i>, 
        vol. {{paper.vol}},
        no. {{paper.no}},
        {{ paper.date | dateFormat() | dateDisplay('MMM yyyy')}}.
    </li>
    {% endfor -%}
</ul>


## Conference Proceedings

<ul class="listing">
    {% for paper in publication.proceedings -%}
    <li>
        {% for name in paper.authors -%}
            {% if loop.last == true -%}
               and
            {% endif -%}
            {% if name == "T.-K. Chang" -%}
                <u>{{ name }}</u>,
            {% else -%}
                {{ name }},
            {% endif -%}
        {% endfor -%}
        "<a href="{{ paper.url | safe}}" target="_blank" rel="noopener">{{ paper.title }}</a>", 
        <i>{{ paper.journal }}</i>, 
        {{ paper.date | dateFormat() | dateDisplay('MMM yyyy')}}.
    </li>
    {% endfor -%}
</ul>