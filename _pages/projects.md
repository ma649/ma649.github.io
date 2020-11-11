---
title: "My Projects"
permalink: /projects/
layout: archive
author_profile: true
---

<div class="grid__wrapper">
    {% for post in site.posts %}
        {% if post.categories contains 'projects' %}
            {% include archive-single.html type="grid" %}
        {% endif %}
    {% endfor %}
</div>
