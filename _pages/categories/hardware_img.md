---
title: Cards by hardware category with images
permalink: /hardware/images
exclude_from_search: true
---
# Cards by hardware category
{% assign items_grouped = site.pages | group_by: 'hardware' %}
{% for hardware in items_grouped  %}
    {% if hardware.name != '' %}
## {{hardware.name}}
        {% for page in site.pages %}
            {% if page.hardware == hardware.name %}
[![Preview]({{page.preview | relative_url}})]({{page.url | relative_url}})
            {% endif %}   
        {% endfor %}
    {% endif %}
{% endfor %}