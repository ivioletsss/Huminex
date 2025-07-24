---
title: Contact
nav:
  order: 5
  tooltip: Email, address, and location
---

# {% include icon.html icon="fa-regular fa-envelope" %}Contact

Got ideas that broadly match our research goals? Come join us! 
Given our highly transdisciplinary focus, we warmly welcome individuals from diverse backgrounds including computer science, design, psychology, and cognitive science.

{%
  include button.html
  type="email"
  text="tut45086@temple.edu"
  link="tut45086@temple.edu"
%}
{%
  include button.html
  type="phone"
  text=" "
  link=" "
%}
{%
  include button.html
  type="address"
  tooltip="Our location on Google Maps for easy navigation"
  link="https://www.google.com/maps"
%}

{% include section.html %}

{% capture col1 %}

{%
  include figure.html
  image="images/contact2.png"
  caption="Contact with us!"
%}

{% endcapture %}

{% capture col2 %}

{%
  include figure.html
  image="images/contact1.png"
  caption="Contact with us!"
%}

{% endcapture %}

{% include cols.html col1=col1 col2=col2 %}
