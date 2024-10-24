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
Distributional effects provide interesting insight into how a given treatment impacts inequality.
This paper extends this notion in two ways. First, it recognizes that inequality spans multiple dimensions, for example, within and between groups, with treatments potentially influencing both. Second, the paper addresses the nontrivial challenge of ranking heterogeneous groups, which heavily depends on the social welfare function of the policymaker. 
To this end, I introduce a model to simultaneously study distributional effects within and between groups while remaining agnostic about this social welfare function. The model consists of a quantile function with two indices, the first capturing heterogeneity within groups and the second addressing the between-group dimension. As a byproduct, the method proves valuable for descriptive analyses of inequalities within and between groups. 
I propose a two-step quantile regression estimator involving within-group regressions in the first stage and between-group regressions in the second stage. 
I show that the estimator is consistent and asymptotically normal when both the number of observations per group and the number of groups diverge to infinity. In an empirical application, I study the effect of training on the distribution of firms' performance within and between markets in Kenya. The results show large positive effects among the successful firms in the best-performing markets, suggesting potential complementarities between firms and market performance.
</small><br><br/>
</div>

### Minimum Distance Estimation of Quantile Panel Data Models <small>[<a href="/files/MD.pdf" download>Download</a>]</small>  <small>[<a href="https://github.com/martinapons/mdqr" >R Package</a>]</small>  <small>[<a href="https://github.com/bmelly/Stata" download>Stata Package</a>]</small>  
<small>with <a href="https://sites.google.com/site/blaisemelly/">Blaise Melly</a></small>
<div style="height:  auto; width: auto;text-align: justify; line-height: 1.2" ><small>
We propose a minimum distance estimation approach to quantile panel data models where the unit effects may be correlated with the covariates. The estimation method is computationally straightforward to implement and fast. We first compute a quantile regression within each unit and then apply GMM to the fitted values from the first stage. The suggested estimators apply (i) to grouped data, where we observe data at the individual level, but the treatment varies at the group level, and (ii) to classical panel data, where we follow the same units over time. Depending on the variables assumed to be exogenous, this approach provides quantile analogs of the classical least squares panel data estimators such as the fixed effects, random effects, between, and Hausman-Taylor estimators. We provide a more precise estimator for grouped (instrumental) quantile regression than the existing ones. We establish the asymptotic properties of our estimator when the number of units and observations per unit jointly diverge to infinity. We suggest an inference procedure that automatically adapts to the (potentially) unknown rate of convergence of the estimators. Monte Carlo simulations show that our estimator and inference procedure also perform well in finite samples when the number of observations per unit is small. In an empirical application, we find that the introduction of the food stamp program increased the birth weights only at the bottom of the distribution.
</small><br><br/>
</div>

### The Apple Does Not Fall Far From the Tree: Intergenerational Persistence of Dietary Habits <small>[<a href="https://frederickluser.github.io/files/Intergenerational_Diet.pdf" download>Download</a>]</small>
<small>with <a href="https://frederickluser.github.io/">Frederic Kluser</a></small>
<div style="height:  auto; width: auto;text-align: justify; line-height: 1.2" ><small>
Inadequate diets harm individual health, generate substantial healthcare costs, and reduce labor market income. Yet, the determinants of unhealthy eating habits remain poorly understood. We provide novel evidence of the strong intergenerational transmission of dietary choices from parents to children by exploiting unique grocery transaction records matched with administrative data. We find that children with parents spending one percentage point more on fruits and vegetables also spend 0.23 percentage points more on fresh produce.
Our estimates exceed comparable measures for income transmission, indicating that dietary habits acquired during childhood are particularly persistent.
Counterfactual analyses show that only 12% of the intergenerational persistence in diet can be explained by the transmission of income and education. Finally, we find substantial heterogeneities in diet transmission and introduce a habit formation model to discuss potential mechanisms.
</small><br><br/>
</div>


<iframe src="../files/income_3d.html" width="100%" height="600px" frameborder="0"></iframe>
**Footnote:** The Figure shows the effect of the business training on the within market and the between market distributions of income from work estimated using the method suggested in the paper _Quantiles on Quantile_ (see paper for details).

## Publications
<ul>{% for post in site.publications %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>


