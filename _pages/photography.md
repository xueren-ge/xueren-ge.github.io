---
layout: archive
title: "Photography"
permalink: /photography/
author_profile: true
---

I'm working on the project "Cognitive Assistant Systems for Emergency Response". Our team collects electronic Patient Care Reports(ePCR) data on Emergency Medical Service (EMS) domain, we are utilizing the data to help build an end-to-end *Cognitive Assistant* to help support real-time, accurate decision making for first responders. We are also trying to incoporate domain knowledge into deep learning models to help first repsonders make real-time protocol selection in EMS domain. We're preparing a draft to publish the paper now.

<nbsp>

{% include base_path %}

{% assign ordered_pages = site.photography | sort:"order_number" %}

{% for post in ordered_pages %}
  <!-- {% include archive-single.html type="grid" %} -->
  {% include archive-single.html %}
{% endfor %}