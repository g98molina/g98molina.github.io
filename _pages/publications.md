---
layout: archive
title: "Publicaciones"
permalink: /publications/
author_profile: true
---

---
title: "Microscopic Insights into Magnetic Warping and Time-Reversal Symmetry Breaking in Topological Surface States of Rare-Earth-Doped Bi<sub>2</sub>Te<sub>3</sub>"
collection: publications
permalink: /publication/2009-10-01-paper-title-number-1
date: 04 November 2025
venue: 'Advanced Materials'
citation: ' '
paperurl: 'https://advanced.onlinelibrary.wiley.com/doi/10.1002/adma.202510877?utm_source=researchgate'
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
