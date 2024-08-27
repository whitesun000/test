---
layout: default
title: "Blog"
permalink: /blog/
---

Welcome to the Blog page. Here you can find all of my blog posts.

{% for post in site.posts %}
  <h2><a href="{{ post.url }}">{{ post.title }}</a></h2>
  <p>{{ post.excerpt }}</p>
  <hr>
{% endfor %}
