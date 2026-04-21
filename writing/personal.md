---
layout: page
title: Personal Essays
description: Personal essays by Emily Maxwell Outland.
---

Reflections on research life, jiu jitsu, tea, books, and the occasional crisis of confidence.

<div class="post-list" style="margin-top:1.5rem;">
{% assign posts = site.posts | where: "category", "personal" %}
{% if posts.size > 0 %}
  {% for post in posts %}
  <div class="post-card">
    <div class="post-meta">
      <span class="tag tag--blossom">personal</span>
      <time>{{ post.date | date: "%B %-d, %Y" }}</time>
    </div>
    <h3><a href="{{ post.url | relative_url }}">{{ post.title }}</a></h3>
    <p>{{ post.excerpt | strip_html | truncate: 220 }}</p>
  </div>
  {% endfor %}
{% else %}
  <p style="color:var(--color-warm-gray); font-size:0.92rem;">Personal essays coming soon.</p>
{% endif %}
</div>

---

[&larr; Back to Writing](/writing/)
