---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

**Guneet S. Dhillon**, Pratik Chaudhari, Avinash Ravichandran, Stefano Soatto
**A Baseline for Few-Shot Image Classification** [PDF](https://arxiv.org/pdf/1909.02729.pdf) (2019)
*Short version in Proceedings of the Workshop on Meta-Learning, Conference on Neural Information Processing Systems (NeurIPS), 2019*

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
