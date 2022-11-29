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
Abstract: We examine the predictive performance of supervised machine learning models in forecasting multi-horizon firm-level equity risk premium. We use an extensive collection of individual firms' financial characteristics and US macroeconomic return predictors for data. We forecast excess returns for (1) all individual firms and (2) each group of firms belonging to the same industry sector in the US. We first show an out-of-sample fit for each forecast model. Second, we forecast and evaluate models pairwise to find ones with superior predictive ability. We also estimate model confidence sets collecting models with superior predictive ability. Finally, we test for a model's conditional superior predictive ability, where a model's predictive ability is determined conditionally on a priori chosen variable indicative of the state of the market.	
<br>
<br>
Keywords: Big Data, Supervised Machine Learning, Return predictability, Forecast evaluation
<br>
<br>
<br>
<br>

<!---
* ***Evaluation of supervised machine learning methods predicting equity risk premium in South Korea<br>(working)***
<br>
Abstract: We examine the predictive performance of supervised machine learning models in forecasting monthly firm-level equity risk premium for stocks currently listed on Korea Exchange or have been listed in the past. We collect firms from January 1990 to December 2019 through Worldscope database and use their financial characteristics as predictors. We forecast returns from January 2005 to December 2019 and test models for superior predictive ability and construct model confidence sets to evaluate forecasts. We also calculate the importance of predictors based on their mean decrease in l2 impurity using the random forest model. We find that for our data, weekly price trend and monthly price trend contribute the most.
-->
{% comment %} 
{% for post in site.publications reversed %}





  {% include archive-single.html %}
{% endfor %}
{% endcomment %} 
