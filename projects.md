---
layout: page
title: "Projects"
permalink: /projects/
---

<h1>{{ page.title }}</h1>
<div class="project-container">
    {% for project in site.data.projects %}
        {% include project_card.html project=project %}
    {% endfor %}
</div>