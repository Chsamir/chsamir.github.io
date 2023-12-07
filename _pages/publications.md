---
layout: archive
title: "Some recent publications"
permalink: /publications/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a> and PDF files
  <u><a href="[{{author.googlescholar}}](https://cv.hal.science/chafik-samir)"> on my HAL Science profile</a>.
  </u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
