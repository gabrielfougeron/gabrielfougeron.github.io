---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

You can download PDF versions of my full CV [in French](http://gabrielfougeron.github.io/files/cv_files/CV_Full_Gabriel_Fougeron_French.pdf) and [in English](http://gabrielfougeron.github.io/files/cv_files/CV_Full_Gabriel_Fougeron_English.pdf).


Publications
======
  <ul>{% for post in site.publications %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Talks
======
  <ul>{% for post in site.talks %}
    {% include archive-single-talk-cv.html %}
  {% endfor %}</ul>
  
<!-- Teaching
======
  <ul>{% for post in site.teaching %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Service and leadership
======
* Currently signed in to 43 different slack teams -->
