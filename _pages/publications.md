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

Work in Progress
======
1. A Study Emotion Management of Internet Social Platforms (with Yidi Guo)

2. Free Private Strategy and Open-Source Contributions: Evidence from GitHub (with Di Zhou, Jiawei Chen)

3. Deriving and Testing a Cobb-Douglas Valuation Function of Internet Platform Companies

4. Is Trade Policy Uncertainty Pushing Chinese Companies to Innovate?  (with Kun Lang, Lin Fu, Qi Kang)
