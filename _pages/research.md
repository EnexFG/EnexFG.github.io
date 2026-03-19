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
  <p class="research-page__eyebrow">Current interests</p>
  <ul class="research-page__keywords">
    <li>Macroeconometrics and forecasting</li>
    <li>Bayesian methods</li>
    <li>High-frequency indicators</li>
    <li>Fiscal policy and oil-revenue shocks</li>
    <li>Dollarization and twin deficits</li>
    <li>Natural language processing</li>
    <li>Competition and simulation</li>
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
