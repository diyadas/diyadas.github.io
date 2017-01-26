---
layout: archive
title: "Resume"
permalink: /resume/
author_profile: true
redirect_from:
  - /wordpress/resume/
---

{% include base_path %}

Education
======
* PhD in Molecular & Cell Biology, University of California, Berkeley, December 2017 (expected)
* AB in Molecular Biology & Certificate in Neuroscience (Quantitative & Computational Neuroscience honors track), Princeton University, June 2012

Experience
======
* Graduate Student Researcher, University of California, Berkeley (2012-present)
  * PI: John Ngai
  * I analyze single-cell RNA-sequencing data to characterize regeneration in the olfactory epithelium, particularly the lineage trajectories arising from the olfactory stem cell.
  * California Institute for Regenerative Medicine (CIRM) Predoctoral Fellow (2015)
  * Elizabeth Einstein Roboz Fellowship (Spring 2015)

* Career Development Initiative in the Physical Sciences (CDIPS) Data Science Workshop (July 2016)
  * Team developed topic ontology for English Wikipedia articles and classifier for new articles
  
Skills
======
* Data analysis, statistics
* Science: molecular biology, developmental biology, stem cell biology, neuroscience, single-cell RNA-sequencing 
* Programming: R/RStudio, Python, Matlab, Git, some bash
* Design: Adobe Illustrator, InDesign

Publications
======
  {% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}

Presentations
======
  {% for post in site.talks reversed %}
    {% unless post.talk_type == "Conference proceedings talk" %}
      {% include archive-single-talk-cv.html %}
    {% endunless %}
  {% endfor %} 

Leadership
======
  {% for post in site.portfolio %}
    {% include archive-single.html %}
  {% endfor %}

Teaching
======
  {% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}