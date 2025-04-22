---
title: "News"
layout: textlay
excerpt: "AML Lab."
sitemap: false
permalink: /allnews.html
---

# News

{% for article in site.data.news %}

<b>{{ article.date }}</b><br>
<div style="margin-left: 6px">
<em>{{ article.headline }}</em><br style="line-height: 20px" />
</div>

{% endfor %}
