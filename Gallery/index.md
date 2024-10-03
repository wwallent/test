---
title: Photo Gallery
nav:
  order: 4
  tooltip: Photos from the field

header-dark: true
footer-dark: true
---

# Photo Gallery
Please don't share without permission...
{% include section.html %}

{% capture content %}
{% include figure.html image="images/Meager_gassy.png" caption="Lorem ipsum" %}
{% include figure.html image="images/PhotoGallery/20220918_111157.jpg" caption="Lorem ipsum" %}
{% include figure.html image="images/PhotoGallery/20220918_120013.jpg" caption="Lorem ipsum" %}
{% include figure.html image="images/PhotoGallery/20220918_132209.jpg" caption="Lorem ipsum" %}
{% include figure.html image="images/PhotoGallery/20220918_134506.jpg" caption="Lorem ipsum" %}

{% endcapture %}

{% include grid.html content=content %}
{% include section.html %}


