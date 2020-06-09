---
layout: page
permalink: /revealjs
title: Presentations
---

{% for Presentation in site.Presentations %}
<p><a href="{{ site.url }}{{ Presentation.url }}" target="_blank">{{ Presentation.title }}</a></p>
{% endfor %}
