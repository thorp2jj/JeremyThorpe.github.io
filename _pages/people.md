---
header:
  image: 14650228_10153990079073857_8456241268632783500_n.jpg
layout: archive
title: "People"
permalink: /people/
author_profile: true
---


{% include base_path %}

{% for post in site.people %}
  {% include archive-single.html %}
{% endfor %}
