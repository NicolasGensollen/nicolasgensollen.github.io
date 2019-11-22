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



Articles published in international journals
======

{% for post in site.journal_publications reversed %}
   {% include archive-single.html %}
{% endfor %}


Articles published in international conferences
======


{% for post in site.conference_publications reversed %}
  {% include archive-single.html %}
{% endfor %}

