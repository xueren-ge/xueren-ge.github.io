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
  <h3>{{ post.title }}</h3>
  <p><strong>Venue:</strong> {{ post.venue }}</p>
  <p>{{ post.date | date: "%B %d, %Y" }}</p>
  {% if post.link %}
    <a href="{{ post.link }}">Read paper</a>
  {% endif %}
  {% if post.github %}
    <a href="{{ post.github }}">Code</a>
  {% endif %}
  <p><strong>Citation:</strong> {{ post.citation }}</p>
{% endfor %}

<sup>*</sup> Equal authorship