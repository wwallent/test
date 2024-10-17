---
title: Team
nav:
  order: 3
  tooltip: About our team
---

# {% include icon.html icon="fa-solid fa-users" %}Team

We are an interdisciplinary group of researchers passionate about research in extreme environments and its applications to microbiology, astrobiology, engineering, and climate science. 

{% include section.html %}

{% include list.html data="members" component="portrait" filters="role: pi, alumni: ^(?!true$)" %}
{% include list.html data="members" component="portrait" filters="role: ^(?!pi$), alumni: false" %}


{% include section.html %}


# {% include icon.html icon="fa-solid fa-users" %}Alumni

Our lab alumni go on to excel in a wide range of academic and professional careers, building on the skills and experiences they gained while working with us. Many of our former members have secured prestigious postdoctoral positions, faculty appointments, and leadership roles in industry. We take pride in their continued success and the lasting impact they make in the scientific community.

{% include section.html %}

{% include list.html data="members" component="portrait" filters="alumni: true" %}

{% include section.html %}
