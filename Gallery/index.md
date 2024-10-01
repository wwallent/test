---
title: Photo Gallery
nav:
  order: 4
  tooltip: Photos from the field

header-dark: true
footer-dark: true
---

# Photo Gallery
Our field sites are uniquely photogenic...enjoy!
{% include section.html %}

{% assign images = site.static_files | where: "path", "images/PhotoGallery/" %}
{% for image in images %}
  ![]({{ image.path }})
{% endfor %}



