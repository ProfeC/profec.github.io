---
category: Learning
tags: [teach,docs, wtf, learn]
filename: 2015-06-05-my-first-post.md
title: My First Jekyll Post
---

# {{ page.title }}

<ul class="tags">
  {% for tag in page.tags %}
    <li>{{ tag }}</li>
  {% endfor %}
</ul>
