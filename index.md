---
title: my notes
---
{% for note in site.notes %}
  [{{note.title}}]({% post_url note.path %})
{% endfor %}