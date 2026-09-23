---
title: Welcome to my blog!
---

# Welcome to my blog

This is my GitHub Pages homepage, built with Jekyll and the `minima` theme.

Here you'll find my notes, updates, and anything else I feel like sharing.
Thanks for stopping by!

## Latest posts

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url | relative_url }}">{{ post.title }}</a>
      <small>{{ post.date | date: "%b %-d, %Y" }}</small>
    </li>
  {% endfor %}
</ul>
