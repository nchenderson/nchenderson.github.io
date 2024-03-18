---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---


{% if site.author.googlescholar %}
  <div class="wordwrap">You can also find a list of articles on <a href="{{site.author.googlescholar}}">my Google Scholar profile</a>.</div>
{% endif %}



Computational Statistics
======

1. Henderson, N.C. and R. Varadhan (2019). [Damped Anderson Acceleration with Restarts and Monotonicity Control for Accelerating EM and EM-like Algorithms.](https://www.tandfonline.com/doi/abs/10.1080/10618600.2019.1594835) Journal of Computational and Graphical Statistics, 28(4), 834-846.

2. Henderson, N.C. and P.J. Rathouz (2018). [AR(1) Latent Class Models for Longitudinal Count Data.](https://onlinelibrary.wiley.com/doi/abs/10.1002/sim.7931) Statistics in Medicine, 37, 4441-4456.

3. McDaniel, L.S., Henderson, N.C., and P.J. Rathouz (2013). [Fast Pure R Implementation of GEE: Application of the Matrix Package.](https://journal.r-project.org/archive/2013-1/mcdaniel-henderson-rathouz.pdf) The R Journal, 5(1), 181-188.

4. Henderson, N.C. and Z. Ouyang. [Parameter-expanded ECME algorithms for Logistic and Penalized Logistic Regression.](https://arxiv.org/abs/2304.03904) ArXiv preprint.


Prostate Cancer
======



{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
