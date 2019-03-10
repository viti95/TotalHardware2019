---
title: Cards by port
permalink: /ports
---
{% assign items_grouped = site.pages | group_by: 'port' %}
{% for port in items_grouped  %}
    {% if port.name != '' %}
## {{port.name}}
        {% for page in site.pages %}
            {% if page.port == port.name %}
[{{page.title}}]({{page.url}})
            {% endif %}
        {% endfor %}
    {% endif %}
{% endfor %}