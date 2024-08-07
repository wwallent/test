---
title: Team
nav:
  order: 3
  tooltip: About our team
---
<h1><a style="text-decoration: none; color: inherit;" href="/members/Jill-Mikucki.html">Principal Investigator</a></h1>

{% capture floatcontent %}

<div class="text-center mt-5">
<a style="text-decoration: none; color: inherit;" href="/members/Jill-Mikucki.html">

  <!-- Avatar -->
  <img src="/images/Team/Jmikucki.jpg"
       style=" max-width: 200px; "
       class="portrait-image"
       />

  <!-- Name & Role -->
  <div class="text-center" style="margin-top: 10px; font-weight: var(--bold); font-size: 1.2rem" > Jill Mikucki </div> <br>
  <div class="text-center" style="margin-top: -10px"> Associate Professor (Reader) </div> <br>
</a>


</div>

{% endcapture %}
{% include float.html content=floatcontent %}

{% assign member = site.members | where: "slug", "angeloudis-p" | first %}

{% for affiliation in member.affiliations %}
<p style="margin: 0.1px; "> -  {{ affiliation }} </p>
{% endfor %}


<a style="text-decoration: none; color: inherit;" href="/members/Jill-Mikucki.html">
Dr Jill Mikucki is an Associate Professor</a>  at the **Department of Microbiology** at **University of Tennessee-Knoxville**. Her research focuses on . &nbsp;&nbsp;&nbsp;
 <a href="/members/Jill-Mikucki">(more)</a>



{% include section.html %}


# {% include icon.html icon="fa-solid fa-users" %}Team

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor
incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis
nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.

{% include section.html %}

{% include list.html data="members" component="portrait" filters="role: pi" %}
{% include list.html data="members" component="portrait" filters="role: ^(?!pi$)" %}

{% include section.html background="images/background.jpg" dark=true %}

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor
incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis
nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.

{% include section.html %}

{% capture content %}

{% include figure.html image="images/photo.jpg" %}
{% include figure.html image="images/photo.jpg" %}
{% include figure.html image="images/photo.jpg" %}

{% endcapture %}

{% include grid.html style="square" content=content %}

{% include section.html %}

# {% include icon.html icon="fa-solid fa-users" %}Alumni

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor
incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis
nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.

{% include list.html data="members" component="portrait" filters="role: alumni" %}

{% include section.html %}
