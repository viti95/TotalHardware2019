---
title: Cards by port with images
permalink: /ports/images
---
# Cards by port
{% assign items_grouped = site.pages | group_by: 'port' %}
{% for port in items_grouped  %}
    {% if port.name != '' %}
## {{port.name}}
        {% for page in site.pages %}
            {% if page.port == port.name %}
[![Preview]({{page.preview | relative_url}})]({{page.url | relative_url}})
            {% endif %}            
        {% endfor %}
    {% endif %}
{% endfor %}