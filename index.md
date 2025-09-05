---
layout: home
title: EoWW
---

# EoWW – End of Work Week Inspiration

Welcome to **EoWW**, a curated weekly selection of curious things to reverse work week woe.

## Interesting Links for Interested People

## Weeks

{% assign sorted = site.weeks | sort: "date" | reverse %}
{% for post in sorted %}
- [{{ post.title }}]({{ post.url }})
{% endfor %}
