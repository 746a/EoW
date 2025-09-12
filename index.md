---
layout: home

---

# EoWW - End Of Work Week

Welcome to **EoWW**, a curated weekly selection of curious things to reverse work week wwoe.

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
