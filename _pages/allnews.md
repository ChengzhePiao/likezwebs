---
title: "News"
layout: textlay
excerpt: "AI4H Lab at Leiden University."
sitemap: false
permalink: /allnews.html
---

# News

{% for article in site.data.news %}
{{ article.date }} <br>
{{ article.headline | markdownify}}
{% endfor %}
