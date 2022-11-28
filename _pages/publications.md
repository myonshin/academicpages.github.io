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
* ***Empirical investigation on supervised machine learning models predicting equity risk premium<br>(Job market paper, [Current manuscript](https://myonshin.github.io/files/CHAP_1.pdf), last update November 2022)***
<br>
Abstract: We examine the performance of supervised machine learning models in forecasting multi-horizon firm-level equity risk premium. A large collection of individual firms' financial characteristics and US macroeconomic predictors for returns from January 1960 to December 2019 are used. We forecast excess returns for (1) all individual firms and for (2) each group of firms belonging to the same industry sector in US. We first show out-of-sample fit for each forecast model. Second, we forecast evaluate models to find ones with superior predictive ability and are included in model confidence sets. Finally we test for conditional superior predictive ability of a model, where a model's CSPA is conditional on a priori chosen variable indicative of the state of the market. 
<br>
<br>
Keywords: Big Data, Supervised Machine Learning, Return predictability, Forecast evaluation
<br>
<br>

{% comment %} 
{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
{% endcomment %} 
