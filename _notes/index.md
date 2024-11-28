---
title: my notes
---
{% assign notes = site.notes | where_exp: "i", "i.path != page.path" %}
{% for note in notes %}
  [{{note.slug}}]({{note.title}})
{% endfor %}