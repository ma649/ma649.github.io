---
title: "Digital Art Portfolio"
permalink: /digitalart/
layout: archive
author_profile: true
---
As you can see, I am a big digital art fan. Currently, I am focusing on minimalist designs in hope to devlop a unique style/niche in the process. Within a few months I aim to open my own Art Store. But, before that happens, you can check out more designs I did on my redbubble shop <a href="https://www.redbubble.com/people/ma649/explore?asc=u&page=1&sortOrder=recent"> here</a>.
<div class="grid__wrapper">
    {% for post in site.posts %}
        {% if post.categories contains 'digitalart' %}
            {% include archive-single.html type="grid" %}
        {% endif %}
    {% endfor %}
</div>
