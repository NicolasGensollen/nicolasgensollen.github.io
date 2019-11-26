---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% include base_path %}

{% if author.googlescholar %}
  <p>You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u></p>
{% endif %}

## Preprints

{% for post in site.preprints reversed %}
	{% include archive-single.html %}
{% endfor %}

## Articles published in international journals

{% for post in site.journal_publications reversed %}
   {% include archive-single.html %}
{% endfor %}

## Articles published in international conferences

{% for post in site.conference_publications reversed %}
  {% include archive-single.html %}
{% endfor %}

## Other publications

### PhD thesis

{% for post in site.thesis reversed %}
  {% include archive-single.html %}
{% endfor %}
