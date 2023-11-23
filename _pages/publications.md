---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% include base_path %}

You can also find my articles on <u><a href="{{author.ads}}">ads</a>,</u> <u><a href="{{author.arxiv}}">arXiv</a>,</u> and <u><a href="{{author.googlescholar}}">Google Scholar profile</a>.</u>


  <li style="font-size:1.em"> Cho et. al. 2023 "Bridging Scales in Black Hole Accretion and Feedback: Magnetized Bondi Accretion in 3D GRMHD" </li>
  <li style="font-size:1.em">Cho and Narayan 2022 ApJ, 932, “Analytical Model of Disk Evaporation and
State Transitions in Accreting Black Holes”</li>
  <li style="font-size:1.em">Cho et. al. 2020 ApJL, 891, “Spectropolarimetric analysis of FRB 181112
at microsecond resolution: Implications for Fast Radio Burst emission mechanism”</li>
  


{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
