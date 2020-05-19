---
layout: page
title: 'Artificial Intelligence & Deep Learning'
permalink: /topic/aidl
---

This series of tutorial is about the basics of artificial intelligence and some in-depth details of neural networks and deep learning. We will follow a step wise approach to explore these topics, so no need to worry if you don't have any background.
<div class="posts">
  {% for post in site.categories.AIDL %}
  <div class="post">
    <h3 class="post-title">
      <a href="{{ post.url | absolute_url }}">
        {{ post.title }}
      </a>
    </h3>

    <span class="post-date">{{ post.date | date_to_string }}</span>
  </div>
  {% endfor %}
</div>
