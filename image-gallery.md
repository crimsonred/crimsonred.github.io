---
title: Gallery
---

## Spider gallery

{% for image in site.gallery %}
[![{{ image.title }}]({{ image.imageUrl }})]({{ image.url }})
> {{ image.title }}
[Next]({{ site.gallery[forloop.index-1] }})
{% endfor %}

## Image submission

In case you have some images to be submitted just email them to some_email@example.com
