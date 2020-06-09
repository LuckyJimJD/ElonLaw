---
layout: page
permalink: /revealjs
title: Presentations
---

{% for presentation in site.presentations %}
<p><a href="{{ site.url }}{{ presentation.url }}" target="_blank">{{ presentation.title }}</a></p>
{% endfor %}
