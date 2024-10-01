title: Photo Gallery
description: Photos from the field
nav:
  order: 4
  tooltip: Photos, people
header: images/header-for-this-page.jpg
footer: images/footer-for-this-page.jpg
header-dark: false
footer-dark: false

{% capture content %}
  ![](/images/PhotoGallery/20220918_111157.jpg)

  ![](/images/PhotoGallery/20220918_120013.jpg)

  ![](/images/PhotoGallery/20220918_132209.jpg)

  ![](/images/PhotoGallery/20220918_134506.jpg)
{% endcapture %}

{% include grid.html content=content %}
