---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if site.author.googlescholar %}
  <div class="wordwrap">You can also find a list of my articles on <a href="{{site.author.googlescholar}}">my Google Scholar profile</a>.</div>
{% endif %}



Computational Statistics
======


[Henderson, N.C. and R. Varadhan (2019).  Damped Anderson Acceleration with Restarts and Monotonicity Control for Accelerating EM and EM-like Algorithms. Journal of Computational and Graphical Statistics, 28(4), 834-846.](https://www.tandfonline.com/doi/abs/10.1080/10618600.2019.1594835)


Prostate Cancer
======

List several papers here


{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
