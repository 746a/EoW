---
layout: default
title: EoW
---

# EoW – End of Week Inspiration

Welcome to EoW, a curated weekly selection of calm and fascinating resources.

## Editions

<ul>
{% for post in site.pages %}
  {% if post.dir contains "_weeks" %}
    <li><a href="{{ post.url }}">{{ post.title }}</a></li>
  {% endif %}
{% endfor %}
</ul>
