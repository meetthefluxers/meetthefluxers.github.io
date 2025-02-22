---
layout: page
title: Podcast
permalink: /podcast/
---

{% for post in site.posts %}
{% if post.categories contains 'news' %}
{% include post-grid.html %}
{% endif %}
{% endfor %}


