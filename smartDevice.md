---
layout: page
title: Smart_Device
---

{% for post in site.posts %}
  {% if post.tags contains 'Smart_Device' %}
    <!-- 카테고리1에 해당하는 글을 여기에 표시합니다. -->
  {% endif %}
{% endfor %}

