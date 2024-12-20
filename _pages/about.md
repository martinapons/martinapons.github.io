---
permalink: /
title: ""
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

Hey there! I’m a fifth-year Ph.D. Candidate in Economics at the <a href="https://www.vwi.unibe.ch/index_eng.html">Department of Economics</a> of the University of Bern. I am visiting the MIT economics department during the 2023-2024 academic year. My research interests are in quantile methods and panel data econometrics.  <a href="https://martinapons.github.io/files/CV_Martina_Pons.pdf" download>You can download my CV here</a>.


## Working Papers

### Quantile on Quantiles <small>[Job Market Paper]</small> <small>[<a href="/files/QQmodel.pdf" download>Download</a>]</small>
(_Winner of International Association for Applied Econometrics 2024 conference best student paper prize_)
<div style="height:  auto; width: auto;text-align: justify; line-height: 1.2" ><small>
Distributional effects provide interesting insight into how a given treatment impacts inequality. This paper extends this notion in two ways. First, it recognizes that inequality spans multiple dimensions, for example, within and between groups, with treatments potentially influencing and creating trade-offs between both. Second, the paper addresses the nontrivial challenge of ranking heterogeneous groups, which heavily depends on the social welfare function of the policymaker. 
To this end, I introduce a model to simultaneously study distributional effects within and between groups while remaining agnostic about this social welfare function. The model consists of a quantile function with two indices, the first capturing heterogeneity within groups and the second addressing the between-group dimension. 
I propose a two-step quantile regression estimator involving within-group regressions in the first stage and between-group regressions in the second stage. 
I show that the estimator is consistent and asymptotically normal when the number of observations per group and the number of groups diverge to infinity. In an empirical application, I study the effect of training on the distribution of firms' performance within and between markets in Kenya. The results show large positive effects among the successful firms in the best-performing markets, suggesting potential complementarities between firms and market performance.
</small><br><br/>
</div>

### Minimum Distance Estimation of Quantile Panel Data Models <small>[<a href="/files/MD.pdf" download>Download</a>]</small>  <small>[<a href="https://github.com/martinapons/mdqr" >R Package</a>]</small>  <small>[<a href="https://github.com/bmelly/Stata" download>Stata Package</a>]</small>  
<small>with <a href="https://sites.google.com/site/blaisemelly/">Blaise Melly</a></small>
<div style="height:  auto; width: auto;text-align: justify; line-height: 1.2" ><small>
We propose a minimum distance estimation approach for quantile panel data models where unit effects may be correlated with covariates. This computationally efficient method involves two stages: first, computing quantile regression within each unit, then applying GMM to the first-stage fitted values. Our estimators are applicable to (i) classical panel data, tracking units over time, and (ii) grouped data, where individual-level data are available, but treatment varies at the group level. Depending on the exogeneity assumptions, this approach provides quantile analogs of classic panel data estimators, including fixed effects, random effects, between, and Hausman-Taylor estimators. In addition, our method offers improved precision for grouped (instrumental) quantile regression compared to existing estimators. We establish asymptotic properties as both the number of units and observations per unit jointly diverge to infinity. Additionally, we introduce an inference procedure that automatically adapts to potentially unknown convergence rates of the estimators. Monte Carlo simulations demonstrate that our estimator and inference procedure perform well in finite samples, even when the number of observations per unit is moderate. In an empirical application, we examine the impact of the food stamp program on birth weights. Our findings reveal that the program's introduction increased birth weights predominantly at the lower end of the distribution, demonstrating our method's ability to capture heterogeneous effects across the outcome distribution.
</small><br><br/>
</div>

### The Apple Does Not Fall Far From the Tree: Intergenerational Persistence of Dietary Habits <small>[<a href="https://frederickluser.github.io/files/Intergenerational_Diet.pdf" download>Download</a>]</small>
<small>with <a href="https://frederickluser.github.io/">Frederic Kluser</a (Revise & Resubmit at _The Review of Economics and Statistics_)></small>

<div style="height:  auto; width: auto;text-align: justify; line-height: 1.2" ><small> 
Inadequate diets harm individual health, generate substantial healthcare costs, and reduce labor market income. Yet, the determinants of unhealthy eating remain poorly understood. This paper provides novel evidence on the intergenerational transmission of dietary choices from parents to children by exploiting unique grocery transaction records matched with administrative data. We document a strong intergenerational persistence of diet that exceeds income transmission across all measures we consider. At the same time, substantial heterogeneities in the persistence of diet indicate that the socioeconomic background and location of children may be crucial to fostering beneficial eating habits and breaking unhealthy ones. We discuss potential mechanisms and show in a counterfactual analysis that only 10\% of the intergenerational persistence in diet can be explained by the transmission of income and education. In line with these results, we introduce a habit formation model and argue that the formation of dietary habits during childhood and their slow alteration are key drivers of our findings.
</small><br><br/>
</div>


<iframe src="../files/income_3d.html" width="100%" height="600px" frameborder="0"></iframe>
**Footnote:** The Figure shows the effect of the business training on the within market and the between market distributions of income from work estimated using the method suggested in the paper _Quantiles on Quantile_ (see paper for details).

## Publications
<ul>{% for post in site.publications %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>


