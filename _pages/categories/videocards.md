---
title: Videocards cards
permalink: /videocards
exclude_from_search: true
---
# Video cards
{% assign items_grouped = site.pages | group_by: 'hardware' %}
{% for hardware in items_grouped  %}
    {% if hardware.name != '' %}
        {% for page in site.pages %}
            {% if page.hardware == 'Video cards' %}
[{{page.title}}]({{page.url | relative_url}})
            {% endif %}
        {% endfor %}
    {% endif %}
{% endfor %}