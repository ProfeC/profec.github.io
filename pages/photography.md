---
layout: page
show_meta: false
title: "Photo Galleries"
subheadline: "A Day in the Life..."
header:
   image_fullwidth: "header_unsplash_5.jpg"
permalink: "/photography/"
---
<ul>
    {% for post in site.categories.photography %}
    <li><a href="{{ site.url }}{{ post.url }}">{{ post.title }}</a></li>
    {% endfor %}
</ul>
