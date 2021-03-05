---
title: publication
layout: layouts/base.njk
subtitle: Clone and deploy your own EleventyOne starter template.
---



### Journal Papers

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
        {{paper.year}}.
    </li>
    {% endfor -%}
</ul>


### Conference Proceedings

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
        {{paper.year}}.
    </li>
    {% endfor -%}
</ul>