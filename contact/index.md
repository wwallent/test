---
title: Contact
nav:
  order: 5
  tooltip: Email, address, and location
---

# {% include icon.html icon="fa-regular fa-envelope" %}Contact

If you're interested in joining our lab as a graduate student, check out the UTK Microbiology website for information about the grad program and application process. 

{%
  include button.html
  type="email"
  text="jmikucki@utk.edu"
  link="jmikucki@utk.edu"
%}
{%
  include button.html
  type="phone"
  text="(865)974-4301"
  link="+1-865-974-4301"
%}
{%
  include button.html
  type="address"
  tooltip="Our location on Google Maps for easy navigation"
  link="https://www.google.com/maps/place/1414+Circle+Dr,+Knoxville,+TN+37916/@35.9573098,-83.9273089,715m/data=!3m2!1e3!4b1!4m6!3m5!1s0x885c17e77f21d151:0x3524772dc470094!8m2!3d35.9573098!4d-83.924734!16s%2Fg%2F11fflx6j9f?entry=ttu&g_ep=EgoyMDI0MTAwMS4wIKXMDSoASAFQAw%3D%3D"
%}

{% include section.html %}

{% capture col1 %}

{%
  include figure.html
  image="images/Mossman-2-4050572619-2.jpg"
  caption="UTK Microbiology Department"
  link="https://micro.utk.edu"
%}

{% endcapture %}

{% capture col2 %}

{%
  include figure.html
  image="images/cec319d4410ef4e4a7d113dfbbcbfa7f-1363889473.jpg"
  caption="UTK College of Arts and Sciences"
  link="https://artsci.utk.edu/academics/departments/"
%}

{% endcapture %}

{% include cols.html col1=col1 col2=col2 %}

{% include section.html dark=true %}

{% capture col1 %}
Lorem ipsum dolor sit amet  
consectetur adipiscing elit  
sed do eiusmod tempor
{% endcapture %}

{% capture col2 %}
Lorem ipsum dolor sit amet  
consectetur adipiscing elit  
sed do eiusmod tempor
{% endcapture %}

{% capture col3 %}
Lorem ipsum dolor sit amet  
consectetur adipiscing elit  
sed do eiusmod tempor
{% endcapture %}

{% include cols.html col1=col1 col2=col2 col3=col3 %}
