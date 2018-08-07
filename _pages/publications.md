---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
header:
  image: Mosaic_Brain_resize25.jpg
---


  My publications: [my Google Scholar profile](https://scholar.google.com/citations?user=ug8CnQUAAAAJ&hl=en){: .btn .btn--success}


{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
