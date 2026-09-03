---
layout: default
title: Notes
---

# Notes

{% assign notes = site.pages | where: "layout", "notes" | sort: "date" | reverse %}
{% if notes.size > 0 %}
  <ul class="notes-list">
  {% for post in notes %}
    <li>
      <a href="{{ post.url | relative_url }}">{{ post.title }}</a>
      <span>{{ post.date | date: "%Y-%m-%d" }}</span>
    </li>
  {% endfor %}
  </ul>
{% else %}
  <p>Notes are coming soon.</p>
{% endif %}
