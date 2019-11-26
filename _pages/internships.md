---
layout: archive
title: "Internships"
permalink: /internships/
author_profile: true
---

{% include base_path %}

You can find here a list of available interships I am supervising. Feel free to contact me if you are interested in one of them or if you wish to discuss a project you have in mind!

More opportunities can also be found on the [complex networks job page](http://www.complexnetworks.fr/projects/).

## Current offers

{% for post in site.internships reversed %}
	{% include archive-single.html %}
{% endfor %}

## Past students

* __Lester Padilla__
	* *Paris-Saclay University and Versailles St-Quentin-en-Yvelines University, April 2016 - September 2016*
	* Master thesis: Reconstructing the European Power Grid from OpenstreetMap data
	* Co-supervised with Vincent Gauthier
