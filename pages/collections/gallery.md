---
title: "Συλλογή Εικόνων"
layout: page-fullwidth
permalink: "/gal/pre/"
show_meta: false
header:
    image_fullwidth: "header5.jpg"
---

<ul class="photo-gallery">
  {% for image in site.gal %}
    <li><img src="{{ image.image_url }}" alt="{{ image.title}}"/></li>
  {% endfor %}
</ul>