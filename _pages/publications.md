---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

You can also find my articles on <u><a href="{author.ads}">ads</a>,</u> <u><a href="{author.arxiv}">arXiv</a>,</u> and <u><a href="{author.googlescholar}">Google Scholar profile</a>.</u>


  <li style="font-size:1.em"> 10/2023 Bridging Scales in Black Hole Accretion and Feedback: Magnetized Bondi Accretion in 3D GRMHD </li>
  <li style="font-size:1.em">Fall 2021: Harvard AY200 Radiative Processes in Astrophysics (graduate course)</li>
  <li style="font-size:1.em">Fall 2019: GIST MM4016 Introduction to Topology (4th-year course)</li>
  <li style="font-size:1.em">Spring 2018: GIST PS3101 Electromagnetism II (3rd-year course)</li>
  

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
