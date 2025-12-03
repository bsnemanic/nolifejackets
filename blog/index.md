---
layout: default
title: Blog
permalink: /blog/
---

# Blog Posts

{% for post in site.posts %}
  <div class="post-card">
    <h3><a href="{{ post.url }}">{{ post.title }}</a></h3>
    <p class="post-date">{{ post.date | date: "%B %d, %Y" }}</p>
    <p>{{ post.excerpt }}</p>
  </div>
{% endfor %}

[← Back Home](/)