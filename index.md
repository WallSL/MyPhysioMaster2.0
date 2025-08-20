---
layout: default
title: Início
---
## Resumos de Guidelines em Fisioterapia
Bem-vindo ao **MyPhysioMaster**. Aqui você encontra resumos práticos baseados em diretrizes.

### Últimos conteúdos
<ul>
{% assign posts = site.guidelines | sort: 'date' | reverse %}
{% for g in posts limit:10 %}
  <li><a href="{{ g.url | relative_url }}">{{ g.title }}</a> — {{ g.year }} ({{ g.organization }})</li>
{% endfor %}
</ul>

[Ver todas as guidelines](/guidelines/)
