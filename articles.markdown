---
layout: page
permalink: /articles/
navigation_weight: 3
---

<div class="article">

{% for post in site.posts %}
  
    <h2><a href="{{ post.url }}">{{ post.title }}</a></h2>
     {% endfor %}


</div>
