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
{% include list.html data="members" component="portrait" filters="role: ^(?!pi$)(?!alumni$)" %}

# {% include icon.html icon="fa-solid fa-rocket" %}Alumni
{% include list.html data="members" component="portrait" filters="role: alumni" %}

# {% include icon.html icon="fa-solid fa-rocket" %}Visiting scholars and students

We had a pleasure of working with the following people:
- **Oliver Dietrich** from Saliba lab at the Helmholtz Institute Würzburg
- **Hao Yuan** from Kasper lab at the Karolinska Institute
- **Ana-Maria Cujba** from Teichmann Lab at the Welcome Sanger Institute
- **Janneke Hulsen** from Vrije Universiteit Amsterdam

{% include section.html background="images/team.jpg" dark=true align="center" %}

{% include section.html %}

{% capture content %}

{% comment %}
{% include figure.html image="images/photo.jpg" %}
{% include figure.html image="images/photo.jpg" %}
{% include figure.html image="images/photo.jpg" %}
{% endcomment %}

{% endcapture %}

{% include grid.html style="square" content=content %}
