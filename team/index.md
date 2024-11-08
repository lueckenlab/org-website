---
title: Team
nav:
  order: 3
  tooltip: About our team
---

# {% include icon.html icon="fa-solid fa-users" %}Team

Meet the faces and names of the heart of the lab!

{% include section.html %}

{% include list.html data="members" component="portrait" filters="role: pi" %}
{% include list.html data="members" component="portrait" filters="role: phd" %}
{% include list.html data="members" component="portrait" filters="role: phd_associate" %}

# {% include icon.html icon="fa-solid fa-rocket" %}Alumni
{% include list.html data="members" component="portrait" filters="role: alumni" %}

# {% include icon.html icon="fa-solid fa-school" %}Visiting scholars and students

We had a pleasure of working with the following people:
- **Oliver Dietrich** from Saliba lab at the Helmholtz Institute Würzburg
- **Hao Yuan** from Kasper lab at the Karolinska Institute
- **Ana-Maria Cujba** from Teichmann Lab at the Welcome Sanger Institute
- **Janneke Hulsen** from Vrije Universiteit Amsterdam

{% include section.html background="images/team.jpg" dark=true align="center" %}

{% include section.html %}

# {% include icon.html icon="fa-solid fa-mountain" %}Beyond science

{% capture text %}

According to [our values](https://lueckenlab.github.io/org-website/#our-values), life and science should be not only productive, but also fun. And we are enjoying it along the way!

{% endcapture %}

{%
  include feature.html
  image="images/cutting-edge.png"
  title="On the cutting edge of research"
  style="bare"
  text=text
%}

{% capture text %}

Outside of working hours, we enjoy hiking, Christmas markets, and the beautiful Munich city. Once in a year, together with Theis lab, we organize a workshop where we all live and work together for a week, usually in the astonishing Alps. 

{% endcapture %}

{%
  include feature.html
  image="images/hiking-2023.png"
  title="Outside of the office"
  flip=true
  style="bare"
  text=text
%}
