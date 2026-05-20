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
PhD Student at Centre for Microbiome Research, Queensland University of Technology<br>
Master of Science (Agr.) in Plant Nutrition, China Agriculture University

#### Coordinates

Level 3 – Translational Research Institute<br>
37 Kent Street,<br>
Woolloongabba QLD 4102,<br>
Australia

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





