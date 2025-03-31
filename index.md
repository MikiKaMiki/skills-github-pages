---
title: Welcome to my blog
---

Hi, I am a .NET Developer.

I am happy to see you here.


<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>
