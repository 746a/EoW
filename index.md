---
layout: home
title: EoWW
---

# EoWW – End of Work Week Inspiration

Welcome to **EoWW**, a curated weekly selection of curious things to reverse work week woe.

## Interesting Links for Interested People

## Weeks

{% assign sorted = site.weeks | sort: "date" | reverse %}
<div class="editions">
  {% for post in sorted %}
  <div class="card">
    <h2><a href="{{ post.url | relative_url }}">{{ post.title }}</a></h2>
    <p>{{ post.date | date: "%d %B %Y" }}</p>
  </div>
  {% endfor %}
</div>
