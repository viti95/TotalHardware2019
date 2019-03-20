---
title: Cards by company
permalink: /company
exclude_from_search: true
---
## Cards by company
{% assign items_grouped = site.pages | group_by: 'company' %}
{% for company in items_grouped  %}
    {% if company.name != '' %}
### {{company.name}}
        {% for page in site.pages %}
            {% if page.company == company.name %}
[{{page.title}}]({{page.url | relative_url}})
            {% endif %}
        {% endfor %}
    {% endif %}
{% endfor %}