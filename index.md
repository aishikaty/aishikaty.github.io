---
title: my notes
---
{% for note in site.notes %}
  [{{ note.title }}]({{ note.url | slice: 1, note.url.size }})
{% endfor %}