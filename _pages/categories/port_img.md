---
title: Cards by port with images
permalink: /ports/images
---
{% assign items_grouped = site.pages | group_by: 'port' %}
{% for port in items_grouped  %}
    {% if port.name != '' %}
## {{port.name}}
        {% for page in site.pages %}
            {% if page.port == port.name %}
[![Front]({{page.image}})]({{page.url}})
            {% endif %}            
        {% endfor %}
    {% endif %}
{% endfor %}