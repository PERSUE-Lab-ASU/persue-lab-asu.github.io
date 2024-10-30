---
title: "News"
layout: textlay
excerpt: "Persue Lab at Arizona State University"
sitemap: false
permalink: /allnews.html
---

# News

---

{% for article in site.data.news %}

{{ article.date }} 
{{ article.headline | markdownify}}
{% endfor %}
