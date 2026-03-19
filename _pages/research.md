---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---

This page gathers selected publications and working papers at the intersection of macroeconometrics, forecasting, fiscal policy, and applied quantitative methods.

My research is motivated by live decision problems: how to measure the economy in real time, identify policy effects, and design useful tools under uncertainty.

Current Themes
==============

* Macroeconomic forecasting and nowcasting
* Fiscal policy and oil-revenue shocks
* Dollarization, external balance, and twin deficits
* Applied NLP and high-frequency measurement
* Simulation and competition policy

{% if site.author.googlescholar %}
  <div class="wordwrap">A fuller list is also available on <a href="{{site.author.googlescholar}}">my Google Scholar profile</a>.</div>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
