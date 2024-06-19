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
1. How to Win the EV Competition? (supervised by Brian Wu)

2. How Local Governments Respond to Conflicting Targets (ready for submission, with (Lang Kun)[www.langkunprc.com])
  
3. A Study of the Emotional Capability of Internet Platforms (Graduate dissertation, with Yidi Guo)

4. Deriving and Testing a Cobb-Douglas Valuation Function of Internet Platform Companies


