---
layout: page
title: Random Encounters Podcast
---

<div class="linktree">
  {% for social in site.data.social %}
    <a href="{{ social.url }}" class="link-button {{ social.platform | downcase | replace: ' ', '-' }}" aria-label="Visit our {{ social.name }} page">
      <i class="fab {{ social.icon }}"></i> {{ social.name }}
    </a>
  {% endfor %}
</div>
