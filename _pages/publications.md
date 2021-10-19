---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

## Selected Publications
{% include base_path %}

{% for post in site.publications reversed %}
     {% if post.selected %}
         {% include archive-single.html %}
     {% endif %}
{% endfor %}

## Peer-Reviewed Publications

{% include base_path %}

{% for post in site.publications reversed %}
     {% if post.pubtype == 'peerreviewed' %}
         {% include archive-single.html %}
     {% endif %}
{% endfor %}


## Preprints

{% include base_path %}

{% for post in site.publications reversed %}
     {% if post.pubtype == 'preprint' %}
         {% include archive-single.html %}
     {% endif %}
{% endfor %}
