---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---

{% include base_path %}

{% assign published_papers = site.publications | where: "publication_status", "published" | sort: "date" | reverse %}
{% assign working_papers = site.publications | where: "publication_status", "working-paper" | sort: "date" | reverse %}

<div class="research-page">
  <div class="research-page__lead">
    <p>My research focuses on macroeconometrics, forecasting, and measurement. I am especially interested in how statistical and computational methods can be used to study real-time economic dynamics in data-constrained environments.</p>
    <p>I work mainly on empirical macroeconomics, Bayesian methods, high-frequency indicators, and natural language processing.</p>
  </div>

  <ul class="research-page__topics">
    <li>Macroeconomic forecasting and nowcasting</li>
    <li>Bayesian methods for macroeconomic analysis</li>
    <li>High-frequency economic measurement</li>
    <li>Fiscal policy and oil-revenue shocks</li>
    <li>Dollarization, external balance, and twin deficits</li>
    <li>Applied natural language processing</li>
    <li>Simulation and competition policy</li>
  </ul>
</div>

Working Papers
============

{% for post in working_papers %}
  {% include archive-single.html %}
{% endfor %}

Publications
==============

{% for post in published_papers %}
  {% include archive-single.html %}
{% endfor %}

{% if site.author.googlescholar %}
  <div class="wordwrap">A fuller list is also available on <a href="{{site.author.googlescholar}}">my Google Scholar profile</a>.</div>
{% endif %}
