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
* Economic damages due to extreme precipitation during tropical storms: evidence from Jamaica. 
This study investigates economic damage risk due to extreme rainfall during tropical storms in Jamaica. To this end, remote sensing precipitation data are linked to regional damage data for five storms. Extreme value modelling of precipitation is combined with an estimated damage function and satellite-derived nightlight intensity to estimate local risk in monetary terms. The results show that variation in maximum rainfall during a storm significantly contributes to parish level damages even after controlling for local wind speed. For instance, the damage risk for a 20 year rainfall event in Jamaica is estimated to be at least 238 million USD, i.e. about 1.5% of Jamaica’s yearly GDP.
Collalti, D., Strobl, E. Economic damages due to extreme precipitation during tropical storms: evidence from Jamaica. Nat Hazards (2021). https://doi.org/10.1007/s11069-021-05025-9 

Work in Progress
======
* B.Sc. Economics, University of Bern, 2013-2016.
* M.Sc. Applied Economic Analysis, University of Bern, 2016-2019.
* Ph.D. Economics & Climate Science, University of Bern, 2019-2023 (expected).







{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
