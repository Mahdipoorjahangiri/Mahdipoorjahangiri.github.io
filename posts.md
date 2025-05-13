---
layout: page
title: All Posts
permalink: /posts/
toc: true
---

# All Blog Posts

{% for post in site.posts %}
- **{{ post.date | date: "%Y-%m-%d" }}**: [{{ post.title }}]({{ post.url }})
{% endfor %}