---
layout: archive
title: ""
permalink: /publications/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

# Working Papers and Works in Progress
***

## Local Linearization Based Subvector Inference in Moment Inequality Models
Revised and Resubmitted, Journal of Econometrics, [Link](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=4227299)

**Abstract** This paper introduces a bootstrap-based profiling inference method for subvectors in moment inequality models following insights from Bugni et al. (2017). Compared to their paper, the new method calculates the critical value by searching over a local neighborhood of a pre-estimator, instead of the whole null parameter space, to profile out nuisance parameters. In this way, non-linear moment conditions are simplified by linear expansion and the bootstrap iterates over quadratic programming problems, which significantly simplifies and accelerates computation. This method controls asymptotic size uniformly over a large class of data generating processes. In the Monte Carlo simulations, the new procedure improves upon the computing time of Bugni et al. (2017) by a factor of up to 170 and Kaido et al. (2019) by a factor of up to 27. I provide an empirical illustration estimating an airline entry game.
