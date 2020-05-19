---
layout: page
title: 'Object Oriented Programming'
permalink: /topic/object-oriented-programming
---

This content cover the installation related to machine translation toolkit.
<div class="posts">
  {% for post in site.categories.object-oriented-programming %}
  <div class="post">
    <h3 class="post-title">
      <a href="{{ post.url | absolute_url }}">
        {{ post.title }}
      </a>
    </h3>

    <span class="post-date">{{ post.date | date_to_string }}</span>

    {{ post.content }}
  </div>
  {% endfor %}
</div>
