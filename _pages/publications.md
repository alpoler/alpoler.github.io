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




<table>
<tr>
 <td valign="center"><img width="400" src="https://github.com/alpoler/alpoler.github.io/blob/master/images/a.JPG" /></td> 
  <td valign="center"> Elimination of Non-Novel Segments at Multi-Scale for Few-Shot Segmentation <br \> 
    Alper Kayabaşı, Gülin Tüfekci, İlkay Ulusoy <br \>
    Winter Conference on Applications of Computer Vision (WACV), 2023 <a href = https://arxiv.org/pdf/2211.02300.pdf> PDF </a> 
  </td> 
</tr>
<tr>
  <td valign="center"> <img width="400" src="https://github.com/alpoler/alpoler.github.io/blob/master/images/arch.png" /> </td> 
  <td> Detecting Driver Drowsiness as an Anomaly Using LSTM Autoencoders 
    <br \>  Gülin Tüfekci*, Alper Kayabaşı*, Erdem Akagündüz, İlkay Ulusoy 
    <br \>    ISM Workshop @ European Conference on Computer Vision (ECCV), 2022 <a href= "https://arxiv.org/abs/2209.05269">PDF</a> <br \>(*Equal Contribution) 
  </td>

<tr>
 <td valign="center"> <img width="400" src="https://github.com/alpoler/alpoler.github.io/blob/master/images/d.JPG" /> </td> 
 <td> Comparison of distance metric learning methods against label noise for fine-grained recognition
    <br \>  Alper Kayabaşı, Kaan Karaman, Ibrahim Batuhan Akkaya
    <br \> Automatic Target Recognition XXXI @ Society of Photo-Optical Instrumentation Engineers (SPIE), 2021 <a href= "https://www.spiedigitallibrary.org/conference-proceedings-of-spie/11729/117290F/Comparison-of-distance-metric-learning-methods-against-label-noise-for/10.1117/12.2587246.short?SSO=1">PDF</a>
  </td>
</tr>
</table>


