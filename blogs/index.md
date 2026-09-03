---
layout: default
title: Blog
---

# Blog

{% assign blog_posts = site.pages | where: "layout", "blog" | sort: "date" | reverse %}
{% if blog_posts.size > 0 %}
  <ul class="blog-list">
  {% for post in blog_posts %}
    <li>
      <a href="{{ post.url | relative_url }}">{{ post.title }}</a>
      <span>{{ post.date | date: "%B %-d, %Y" }}</span>
    </li>
  {% endfor %}
  </ul>
{% else %}
  <p>Posts are coming soon.</p>
{% endif %}
