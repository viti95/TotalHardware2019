---
title: Videocards cards
permalink: /videocards/images
exclude_from_search: true
---
# Graphic cards
{% assign items_grouped = site.pages | group_by: 'hardware' %}
{% for hardware in items_grouped  %}
    {% if hardware.name != '' %}
        {% for page in site.pages %}
            {% if page.hardware == 'Video cards' %}
[![Preview]({{page.preview | relative_url}})]({{page.url | relative_url}})
            {% endif %}
        {% endfor %}
    {% endif %}
{% endfor %}