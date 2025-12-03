---
layout: default
title: No Life Jackets
permalink: /
---

# No Life Jackets

Welcome — a simple index of our podcast episodes and blog.

## Episodes

<ul>
{% for ep in site.data.podcasts %}
  <li>
    <strong>{{ ep.title }}</strong><br />
    <em>{{ ep.description }}</em><br />
    <a href="{{ ep.link_youtube }}" target="_blank" rel="noopener">YouTube</a>
    &nbsp;|&nbsp;
    <a href="{{ ep.link_spotify }}" target="_blank" rel="noopener">Spotify</a>
  </li>
{% endfor %}
</ul>

## Blog

See the blog index: [Blog](/blog/)
