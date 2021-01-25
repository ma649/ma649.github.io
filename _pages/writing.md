---
title: "Weekly Writing"
permalink: /writing/
layout: archive
author_profile: true
---
A collection of  weekly writings on various topics and concepts from readings.

<div class="grid__wrapper">
    {% for post in site.posts %}
        {% if post.categories contains 'writing' %}
            {% include archive-single.html type="grid" %}
        {% endif %}
    {% endfor %}
</div>
