---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

My publications in peer-reviewed journals are listed on this page. A plain English summary is provided for all of them. 

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
