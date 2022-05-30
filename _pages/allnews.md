---
title: "News"
layout: textlay
excerpt: "Xu-Cheng He @ Carnegie Mellon University"
sitemap: false
permalink: /allnews.html
---

# News

{% for article in site.data.news %}
<p>{{ article.date }} <br>
<em>{{ article.headline | markdownify}}</em></p>
{% endfor %}
