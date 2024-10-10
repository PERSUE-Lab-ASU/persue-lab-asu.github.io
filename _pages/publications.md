---
title: "Persue Lab - Publications"
layout: gridlay
excerpt: "Persue Lab -- Publications."
sitemap: false
permalink: /publications/ 
---


# Publications



## Full List of publications

{% for publi in site.data.publist %}

{{ publi.title }} 
{{ publi.authors }} 
{{ publi.link.display }}

{% endfor %}
