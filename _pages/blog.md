---
permalink: /blog/
title: "Blog"
excerpt: "Notes on research and life."
layout: default
author_profile: true
---

# Blog

This page collects occasional notes and short posts on:

- 🧠Deep Learning in Medical Imaging
- 📷 Photography
- 🍳 Cooking
- ✈️ Travel

## Posts

<ul>
{% for post in site.posts %}
  <li>
    <a href="{{ post.url | relative_url }}">{{ post.title }}</a> <small>({{ post.date | date: "%Y-%m-%d" }})</small>
  </li>
{% endfor %}
</ul>