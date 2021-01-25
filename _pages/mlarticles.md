---
title: "Data Science Articles"
permalink: /mlarticles/
layout: single 
author_profile: true
---

Writing down topics in my own words usually helps me understand the subject at hand better. Here, I will be publishing articles that explain various concepts in Machine Learning and Deep Learning. 
<br><br>


<div class="grid__wrapper">
    {% for post in site.posts %}
        {% if post.categories contains 'mlarticles' %}
            {% include archive-single.html type="grid" %}
        {% endif %}
    {% endfor %}
</div>

<br clear="all" /><br/>

<script type='text/javascript' src='https://ko-fi.com/widgets/widget_2.js'></script><script type='text/javascript'>kofiwidget2.init('Buy me a coffee', '#29abe0', 'C0C3387TR');kofiwidget2.draw();</script> 
