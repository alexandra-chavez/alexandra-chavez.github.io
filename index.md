---
layout: single
title: "Home"
author_profile: true
---

## About

Write your short professional introduction here.

## Latest Updates

{% for post in site.posts limit:3 %}
### [{{ post.title }}]({{ post.url | relative_url }})

{{ post.excerpt }}

*{{ post.date | date: "%B %d, %Y" }}*

---
{% endfor %}
