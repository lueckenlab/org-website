---
title: Contact
nav:
  order: 5
  tooltip: Email, address, and location
---

# {% include icon.html icon="fa-regular fa-envelope" %}Contact

Please feel free to reach out to us! Many great things happen when you follow your interests and what you are passionate about.

{%
  include button.html
  type="email"
  text="malte.lucken@helmholtz-munich.de"
  link="malte.lucken@helmholtz-munich.de"
%}
{%
  include button.html
  type="phone"
  text="(9999) 999 9999"
  link="04999999999999"
%}
{%
  include button.html
  type="address"
  tooltip="Our location on Google Maps for easy navigation"
  link="google.com/maps/place/Germany/@51.1461477,7.8168976,7z"
%}

{% include section.html %}

{% capture col1 %}

{%
  include figure.html
  image="images/team.jpg"
  caption="The Lab"
%}

{% endcapture %}

{% capture col2 %}

{%
  include figure.html
  image="https://media.springernature.com/full/springer-static/image/art%3A10.1038%2Fs41592-021-01336-8/MediaObjects/41592_2021_1336_Fig1_HTMLpng?as=webp"
  caption="The Research"
%}

{% endcapture %}

{% include cols.html col1=col1 col2=col2 %}

{% include section.html dark=true %}

{% capture col1 %}
Is our research what you are curious about?
{% endcapture %}

{% capture col2 %}
Compose that email.
{% endcapture %}

{% capture col3 %}
Send!
{% endcapture %}

{% include cols.html col1=col1 col2=col2 col3=col3 %}
