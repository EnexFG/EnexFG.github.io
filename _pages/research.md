---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---

My research focuses on macroeconometrics, forecasting, and measurement. I am especially interested in how statistical and computational methods can be used to study real-time economic dynamics in data-constrained environments.

I work mainly on empirical macroeconomics, Bayesian methods, high-frequency indicators, and natural language processing, with applications to fiscal policy, external balance, and competition.

{% include base_path %}

Research Areas
==============

* Macroeconomic forecasting and nowcasting
* Bayesian methods for macroeconomic analysis
* High-frequency economic measurement
* Fiscal policy and oil-revenue shocks
* Dollarization, external balance, and twin deficits
* Applied natural language processing
* Simulation and competition policy

Selected Work
=============

[`Tracking the economy at high frequency`]({{ base_path }}/research/2025-07-10-paper-title-number-3)

Develops a Bayesian mixed-frequency framework for measuring economic activity in real time and estimating pseudo-weekly recession probabilities in a data-constrained economy.

[`Good policy or good luck? Analyzing the effects of fiscal policy and oil revenue shocks in Ecuador`]({{ base_path }}/research/2021-08-01-paper-title-number-2)

Studies the macroeconomic effects of fiscal policy and oil-revenue shocks in Ecuador using Bayesian structural vector autoregressions.

[`Looking for the Twin Deficits in a Dollarized Oil-Exporting Economy`]({{ base_path }}/research/2025-07-10-paper-title-number-4)

Examines how fiscal shocks and oil revenues affect the trade balance and the real exchange rate in a dollarized, oil-exporting economy.

[`Collusive networks in market-sharing agreements: An agent-based simulation`]({{ base_path }}/research/2025-08-20-paper-title-number-5)

Uses an agent-based network model to study market-sharing agreements, entry conditions, and the stability of collusive structures under different competitive settings.

{% if site.author.googlescholar %}
  <div class="wordwrap">A fuller list is also available on <a href="{{site.author.googlescholar}}">my Google Scholar profile</a>.</div>
{% endif %}

Publications
============

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
