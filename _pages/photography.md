---
layout: archive
title: "Photography"
permalink: /photography/
author_profile: true
---

Photos taken by me :>

<nbsp>

{% include base_path %}

{% assign ordered_pages = site.photography | sort:"order_number" %}

{% for post in ordered_pages %}
  <!-- {% include archive-single.html type="grid" %} -->
  {% include archive-single.html %}
{% endfor %}