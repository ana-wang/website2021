---
layout: page
title: Articles
permalink: /articles/
---

<div class="article">
{% for post in site.posts %}
  
      <h2><a href="{{ post.url }}">{{ post.title }}</a></h2>
   
  {% endfor %}
</div>