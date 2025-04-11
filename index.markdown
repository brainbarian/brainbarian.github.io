---
layout: default
title: Random Encounters Podcast
---



<div class="linktree">
  {% for social in site.data.social %}
    {% if social.url contains "yourpage" or social.url contains "yourshowid" %}
      <!-- Skip placeholder URLs -->
    {% else %}
      <a href="{{ social.url }}" class="link-button {{ social.name | downcase | replace: ' ', '-' }}" aria-label="Visit our {{ social.name }} page">
        <i class="fab {{ social.icon }}"></i> {{ social.name }}
      </a>
    {% endif %}
  {% endfor %}
</div>

