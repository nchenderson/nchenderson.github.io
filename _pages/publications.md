---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

Prostate Cancer
======

List several papers here

Computational Statistics
======


{% if site.author.googlescholar %}
  <div class="wordwrap">You can also find my articles on <a href="{{https://scholar.google.com/citations?user=QTRX6BgAAAAJ&hl=en&oi=sra}}">my Google Scholar profile</a>.</div>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
