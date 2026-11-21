---
layout: default
title: Blog
---

# Blog

Notes and articles on data science, machine learning, medical imaging, and physics.

<div class="timeline">
  {% for post in site.posts %}
    <div class="timeline-item">
      <div class="timeline-header">
        <h3 class="timeline-role"><a href="{{ post.url | relative_url }}">{{ post.title }}</a></h3>
        <span class="tag">{{ post.date | date: "%B %-d, %Y" }}</span>
      </div>
      <div class="text-muted-sm">
        {{ post.excerpt }}
      </div>
    </div>
  {% endfor %}
</div>
