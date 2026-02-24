---
title: Home
layout: layout.njk
---

# Casper Ho

DevOps Engineer & Developer

## Latest Posts

{% for post in collections.posts %}
  <p><a href="{{ post.url }}">{{ post.data.title }}</a></p>
{% endfor %}