---
title: "Data Science Articles"
permalink: /articles/
layout: single 
author_profile: true
---

Writing down topics in my own words usually helps me understand the subject at hand better. Here, I will be publishing articles that explain various concepts in Machine Learning and Deep Learning. 
<br><br>


<div class="grid__wrapper">
    {% for post in site.posts %}
        {% if post.categories contains 'articles' %}
            {% include archive-single.html type="grid" %}
        {% endif %}
    {% endfor %}
</div>

<br clear="all" /><br/>

[![ko-fi](https://ko-fi.com/img/githubbutton_sm.svg)](https://ko-fi.com/C0C3387TR)
