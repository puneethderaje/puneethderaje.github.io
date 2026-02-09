---
layout: default
title: Updates
---

# Activities

- Teaching assistant for ...
- Conference organizer ...
- Reviewer for ...

# Blog Posts

{% raw %}{% for post in site.posts %}
- [{{ post.title }}]({{ post.url }}) — {{ post.date | date: "%Y-%m-%d" }}
{% endfor %}{% endraw %}

