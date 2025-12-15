---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

## Journals

{% for post in site.publications reversed %}
  {% if post.category == 'manuscripts' %}
  <p>{{ post.citation }}</p>
  {% endif %}
{% endfor %}

## Patents

{% for post in site.publications reversed %}
  {% if post.category == 'patents' %}
  <p>{{ post.citation }}</p>
  {% endif %}
{% endfor %}

## Posters

{% for post in site.publications reversed %}
  {% if post.category == 'posters' %}
  <p>{{ post.citation }}</p>
  {% endif %}
{% endfor %}