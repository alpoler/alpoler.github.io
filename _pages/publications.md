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

Alper Kayabaşı, Gülin Tüfekci, İlkay Ulusoy. **Elimination of Non-Novel Segments at Multi-Scale for Few-Shot Segmentation**, in Winter Conference on Applications of Computer Vision (WACV), 2023 ([PDF](https://arxiv.org/abs/2211.02300))

Gülin Tüfekci<sup>\*</sup>, Alper Kayabaşı<sup>\*</sup>, Erdem Akagündüz, İlkay Ulusoy. **Detecting Driver Drowsiness as an Anomaly Using LSTM Autoencoders**, in  In-Vehicle Sensing and Monitorization Workshop @ European Conference on Computer Vision (ECCV), 2022 ([PDF](https://arxiv.org/abs/2209.05269)), (*Equal Contribution)


Alper Kayabaşı, Kaan Karaman, Ibrahim Batuhan Akkaya. **Comparison of distance metric learning methods against label noise for fine-grained recognition**, in Automatic Target Recognition XXXI @ Society of Photo-Optical Instrumentation Engineers (SPIE), 2021 ([PDF](https://www.spiedigitallibrary.org/conference-proceedings-of-spie/11729/117290F/Comparison-of-distance-metric-learning-methods-against-label-noise-for/10.1117/12.2587246.short?SSO=1))
