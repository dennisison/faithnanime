---
permalink: /reviews/
title: "All Reviews"
layout: single
author_profile: true
---

Here are all my anime reviews, organized by rating and genre.

## Recent Reviews

{% for post in site.posts limit:10 %}
  <h3><a href="{{ post.url }}">{{ post.title }}</a></h3>
  <p>{{ post.excerpt }}</p>
{% endfor %}

[View all posts](/year-archive/)
