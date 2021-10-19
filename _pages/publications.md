---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

## Peer-Reviewed Publications

{% include base_path %}

{% for post in site.publications reversed %}
     {% if post.pubtype == 'peerreviewed' %}
  {% include archive-single.html %}
{% endfor %}


## Preprints

{% include base_path %}

{% for post in site.publications reversed %}
     {% if post.pubtype == 'preprint' %}
      {% include archive-single.html %}
{% endfor %}
