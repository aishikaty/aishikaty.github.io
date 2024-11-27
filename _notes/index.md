---
title: my notes
---
{% for note in site.notes | where_exp: "i", "i.path != page.path" %}
  [{{note.title}}]({{note.url}}) {{note.path}} != {{page.path}}
{% endfor %}