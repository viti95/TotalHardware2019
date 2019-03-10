---
title: Cards by hardware category
permalink: /hardware
---
# Cards by hardware category
{% assign items_grouped = site.pages | group_by: 'hardware' %}
{% for hardware in items_grouped  %}
    {% if hardware.name != '' %}
## {{hardware.name}}
        {% for page in site.pages %}
            {% if page.hardware == hardware.name %}
[{{page.title}}]({{page.url | relative_url}})
            {% endif %}
        {% endfor %}
    {% endif %}
{% endfor %}