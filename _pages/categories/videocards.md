---
title: Video cards
permalink: /videocards
exclude_from_search: true
---
## Video cards
{% for page in site.pages %}
    {% if page.hardware == 'Videocard' %}
[{{page.title}}]({{page.url | relative_url}})
    {% endif %}
{% endfor %}
