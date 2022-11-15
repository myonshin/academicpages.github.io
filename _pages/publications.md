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

<span style="color:orange">Working papers</span>
======
* ***Empirical investigation on supervised machine learning models predicting equity risk premium(Job market paper)***
<br>
Abstract: Using US monthly data, we examine the performance of various supervised machine learning models in forecasting multi-horizon firm-level equity risk premium. Following Gu, Kelly, and Xiu (2020), we use a panel of firm-level US financial characteristics and macroeconomic predictors from March 1957 to December 2016. First, using tests by Giacomini and White (2006), Hansen, Lunde, and Nason (2011), and Hansen (2005), we compare across models and find the model with superior predictive ability. Additionally, we test for conditional superior predictive ability across models using the test by Li, Liao, and Quaedvlieg (2022). Superior predictive ability of a model is conditional on scalar state variable during prediction periods. Among the models tested, we find that generally, partial least squares and random forest show best predictive ability. 
<br>
<br>
Keywords: Big Data, Supervised Machine Learning, Return predictability, Forecast evaluation
<br>
<br>
[Current menuscript](https://myonshin.github.io/files/Syllabus_Fall2021_M524.pdf)
{% comment %} 
{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
{% endcomment %} 
