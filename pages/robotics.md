---
layout: page
show_meta: false
title: "Robotics"
subheadline: ""
teaser: "Here you can find a list of all the posts that have to do with my work with my robotics team, FTC Team 6832 (Iron Reign)."
header:
   image_fullwidth: "maxteaching.jpg"
permalink: "/robotics/"
---


<ul>
    {% for post in site.categories.robotics %}
    <li><a href="{{ site.url }}{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a></li>
    {% endfor %}
</ul>

