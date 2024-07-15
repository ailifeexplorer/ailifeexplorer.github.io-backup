---
layout: default
---

# Welcome to My Blog

Here's a list of my latest posts:

{% for post in site.posts %}
- [{{ post.title }}]({{ post.url }})
{% endfor %}