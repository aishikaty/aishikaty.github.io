---
title: my notes
---
{% for note in site.notes %}
<a href="{{ note.url | slice: 1, note.url.size }}">{{ note.title }}</a><br>
{% endfor %}