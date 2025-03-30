---
permalink: /news/
title: "News"
excerpt: "News and Updates"
author_profile: true
---

# News and Updates

<div class="news">
{% for item in site.data.news %}
  <div class="news-item">
    <span class="date">{{ item.date | date: "%d-%m-%Y" }}</span>
    <span class="text">{{ item.text | markdownify }}</span>
  </div>
{% endfor %}
</div> 