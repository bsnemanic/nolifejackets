---
layout: default
title: No Life Jackets
permalink: /
---

<div class="hero">
  <h1>No Life Jackets</h1>
  <p class="tagline">A podcast exploring ideas without a safety net.</p>
</div>

<div class="sections">
  <a href="/podcast/" class="card">
    <div class="card-icon">🎙️</div>
    <h2>Podcast</h2>
    <p>Listen to our latest episodes on YouTube and Spotify.</p>
  </a>

  <a href="/blog/" class="card">
    <div class="card-icon">📝</div>
    <h2>Blog</h2>
    <p>Read our thoughts and reflections.</p>
  </a>
</div>

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
