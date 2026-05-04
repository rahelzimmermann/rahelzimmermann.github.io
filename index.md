---
layout: homesite
title: About
---


<img src="/public/profile_pic.jpg" width="240" />

{% for post in site.posts %}
{% if post.path contains 'rahels-posts' %}
  <article>
    {{ post.content }}
  </article>
{% endif %} 
{% endfor %}