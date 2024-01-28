---
layout: archive
title: "Teaching"
permalink: /teaching/
author_profile: true
---

{% include base_path %}

##Teaching assistant:

* CS 3281 (Principles Operating Systems) - Fall 2022
* CS 3891/5891 (Numerical Methods) - Fall 2023
* CS 3891/5891 (Quantum Computing) - Spring 2024

{% for post in site.teaching reversed %}
  {% include archive-single.html %}
{% endfor %}
