---
layout: page
title: "Projects"
permalink: /projects/
---

<h1>{{ page.title }}</h1>
<div class="project-container">
    {% for project in site.data.projects %}
    <div class="project-card">
        <a href="{{ project.url }}" target="_blank">
            <img src="{{ project.image }}" alt="{{ project.title }}" class="project-image">
            <div class="project-content">
                <h2 class="project-title">{{ project.title }}</h2>
                <p class="project-description">{{ project.description }}</p>
            </div>
        </a>
    </div>
    {% endfor %}
</div>