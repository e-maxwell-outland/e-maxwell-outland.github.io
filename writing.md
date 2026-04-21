---
layout: page
title: Writing
description: Research notes and personal essays by Emily Maxwell Outland.
---

I write to think through ideas before they're finished, and to make research accessible outside the lab. Here you'll find notes from ongoing work alongside more personal reflections — the kind of thinking that doesn't fit neatly into a paper.

---

## Research Notes

Occasional notes on ongoing work, interesting papers, and thinking-in-progress.

<div class="post-list">
{% assign research_posts = site.posts | where: "category", "research" | limit: 2 %}
{% if research_posts.size > 0 %}
  {% for post in research_posts %}
  <div class="post-card">
    <div class="post-meta">
      <span class="tag tag--sage">research</span>
      <time>{{ post.date | date: "%B %-d, %Y" }}</time>
    </div>
    <h3><a href="{{ post.url | relative_url }}">{{ post.title }}</a></h3>
    <p>{{ post.excerpt | strip_html | truncate: 180 }}</p>
  </div>
  {% endfor %}
{% else %}
  <p style="color:var(--color-warm-gray); font-size:0.92rem;">Research notes coming soon.</p>
{% endif %}
</div>

[All Research Notes &rarr;](/writing/research/)

---

## Personal Essays

Reflections on research life, jiu jitsu, tea, and the occasional crisis of confidence.

<div class="post-list">
{% assign personal_posts = site.posts | where: "category", "personal" | limit: 2 %}
{% if personal_posts.size > 0 %}
  {% for post in personal_posts %}
  <div class="post-card">
    <div class="post-meta">
      <span class="tag tag--blossom">personal</span>
      <time>{{ post.date | date: "%B %-d, %Y" }}</time>
    </div>
    <h3><a href="{{ post.url | relative_url }}">{{ post.title }}</a></h3>
    <p>{{ post.excerpt | strip_html | truncate: 180 }}</p>
  </div>
  {% endfor %}
{% else %}
  <p style="color:var(--color-warm-gray); font-size:0.92rem;">Personal essays coming soon.</p>
{% endif %}
</div>

[All Personal Essays &rarr;](/writing/personal/)
