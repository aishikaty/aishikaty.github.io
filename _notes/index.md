---
title: my notes
---
{% for note in site.notes | where_exp: "i", "i.url != page.url" %}
  [{{note.title}}]({{note.url}})
{% endfor %}