---
layout: default
title: EoW
---

# EoW – End of Week Inspiration

Welcome to **EoW**, a curated end of weekly selection of curious things to reverse work week woe.

## Interesting Links for Interested People

## Weeks

{% for post in site.pages %}
  {% if post.dir contains "_weeks" %}
- [{{ post.title }}]({{ post.url }})
  {% endif %}
{% endfor %}
