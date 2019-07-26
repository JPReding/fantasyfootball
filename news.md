---
layout: default
title: News
description: The week by week breakdown.
---
<ul>
  {% for post in site.posts %}
      <h2><a href="{{site.baseurl}}{{ post.url }}">{{ post.title }}</a></h2>
      <p>{{ post.excerpt }}</p>
      <hr>
  {% endfor %}
</ul>