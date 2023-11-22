---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

You can also find my articles on <u><a href="{{author.ads}}">ads</a>,</u> <u><a href="{{author.arxiv}}">arXiv</a>,</u> and <u><a href="{{author.googlescholar}}">Google Scholar profile</a>.</u>

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
