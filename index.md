---
layout: home
title: EoW
---

# EoW – End of Week Inspiration

Welcome to **EoW**, a curated weekly selection of curious things to reverse work week woe.

## Interesting Links for Interested People

## Weeks

{% assign sorted = site.weeks | sort: "date" | reverse %}
{% for post in sorted %}
- [{{ post.title }}]({{ post.url }})
{% endfor %}
