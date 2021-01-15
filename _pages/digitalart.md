---
title: "Digital Art Portfolio"
permalink: /digitalart/
layout: archive
author_profile: true
---
As you can see, I am a big digital art fan. I am not a proffessional artist (yet!), and this mostly a hobby for me. Currently, I am focusing on minimal / storyboard designs in hope to devlop a unique style/niche in the process. Within a few months I aim to open my own Digital Art Store! But, before that happens, you can check out my designs at my <a href="https://ko-fi.com/otusflow/gallery"> Ko-fi gallery </a> or vist my redbubble shop <a href="https://www.redbubble.com/people/ma649/explore?asc=u&page=1&sortOrder=recent"> here</a>.
<div class="grid__wrapper">
    {% for post in site.posts %}
        {% if post.categories contains 'digitalart' %}
            {% include archive-single.html type="grid" %}
        {% endif %}
    {% endfor %}
</div>
<br clear="all" /><br/>

<script type='text/javascript' src='https://ko-fi.com/widgets/widget_2.js'></script><script type='text/javascript'>kofiwidget2.init('Support me on Ko-fi', '#19a2cf', 'C0C3387TR');kofiwidget2.draw();</script> 

