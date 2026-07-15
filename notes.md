---
layout: page
title: notes
permalink: /notes/
---

{% assign notes = site.notes | sort: "date" | reverse %}
<ul class="post-list note-list">
  {% for note in notes %}
  <li>
    <a href="{{ note.url | relative_url }}">
      <time datetime="{{ note.date | date_to_xmlschema }}">{{ note.date | date: "%Y-%m-%d" }}</time>
      <span>{{ note.title }}</span>
    </a>
  </li>
  {% endfor %}
</ul>
