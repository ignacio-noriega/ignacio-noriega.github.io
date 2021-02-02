---
layout: portfolio-details
permalink: /portfolio/
title: codeklavier
category: piano
link: #
---

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
      {{ post.content }}
    </li>
  {% endfor %}
</ul>
