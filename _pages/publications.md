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

Alper Kayabaşı, Gülin Tüfekci, İlkay Ulusoy. Elimination of Non-Novel Segments at Multi-Scale for Few-Shot Segmentation, in Winter Conference on Applications of Computer Vision (WACV), 2023 ([PDF](https://arxiv.org/abs/2211.02300))
