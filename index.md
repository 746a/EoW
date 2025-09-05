---
layout: default
title: EoW
---

# EoW – End of Week Inspiration

Welcome to **EoW**, a curated end of weekly selection of curious things to reverse work week woe.

## Interesting Links for Interested People

## Editions

{% assign sorted = site.weeks | sort: "date" | reverse %}
{% for post in sorted %}
- [{{ post.title }}]({{ post.url }})
{% endfor %}
