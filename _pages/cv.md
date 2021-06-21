---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

This page provides an online version on my resume. In addition, you can download my resume as a PDF file in two different formats:

* __Academic version__
  * [English](tba) *Currently not available...*
  * [French](https://nicolasgensollen.github.io/files/academic-resume-french-nicolas-gensollen.pdf)
* __Short version__
  * [English](https://nicolasgensollen.github.io/files/short-resume-english-nicolas-gensollen.pdf)
  * [French](tba) *Currently not available...*

----------

# Education

## Ph.D in Computer Science, 2016
  
* __Delivered by__: [Telecom SudParis](https://www.telecom-sudparis.eu/), Evry, France
* __Scholarship__: Awarded by the *Pierre and Marie Curie University* (UPMC, now *Sorbonne University*)
* __Supervisors__: Michel Marot, Monique Becker, Vincent Gauthier
* __Defense date__: October 7th 2016
* __Defense jury__:
  * [Matthieu Latapy](https://www-complexnetworks.lip6.fr/~latapy/), LIP6, *president*
  * [André-Luc Beylot](http://irt.enseeiht.fr/beylot/), ENSEEIHT, *rapporteur*
  * [Jean-Guy Caputo](http://lmi2.insa-rouen.fr/~jgcaputo/), INSA Rouen, *rapporteur*
  * [Frederica Darema](https://www.af.mil/About-Us/Biographies/Display/Article/108635/dr-frederica-darema/), AFSOR
  * [Slawomir Pietrasz](https://fr.linkedin.com/in/slawomir-pietrasz-89a73a5/de), ENGIEE
  * [Michel Marot](http://www-public.imtbs-tsp.eu/~marot/), Telecom SudParis
  * [Monique Becker](https://www.researchgate.net/profile/Monique_Becker), Telecom SudParis
  * [Vincent Gauthier](https://complex.luxbulb.org/), Telecom SudParis

## Engineer degree in Telecommunications, 2012
  
* __Delivered by__: [Telecom SudParis](https://www.telecom-sudparis.eu/), Evry, France
* __Last year option__: Services and Infrastructure convergence (CSI)
* __Supervisors__: Laurent Bernard, [Eric Gangloff](https://fr.linkedin.com/in/eric-gangloff-b19720aa)

## Baccalauréat, 2007

* __Delivered by__: Lycée Richelieu, Rueil Malmaison, France
* __Option__: Scientific (S)
* __Honnor__: *Très Bien*

  
----------

# Current Position

## November 2020 - Now: Research Engineer
  
* __Workplace__: [INRIA](https://www.inria.fr/fr), Saclay, France
* __Team__: [PARIETAL](https://team.inria.fr/parietal/)
* __Research focus__: Developement and maintenance of statistical learning softwares for NeuroImaging.
* __Supervisor__: [Bertrand Thirion](https://pages.saclay.inria.fr/bertrand.thirion/)

----------

# Work experience

## December 2018 - October 2020: Postdoctoral researcher
  
* __Workplace__: [Sorbonne University](http://www.sorbonne-universite.fr/) ([LIP6](https://www.lip6.fr/), UMR 7606), Paris, France
* __Team__: [Complex Networks](http://www.complexnetworks.fr/)
* __Research focus__: Designing anomaly detection methods for large streams of interactions
* __Supervisor__: [Matthieu Latapy](https://www-complexnetworks.lip6.fr/~latapy/)

## March 2017 - November 2018: Postdoctoral researcher
  
* __Workplace__: [National Renewable Energy Laboratory](https://www.nrel.gov/) (NREL), Golden, Colorado, USA
* __Team__: [Power Systems Design and Studies](https://www.nrel.gov/grid/power-systems-design-studies.html)
* __Research focus__: Designing methods and tools to optimize the deployment of renewable energy ressources in distribution systems
* __Supervisors__: [Bri-Mathias Hodge](https://www.colorado.edu/faculty/hodge/), [Bryan Palmintier](http://bryan.palmintier.net/)

## October 2013 - October 2016: Moniteur (special PhD student status with a teaching load)
  
* __Workplace__: [Sorbonne University](http://www.sorbonne-universite.fr/), Paris, France
* __Teaching load__: 192 hours (see *Teaching* section)

## November 2012 - September 2013: Research engineer
  
* __Workplace__: [Telecom SudParis](https://www.telecom-sudparis.eu/) ([SAMOVAR](http://samovar.telecom-sudparis.eu/?lang=fr), UMR 5157), Saclay, France
* __Team__: [METHODES](http://samovar.telecom-sudparis.eu/spip.php?rubrique128&lang=fr)
* __Research focus__: Smart Grids, Complex Networks
* __Supervisor__: [Michel Marot](http://www-public.imtbs-tsp.eu/~marot/), Monique Becker, [Vincent Gauthier](https://complex.luxbulb.org/)

## July 2011 - January 2012: Intern
  
* __Workplace__: [Conseil Général de la Seine-et-Marne](https://www.seine-et-marne.fr/) (CG77), Melun, France
* __Team__: *Aménagement du Territoire*
* __Duties__: Building a simulation and optimization tool for the optical fiber deployment in the Seine-et-Marne region.
* __Supervisor__: [Ariel Turpin](https://fr.linkedin.com/in/ariel-turpin-78b50929)
  

----------

# Publications

## Preprints

  <ul>{% for post in site.preprints reversed %}
      {% include archive-single-cv.html %}
    {% endfor %}</ul>
 
## International conferences

 <ul>{% for post in site.conference_publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
## International journals

  <ul>{% for post in site.journal_publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

  
----------

# Talks

## International talks
  
  <ul>{% for post in site.international_talks reversed %}
    {% include archive-single-talk-cv.html %}
  {% endfor %}</ul>

## Seminars and Workshops

  <ul>{% for post in site.local_talks reversed %}
    {% include archive-single-talk-cv.html %}
  {% endfor %}</ul>  
  
----------

# Teaching
  
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

----------

# Supervised students

* __Lester Padilla__
  * *Paris-Saclay University and Versailles St-Quentin-en-Yvelines University, April 2016 - September 2016*
  * Master thesis: Reconstructing the European Power Grid from OpenstreetMap data
  * Co-supervised with Vincent Gauthier
  
----------

# Open source main contributions

  <ul>{% for post in site.open_source reversed %}
    {% include archive-single-talk-cv.html %}
  {% endfor %}</ul>

  
----------

# Administrative responsibilities 

## 2021

* Organization of the [Nilearn dev-days 2021](https://nilearn.github.io/dev-days-2021/).

## 2020

* In charge of organising the seminars for the *Complex Networks* team at LIP6.
* Reviewer for the journal [Theoretical Computer Science](https://www.journals.elsevier.com/theoretical-computer-science).

## 2019

* In charge of organising the seminars for the *Complex Networks* team at LIP6.
* Reviewer for the journal [Computer Communications](https://www.journals.elsevier.com/computer-communications).
* Reviewer for the conference [TMA 2019](https://tma.ifip.org/2019/), Paris, France.

  
----------

# Skills

## Languages

* __French__: Native speaker
* __English__: Professional
* __German__: Coversational level

----------

## Technical skills

### Programming languages

* Scripting
  * Python
  * Julia
  * Matlab

* Web
  * HTML/CSS
  * PHP
  * JavaScript

* Others
  * C/C++/C#
  * Visual Basics
  * LaTeX

----------

### Tools

Here is a non-exhaustive selection of my favorite tools and packages:

* Continuous integration and testing
  * Git/GitHub/GitLab
  * Travis/CodeCov/PyTest

* Databases
  * MySQL
  * PostgreSQL/PostGIS
  * MongoDB
  * SQLAlchemy

* Machine Learning
  * Scikit-learn
  * TensorFlow
  * PyTorch

* Graphs
  * NetworkX
  * NetworKit
  * LightGraphs.jl
  * Gephi

* Performance and parallel computing
  * Dask
  * Spark
  * Moab
  * TORQUE

* Power System Modeling
  * OpenDSS
  * CYME
  * Synergi
  * DEW

