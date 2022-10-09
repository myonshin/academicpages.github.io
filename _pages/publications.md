---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles at <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

<span style="color:blue">Working papers</span>
======
* ***Empirical investigation on supervised machine learning models predicting firm-level\\\hspace{29pt} monthly equity risk premium***
<br>E671 Econometrics 3, Spring 2022



{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
