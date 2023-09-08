---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

Xu J, **Goss DD**, Saliba SA. [A Novel Intrinsic Foot Muscle Strength Dynamometer Demonstrates Moderate-To-Excellent Reliability and Validity](https://doi.org/10.26603/001c.84310) <i> International Journal of Physical Therapy </i> (2023).
