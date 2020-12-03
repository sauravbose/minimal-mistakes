---
permalink: /projects/
title: "Projects"
author_profile: true
---
Home/Projects

{% for page in site.pages %}
  {{page.title}} <br>
{% endfor %}

These are the projects.

{% for page in site.pages %}
  {{page.url}} <br>
{% endfor %}
