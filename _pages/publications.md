---
layout: archive
title: "Publicaciones"
permalink: /publications/
author_profile: true
---

{% assign principal = site.publications | where: "role", "principal" | sort: "date" | reverse %}
{% assign coautor = site.publications | where: "role", "coautor" | sort: "date" | reverse %}

{% if principal.size > 0 %}
## Autor principal

{% for post in principal %}
  {% include archive-single.html %}
{% endfor %}
{% endif %}

{% if coautor.size > 0 %}
## Coautor

{% for post in coautor %}
  {% include archive-single.html %}
{% endfor %}
{% endif %}

## Manuscripts under review

- **First-Principles Insights into N₂H₄-Assisted Exfoliation of CuₓTiSe₂**

  *Under review*
