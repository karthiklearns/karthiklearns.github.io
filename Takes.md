---
layout: page
title: Takes
permalink: /Takes/
---

<div class="posts">
  {% for post in site.categories.Takes %}
  <div class="post">
    <h1 class="post-title">
      <a href="{{ post.url | relative_url }}">
        {{ post.title }}
      </a>
    </h1>

    <span class="post-date">{{ post.date | date_to_string }}</span>

    {{ post.content }}
  </div>
  {% endfor %}
</div>