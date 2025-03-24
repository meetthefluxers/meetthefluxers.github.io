---
layout: page
title: A Flux Science Podcast
permalink: /podcast/
---

<div style="display: flex; justify-content: center;">
    <iframe style="border-radius:0px" src="https://open.spotify.com/embed/show/5Czt3zAg38YjUirORIAP55?utm_source=generator" width="75%" height="152" frameBorder="0" allowfullscreen="" allow="autoplay; clipboard-write; encrypted-media; fullscreen; picture-in-picture" loading="lazy"></iframe>
</div>

{% for post in site.posts %}
{% if post.categories contains 'news' %}
{% include post-grid.html %}
{% endif %}
{% endfor %}


