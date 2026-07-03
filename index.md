---
layout: single
title: "Home"
author_profile: true
---

## About

Evolutionary researcher mixing experimental ecology with chemical, genetic and epigenetic profiling. 
Focussed on characterizing the paths and mechanisms in which stress-induced non-genetic changes alter
organismal evolution. Postdoctoral researcher in the Plant Evolutionary Ecology group–JGU Mainz.


## Latest Updates

{% for post in site.posts limit:3 %}
### [{{ post.title }}]({{ post.url | relative_url }})

{{ post.excerpt }}

*{{ post.date | date: "%B %d, %Y" }}*

---
{% endfor %}
