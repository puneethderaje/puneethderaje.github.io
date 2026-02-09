---
layout: default
title: Updates
---

# Activities

- Conference organizer ...
- Hobbies and non-research posts

# Blog Posts

{% for post in site.posts %}
- [{{ post.title }}]({{ post.url }}) — {{ post.date | date: "%Y-%m-%d" }}
{% endfor %}

