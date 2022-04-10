---
layout: page
title: Field notes
permalink: /fieldnotes/
---
<ul>
  {% for post in site.posts %}
    <li>
      <h2>{{ post.title }}</h2>
      < ! <h2><a href="{{ post.url }}">{{ post.title }}</a></h2> >
      {{ post.excerpt }}
    </li>
  {% endfor %}
</ul>
