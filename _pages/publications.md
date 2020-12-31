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

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

Preprints
=========
---
title: "On transfer learning for chatter detection in turning using wavelet packet transform and ensemble empirical mode decomposition"
collection: publications
date: 2019-5-21
venue: 'arXiv'
---

[Learn more](https://doi.org/10.1016/j.cirpj.2019.11.003)