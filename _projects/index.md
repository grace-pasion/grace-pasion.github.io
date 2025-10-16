---
layout: page
permalink: /projects/
title: Projects
---
{% for project in site.projects %}
<div class="project-card">
  <h2><a href="{{ project.url | relative_url }}">{{ project.title }}</a></h2>
  <p>{{ project.excerpt }}</p>
</div>
{% endfor %}
