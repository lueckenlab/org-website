---
title: Home
---

# The Lücken Lab (also known as the Lucky lab) welcomes you to our site!

We build machine learning models on single-cell data and translate these to clinical applications predominantly in lung research. In particular, we focus on building cellular reference models of human tissues by integrating diverse single-cell datasets to improve the representation of human diversity. Using these reference models we are pioneering efforts to model patient variation, enable rapid analysis of new data, and work towards personlized medicine.

<!-- {%
  include figure.html
  image="https://avatars.githubusercontent.com/u/115151049?s=200&v=4"
  width="65%"
%} -->

{% include section.html %}

## Highlights

{% capture text %}

Our mission is to translate single-cell tools and machine learning methods to clinical applications, with a specific focus on atlases and pulmonary research. High standards in terms of robustness and reliability are set for methods used in clinical practice. To promote translatability of our methods, we aim to apply these standards throughout our single-cell work by promoting open, community-driven benchmarking.

{%
  include button.html
  link="research"
  text="See our publications"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}

{% endcapture %}

{%
  include feature.html
  image="images/scib.png"
  link="research"
  title="Our research"
  flip=true
  style="bare"
  text=text
%}

{% capture text %}

Our team welcomes highly motivated people from any background and any part of the world. We are a very colaborative and interactive group. We love to get together to talk about science, for coding sessions, or just to grab a drink during our breaks.

{%
  include button.html
  link="team"
  text="Meet our team"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}

{% endcapture %}

{%
  include feature.html
  image="images/team.jpg"
  link="team"
  title="Our Team"
  text=text
%}
