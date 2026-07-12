---
title: "News"
permalink: /news/
layout: archive
author_profile: true
---

{% assign news_posts = site.categories.news %}

{% for post in news_posts %}
  {% include archive-single.html %}
{% endfor %}
