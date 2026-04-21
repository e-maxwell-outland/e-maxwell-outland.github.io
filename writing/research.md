---
layout: page
title: Research Notes
description: Research notes and thinking-in-progress by Emily Maxwell Outland.
---

Notes on ongoing work, papers worth thinking about, and ideas that aren't papers yet.

<div class="post-list" style="margin-top:1.5rem;">
{% assign posts = site.posts | where: "category", "research" %}
{% if posts.size > 0 %}
  {% for post in posts %}
  <div class="post-card">
    <div class="post-meta">
      <span class="tag tag--sage">research</span>
      <time>{{ post.date | date: "%B %-d, %Y" }}</time>
    </div>
    <h3><a href="{{ post.url | relative_url }}">{{ post.title }}</a></h3>
    <p>{{ post.excerpt | strip_html | truncate: 220 }}</p>
  </div>
  {% endfor %}
{% else %}
  <p style="color:var(--color-warm-gray); font-size:0.92rem;">No research notes yet — check back soon.</p>
{% endif %}
</div>

---

[&larr; Back to Writing](/writing/)
