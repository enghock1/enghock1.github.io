---
layout: archive
title: "Personal Projects"
permalink: /projects/
author_profile: true
---

{% for post in site.projects reversed %}
  <div style="margin-bottom: 2em;">
    <h2 style="margin-bottom: 0.5em;">
      <a href="{{ post.external_url }}" target="_blank" rel="noopener noreferrer">
        {{ post.title }}
      </a>
    </h2>
    <!-- {% if post.date %}
      <p style="color: #7a8288; font-size: 0.9em; margin-bottom: 0.5em;">{{ post.date | date: "%B %Y" }}</p>
    {% endif %} -->
    {% if post.excerpt %}
      <p>{{ post.excerpt }}</p>
    {% endif %}
  </div>
{% endfor %}