---
title: Welcome to my blog
---
<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
      <p>{{ content }}</p>
      <p>{{ post.excerpt }}</p>
    </li>
  {% endfor %}
  <p> site.posts</p>
</ul>
