---
layout: archive
title: "Research"
excerpt: "These are the topics that, I had chance to work on during my Bachelor studies."
permalink: /research/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.research reversed %}
  {% include archive-single.html %}
{% endfor %}

* [Graphene Applications](http://www.nanobees.web.tr/en/research/graphene/applications)
* [Graphene Device Characterization](http://nanobees.fizik.itu.edu.tr/en/facilities/devicecharacterization)
* [Lock-in Theory for Scanning Tunneling Spectroscopy](http://haltugyildirim.github.io/files/lock-in.pdf)
