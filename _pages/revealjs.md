---
layout: page
permalink: /revealjs
title: Presentations
---

{% for page in site.pages %}
<p><a href="{{ site.baseurl }}{{ page.url }}" target="_blank">{{ page.title }}</a></p>
{% endfor %}
