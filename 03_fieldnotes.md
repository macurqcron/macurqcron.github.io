---
layout: page
title: Field notes
permalink: /fieldnotes/
---
<ul>
  {% for post in site.posts %}
    <li>
      <h2>{{ post.title }}</h2>
     
      {{ post.excerpt }}
    </li>
  {% endfor %}
</ul>
