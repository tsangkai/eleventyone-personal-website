---
title: publications
subtitle:
layout: layouts/base.njk
---



## journal papers

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
        "{{ paper.title }}", 
        <i>{{ paper.journal }}</i>, 
        vol. {{paper.vol}},
        no. {{paper.no}},
        {{ paper.date | dateFormat() | dateDisplay('MMM yyyy')}}.
        [<a href="{{ paper.url | safe}}" target="_blank" rel="noopener">link</a>]
    </li>
    {% endfor -%}
</ul>


## conference proceedings

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
        "{{ paper.title }}", 
        <i>{{ paper.journal }}</i>, 
        {{ paper.date | dateFormat() | dateDisplay('MMM yyyy')}}.
        [<a href="{{ paper.url | safe}}" target="_blank" rel="noopener">link</a>]
    </li>
    {% endfor -%}
</ul>