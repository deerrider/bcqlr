---
layout: page
title: 死人天使
comments: false
---
<div class="post-list">
    {% for post in site.posts %} 
        {% if post.category == "死人天使" %}
        {% if post.finished %}
            <ul>
            <li class="wow fadeInLeft" data-wow-duration="1.5s">
            <a class="zoombtn" href="{{ site.url }}{{ post.url }}">{{ post.title }}</a>
            </li>
            </ul>
        {% endif %}
        {% endif %} 
    {% endfor %}
</div>