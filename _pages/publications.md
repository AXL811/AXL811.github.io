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
1. A Study of the Emotional Capability of Internet Platforms (Graduate dissertation, with Yidi Guo)

2. Deriving and Testing a Cobb-Douglas Valuation Function of Internet Platform Companies

3. Is Trade Policy Uncertainty Pushing Chinese Companies to Innovate?  (with Kun Lang, Lin Fu, Qi Kang)

4. The dynamics of global value chain with a focus on the automobile industry (supervised by Brian Wu)
