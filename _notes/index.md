---
title: my notes
---
{% assign notes = site.notes | where_exp: "i", "i.path != page.path" %}
{% for note in notes %}
  <{{note.title}}>
  <{{note.name}}>
  <{{note.slug}}>
  <{{note.path}}>
  <{{note.slug}}>
{% endfor %}