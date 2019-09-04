---
layout: page
permalink: /scholarship/
title: Scholarship
---
<!-- Recent Publications -->
## Recent Publications

{% for publication in site.data.publications %}
<a href="https://luckyjimjd.github.io/assets/pdf/{{ publication.pdf }}" target="_blank">{{ publication.title }}</a>, {{ publication.volume }} {{ publication.journal }} {{ publication.page }} ({{ publication.date }}) 
{% endfor %}


<!-- Work in Progress -->
## Work in Progress

{% for project in site.data.projects %}
<a href="{{ project.osf }}">{{ project.title }}</a>
{% endfor %}



