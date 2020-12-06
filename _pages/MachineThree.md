---
title: "Machine Three"
permalink: /MachineThree/
layout: archive
author_profile: true
---

The Machine Three project is youtube channel I started where I try to break down meachine learning concepts in a simple way.

<div class="grid__wrapper">
    {% for post in site.posts %}
        {% if post.categories contains 'MachineThree' %}
            {% include archive-single.html type="grid" %}
        {% endif %}
    {% endfor %}
</div>
