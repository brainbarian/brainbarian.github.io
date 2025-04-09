---
layout: default
title: "Random Encounters Podcast"
---
<input type="checkbox" id="burger-toggle" style="display:none;">
<label for="burger-toggle" class="burger-menu">☰</label>
<nav class="nav-menu">
  <a href="/episodes/" class="nav-link">Episodes</a>
</nav>

<div class="linktree-container">
  <h1>Random Encounters Podcast</h1>
  <p>Under construction please wait!</p>
  
  <div class="linktree-links">
    {% for link in site.data.social %}
      <a href="{{ link.url }}" class="linktree-button" target="_blank" rel="noopener noreferrer">
        <i class="fab {{ link.icon }}"></i> {{ link.name }}
      </a>
      
    {% endfor %}
  </div>
  
  <a href="/episodes/" class="episodes-button">Podcast Episodes</a>
</div>
