
---
title: "Digital Art Portfolio"
permalink: /digitalart/
layout: archive
author_profile: true
---

<div class="grid__wrapper">
    {% for post in site.posts %}
        {% if post.categories contains 'digitalart' %}
            {% include archive-single.html type="grid" %}
        {% endif %}
    {% endfor %}
</div>
