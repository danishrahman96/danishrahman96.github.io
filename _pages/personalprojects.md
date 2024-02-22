---
layout: archive
title: "Personal Projects"
permalink: /personalprojects/
author_profile: true
---

This is a list of personal projects that I have completed over the past few years. Please feel free to click on each of them for more information, references and papers relevant to them.

{% include base_path %}

{% for post in site.personalprojects %}
  {% include archive-single.html %}
{% endfor %}
