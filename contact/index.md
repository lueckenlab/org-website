---
title: Contact
nav:
  order: 4
  tooltip: Email, address, and location
---

# {% include icon.html icon="fa-regular fa-envelope" %}Contact

Please feel free to reach out to us!

{%
  include button.html
  type="email"
  text="malte.lucken@helmholtz-munich.de"
  link="malte.lucken@helmholtz-munich.de"
%}
{%
  include button.html
  type="address"
  tooltip="Our location on Google Maps for easy navigation"
  link="https://www.google.com/maps/place/Germany/@51.1461477,7.8168976,7z"
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
  image="https://media.springernature.com/full/springer-static/image/art%3A10.1038%2Fs41592-021-01336-8/MediaObjects/41592_2021_1336_Fig1_HTML.png?as=webp"
  caption="The Research"
%}

{% endcapture %}

{% include cols.html col1=col1 col2=col2 %}

{% include section.html dark=true %}

{% capture col1 %} Is our research what
you are curious about?
{% endcapture %}

{% capture col2 %} Compose that email.
{% endcapture %}

{% capture col3 %} Send!
{% endcapture %}

{% include cols.html col1=col1 col2=col2 col3=col3 %}
