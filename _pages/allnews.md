---
title: "News"
layout: textlay
excerpt: "Baeg Lab at University of Macau."
sitemap: false
permalink: /allnews.html
---

# News

{% for article in site.data.news %}
<p>{{ article.date }} <br> {{ article.headline | markdownify}}</p>
{% endfor %}
