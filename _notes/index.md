---
title: my notes
---
{% for note in site.notes %}
  [{{note.title}}]({{note.url}})
{% endfor %}