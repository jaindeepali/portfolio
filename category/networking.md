---
layout: home
title: Networking
---
<ul>
  {% for post in site.categories.networking %}
    <li>
      <img src="{{ post.images.first }}">
      <a href="{{ post.url }}">{{ post.title }}</a>
      <div class="excerpt">
      	{{ post.excerpt }}
      </div>
      <div class="full-content">
      	{{ post.content }}
      </div>
    </li>
  {% endfor %}
</ul>