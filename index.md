---
layout: single
title: "Florian Mai"
excerpt: "Junior Research Group Leader @ University of Bonn"
author_profile: true
---

## Welcome

I am a Junior Research Group Leader at the [CAISA group at University of Bonn](https://caisa-lab.github.io/), led by Lucie Flek, as part of [The Lamarr Institute for Machine Learning and Artificial Intelligence](https://lamarr-institute.org/).

My research focuses on learning planning components for language models from unlabeled data, applying the "bitter lesson" of AI to planning and reasoning in LLMs. I believe that taking the self-supervised learning approach to the level of planning and reasoning is key to unlocking the full potential of language models.

[Read more about my research and background →](/about/)

## News

<div class="news">
{% for item in site.data.news limit:5 %}
  <div class="news-item">
    <span class="date">{{ item.date | date: "%d-%m-%Y" }}</span>
    <span class="text">{{ item.text | markdownify }}</span>
  </div>
{% endfor %}
</div>

[View all news →](/news/)

## Selected Publications

<div class="publications-list">
{% assign selected_publications = site.publications | where: "selected", true | sort: "date" | reverse %}
{% for pub in selected_publications limit:3 %}
  <div class="publication-item">
    <a href="{{ pub.url | relative_url }}">{{ pub.title }}</a><br>
    <em>{{ pub.venue }}</em>, {{ pub.date | date: "%Y" }}<br>
    {{ pub.excerpt }}
  </div>
{% endfor %}
</div>

[View all publications →](/publications/)