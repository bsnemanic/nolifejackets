---
layout: default
title: Podcast
permalink: /podcast/
---

# Episodes

{% for ep in site.data.podcasts %}
<div class="episode">
  <h3>{{ ep.title }}</h3>
  <p>{{ ep.description }}</p>
  <div class="episode-links">
    <a href="{{ ep.link_youtube }}" target="_blank" rel="noopener">▶️ YouTube</a>
    <a href="{{ ep.link_spotify }}" target="_blank" rel="noopener">🎵 Spotify</a>
  </div>
</div>
{% endfor %}

[← Back Home](/)