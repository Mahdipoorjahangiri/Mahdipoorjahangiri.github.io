---
layout: page
title: Posts
permalink: /posts/
nav_order: 2
---

# Blog Posts

{% for post in site.posts %}
- [{{ post.title }}]({{ post.url }}) - {{ post.date | date: "%B %d, %Y" }}
{% endfor %}
