---
title: "About"
layout: gridlay
sitemap: false
permalink: /about/
---

## About

<div class="jumbotron">
<div class="row">
<div class="col-sm-4">
<center>
<img src="{{ site.url }}{{ site.baseurl }}/images/headshot.jpg" width="200"/>
</center>
</div>
<div class="col-sm-8 col-xs-12">
<h2>
Xi ZHOU
</h2>
Master of Science (Agr.) in Plant Nutrition<br>
China Agriculture University (CAU), P. R. China


#### Coordinates

19 Science Park West Avenue, Hong Kong Science Park<br>
Pak Shek Kok, New Territories, Hong Kong SAR

<img width="468" height="37" alt="image" src="https://github.com/user-attachments/assets/aec022ac-ae6b-426f-9288-1a575a2187c1" />


<div>
{% for member in site.data.pi %}
  {% if member.email %}<a href="mailto:{{ member.email }}" target="_blank"><i class="fa fa-envelope-square fa-3x"></i></a> {% endif %}
  {% if member.cv %} <a href="{{ member.cv }}" target="_blank"><i class="ai ai-cv-square ai-3x"></i></a> {% endif %}
  {% if member.linkedin %} <a href="{{ member.linkedin }}" target="_blank"><i class="fa fa-linkedin-square fa-3x"></i></a> {% endif %}
  {% if member.twitter %} <a href="{{ site.url }}{{ site.baseurl }}/{{ member.twitter }}" target="_blank"><i class="fa fa-twitter-square fa-3x"></i></a> {% endif %}
  {% if member.github %} <a href="{{ member.github }}" target="_blank"><i class="fa fa-github-square fa-3x"></i></a> {% endif %}
  {% if member.researchgate %} <a href="{{ member.researchgate }}" target="_blank"><i class="ai ai-researchgate-square ai-3x"></i></a>{% endif %} {% endfor %}
</div>
</div>
</div>
</div>



