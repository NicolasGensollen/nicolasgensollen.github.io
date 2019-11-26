---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% include base_path %}

This page gathers my main publications divided in categories (*Preprints*, *Articles published in international journals*, *Articles published in international conferences*, and *other publications*).

You can also find my articles on my [Google Scholar profile](https://scholar.google.fr/citations?user=4UsQKiwAAAAJ&hl=fr).

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
