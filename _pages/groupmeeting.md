---
title: "Group Meeting"
layout: textlay
excerpt: "Tangram Nuclear Theory Collaboration"
sitemap: false
permalink: /groupmeeting.html
---

# groupmeeting

{% for article in site.data.news %}
<p>{{ article.date }} <br>
<em>{{ article.headline }}</em></p>
{% endfor %}
