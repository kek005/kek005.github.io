---
layout: page
title: "Projects"
permalink: /projects/
---

# Projects

Here are some of the projects I've worked on:

{% for project in site.data.projects %}
- [{{ project.title }}]({{ project.url }}): {{ project.description }}
{% endfor %}