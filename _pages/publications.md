---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}


Publications
======
* The Impact of Air Pollution on Birthweight: Evidence from Grouped Quantile Regression

Estimates of the average effect of pollution on birthweight might not provide a complete picture if more vulnerable infants are disproportionately more affected. To address this, I focus on the distributional effect of particulate matter pollution (PM2.5) on birthweight. To estimate the impact, this paper uses grouped quantile regression, a methodology developed by Chetverikov et al. (2016), which allows estimating the impact of a group-level treatment on an individual-level outcome when there are group-level unobservables. The analysis reveals nonhomogeneous effects indicating that pollution disproportionately affects infants in the lower tail of the conditional distribution, whereas average effects suggest only minimal and not economically significant impact of pollution on birthweight. The findings are also consistent across different specifications. https://doi.org/10.1007/s00181-021-02048-w





{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
