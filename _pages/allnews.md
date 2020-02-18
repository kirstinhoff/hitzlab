---
title: "News"
layout: textlay
excerpt: "Hitz Cardiovascular Genetics Lab"
sitemap: false
permalink: /allnews.html
---

# News

{% for funding in site.data.news %}
<p>{{ funding.agencia }} <br>
<em>{{ funding.logo }}</em></p>
{% endfor %}
