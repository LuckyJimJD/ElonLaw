---
layout: page
permalink: /presentations/
title: Presentations
---

{% for presentation in site.data.presentations %}
<p><a href="{{ site.baseurl }}/presentations/{{ presentation.revealjs }}" target="_blank">{{ presentation.title }}</a></p>
{% endfor %}

