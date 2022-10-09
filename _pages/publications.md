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
* ***Empirical investigation on supervised machine learning models predicting firm-level monthly equity risk premium***
<br>
Abstract: Using US monthly data, we examine the performance of various supervised machine learning models' performance in forecasting multi-horizon firm-level equity risk premium. Following Gu, Kelly, and Xu (2020) we use a panel of firm-level US financial ratios and macroeconomic variables as common covariates. The big data spans from March 1957 to December 2019. First, using tests by Giacomini and White (2006) and Hansen (2005), we compare models to the benchmark of 0 forecast and examine out-of-sample fit. Among the models tested, we find that LASSO, random forest, and neural network provides good fit. Using test by Li, Liao, and Quaedvlieg (2020) we further the inference by testing for model superiority conditional on a state variable indicative of the state of the US economy during the out-of-sample periods. We observe that the difference among the models become smaller.


{% comment %} 
{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
{% endcomment %} 
