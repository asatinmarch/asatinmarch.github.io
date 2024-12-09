---
title: Welcome to my blog
---
<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }} </a><a>{{ post.date }}</a>
      <p>{{ post.excerpt }}</p>
    </li>
  {% endfor %}
</ul>
