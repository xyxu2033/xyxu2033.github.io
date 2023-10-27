---
title: Conferences
date: 2023-09-05
---

{% for post in site.tags.conference %}
  # [{{ post.title }}]({{ post.path }})
  {{ post.excerpt }}

{% endfor %}

