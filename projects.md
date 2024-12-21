---
layout: page
title: "Projects"
permalink: /projects/
---

<h1>{{ page.title }}</h1>

<div style="text-align: center; margin-bottom: 20px;">
  <a href="/" class="btn btn--primary">Back to Home</a>
</div>

<div class="project-container">
    {% for project in site.data.projects %}
    <div class="project-card" style="background-image: url('{{ project.image }}');">
        <a href="{{ project.url }}" target="_blank">
            <div class="project-content">
                <h2 class="project-title">{{ project.title }}</h2>
                <p class="project-description">{{ project.description }}</p>
            </div>
        </a>
    </div>
    {% endfor %}
</div>