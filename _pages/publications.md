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






<br>

# Working Papers
***

## Inference on Union Bounds 
[Link](https://xinyuebei-econ.github.io/files/UnionBD.pdf), [R package](https://github.com/xinyuebei-econ/UnionBounds/tree/main), [Matlab](https://github.com/xinyuebei-econ/Union-Bounds---Matlab-Replication), latest draft: 2024

**Abstract** A union bound is a union of multiple bounds. Union bounds occur in a wide variety of empirical settings, such as difference-in-differences, regression discontinuity design, bunching, and misspecification analysis. In this paper, I propose a confidence interval for these kinds of bounds based on modified conditional inference. I show that it improves upon existing methods in a large set of data generating processes. The new procedure gives statistically significant results while the pre-existing alternatives do not in the empirical applications in Dustmann, Lindner, Schönberg, Umkehrer, and Vom Berge (2022).

Partially supersedes my [JMP](https://xinyuebei-econ.github.io/files/Bei_Xinyue_JMP.pdf)

## Hypothesis Tests with a Repeatedly Singular Information Matrix 
with [Dante Amengual](https://www.cemfi.es/~amengual/) and [Enrique Sentana](https://www.cemfi.es/~sentana/),  latest draft: 2023 [Link](https://www.cemfi.es/~sentana/es/Singular2305.pdf) 


**Abstract** We study score-type tests in likelihood contexts in which the nullity of the information matrix under the null is greater than one, thereby generalizing existing results in the literature. Examples include multivariate regressions with sample selectivity, semi-nonparametric distributions, Hermite expansions of Gaussian copulas, and purely non-linear predictive regressions among others. Our proposal, which involves higher-order derivatives, is asymptotically equivalent to the likelihood ratio test but only requires estimation under the null, a substantial advantage for resampling-based inference. We conduct extensive Monte Carlo exercises to study the finite sample size and power properties of our proposal, comparing it to alternative approaches.


<br>

# Publications
***

## Local Linearization Based Subvector Inference in Moment Inequality Models
_Journal of Econometrics_, 2024 [Link](https://www.sciencedirect.com/science/article/pii/S0304407623002658), [SSRN](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=4475065), [Code](https://github.com/xinyuebei-econ/Local-Linearization)

**Abstract** This paper introduces a bootstrap-based profiling inference method for subvectors in moment inequality models following insights from Bugni et al. (2017). Compared to their paper, the new method calculates the critical value by searching over a local neighborhood of a pre-estimator, instead of the whole null parameter space, to profile out nuisance parameters. In this way, non-linear moment conditions are simplified by linear expansion and the bootstrap iterates over quadratic programming problems, which significantly simplifies and accelerates computation. This method controls asymptotic size uniformly over a large class of data generating processes. In the Monte Carlo simulations, the new procedure improves upon the computing time of Bugni et al. (2017) and Kaido et al. (2019) significantly. I provide an empirical illustration estimating an airline entry game.

## Score-type Tests for Normal Mixtures
with [Dante Amengual](https://www.cemfi.es/~amengual/), [Marine Carrasco](https://sceco.umontreal.ca/english/department-directory/professors/professor/in/in15211/sg/Marine%20Carrasco/), and [Enrique Sentana](https://www.cemfi.es/~sentana/) \
_Journal of Econometrics_, 2024 [Link](https://www.sciencedirect.com/science/article/pii/S0304407624000630?casa_token=gU1E_esPGeAAAAAA:LfFUzeXkdRKviRk9FN2j6f5hBfRw1m3fV8j9MokuelRX5AxNebbhPjocEeq44MS_REDUXvtv) 


**Abstract** Testing normality against discrete normal mixtures is complex because some parameters turn increasingly underidentified along alternative ways of approaching the null, others are inequality constrained, and several higher-order derivatives become identically 0. These problems make the maximum of the alternative model log-likelihood function numerically unreliable. We propose score-type tests asymptotically equivalent to the likelihood ratio as the largest of two simple intuitive statistics that only require estimation under the null. One novelty of our approach is that we treat symmetrically both ways of writing the null hypothesis without excluding any region of the parameter space. We derive the asymptotic distribution of our tests under the null and sequences of local alternatives. We also show that their asymptotic distribution is the same whether applied to observations or standardized residuals from heteroskedastic regression models. Finally, we study their power in simulations and apply them to the residuals of Mincer earnings functions.

## Highly Irregular Serial Correlation Tests
with [Dante Amengual](https://www.cemfi.es/~amengual/) and [Enrique Sentana](https://www.cemfi.es/~sentana/) \
_Econometrics and Statistics_, 2024 [Link](https://www.sciencedirect.com/science/article/abs/pii/S2452306224000017) 


**Abstract** We develop tests for neglected serial correlation when the information matrix is repeatedly singular under the null. Specifically, we consider white noise against a multiplicative seasonal AR model, and a local-level model against a nesting UCARIMA one. Our proposals, which involve higher-order derivatives, are asymptotically equivalent to the likelihood ratio test but only require estimation under the null. Remarkably, we show that our proposed tests effectively check that certain autocorrelations of the observations are 0 , so their asymptotic distribution is standard. We conduct Monte Carlo exercises that study their finite sample size and power properties, comparing them to alternative approaches.

## Normal But Skewed?
with [Dante Amengual](https://www.cemfi.es/~amengual/) and [Enrique Sentana](https://www.cemfi.es/~sentana/) \
_Journal of Applied Econometrics_, 2022 [Link](https://onlinelibrary.wiley.com/doi/abs/10.1002/jae.2927)

**Abstract** We propose a multivariate normality test against skew normal distributions using higher-order log-likelihood derivatives, which is asymptotically equivalent to the likelihood ratio but only requires estimation under the null. Numerically, it is the supremum of the univariate skewness coefficient test over all linear combinations of the variables. We can simulate its exact finite sample distribution for any multivariate dimension and sample size. Our Monte Carlo exercises confirm its power advantages over alternative approaches. Finally, we apply it to the joint distribution of US city sizes in two consecutive censuses finding that non-normality is very clearly seen in their growth rates.
