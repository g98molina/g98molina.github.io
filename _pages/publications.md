---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% assign principal = site.publications | where: "role", "principal" | sort: "date" | reverse %}
{% assign coauthor = site.publications | where: "role", "coauthor" | sort: "date" | reverse %}

{% if principal.size > 0 %}
## First Author

{% for post in principal %}
  {% include archive-single.html %}
{% endfor %}
{% endif %}

{% if coauthor.size > 0 %}
## Co-author

{% for post in coauthor %}
  {% include archive-single.html %}
{% endfor %}
{% endif %}

{% if review.size > 0 %}
## Manuscripts under Review

{% for post in review %}
  {% include archive-single.html %}
{% endfor %}
{% endif %}
```
