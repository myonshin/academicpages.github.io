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
* ***Empirical investigation on supervised machine learning models predicting equity risk premium<br>(Job market paper, [Current manuscript](https://myonshin.github.io/files/CHAP_1.pdf), last update Nov 18 2022)***
<br>
Abstract: We examine the performance of supervised machine learning models in forecasting multi-horizon firm-level equity risk premium. US monthly data from Gu, Kelly, and Xiu (2020), a panel of firm-level US financial characteristics and macroeconomic predictors from March 1957 to December 2016 is used. To access performance we first test for equal predictive ability model pairs and check their out-of-sample fit. Second, we compare across all models jointly and find the model with superior predictive ability. Finally we test for conditional superior predictive ability(CSPA) across models jointly, where a model’s CSPA is conditional on a prior chosen state variable. Among the models tested, we find that generally, partial least squares and random forest have SPA and CSPA over other models.
<br>
<br>
Keywords: Big Data, Supervised Machine Learning, Return predictability, Forecast evaluation
<br>
<br>


Evaluation of supervised machine learning methods predicting South Korea equity risk premium(working)

Using South Korea monthly data, we examine the performance of various supervised machine learning models in forecasting monthly firm-level equity risk premium. We collect firms  in Korea Exchange from January 1990 to December 2019 and get their excess stock returns and predictors through Worldscope. Using tests by Giacomini and White (2006), Hansen, Lunde, and Nason (2011), and Hansen (2005), we compare across models and find the model with superior predictive ability. With our data, we find that LASSO, partial least squares, and random forest show superior predictive best predictive ability.





{% comment %} 
{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
{% endcomment %} 
