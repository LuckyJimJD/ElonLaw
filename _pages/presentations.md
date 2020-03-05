---
layout: page
permalink: /presentations/
title: Presentations 
---

# Presentations

{% for presentations in site.data.presentations %}
<a href="{{ project.osf }}">{{ presentation.revealjs }}</a>
{% endfor %}



