---
title: "News"
layout: textlay
excerpt: "Xu-Cheng He @ Carnegie Mellon University"
sitemap: false
permalink: /allnews.html
---

# News

{% for article in site.data.news %}
<br>__{{ article.date }}__
{{ article.headline | markdownify}}
{% endfor %}
