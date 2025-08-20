---
layout: default
title: Todas as guidelines
permalink: /guidelines/
---
## Todas as guidelines
<ul>
{% assign sorted = site.guidelines | sort: 'title' %}
{% for g in sorted %}
  <li><a href="{{ g.url | relative_url }}">{{ g.title }}</a> — {{ g.year }} ({{ g.organization }})</li>
{% endfor %}
</ul>
