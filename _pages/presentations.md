---
layout: page
permalink: /presentations/
title: Presentations 
---

# Presentations

{% for presentations in site.data.presentations %}
<a href="{{ presentation.revealjs }}">{{ presentation.title }}</a>
{% endfor %}



