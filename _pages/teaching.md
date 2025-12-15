---
layout: archive
title: "Teaching Assistant"
permalink: /teaching/
author_profile: true
---

{% for post in site.teaching reversed %}
  <p style="display: flex; justify-content: space-between;">
    <span>{{ post.title }}</span>
    <span>{% if post.years %}{{ post.years }}{% else %}{{ post.date | date: "%Y" }}{% endif %}</span>
  </p>
{% endfor %}