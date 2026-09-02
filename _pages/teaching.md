---
layout: archive
title: "Teaching"
permalink: /teaching/
author_profile: true
redirect_from:
  - /teach
---

{% include base_path %}

Students learn the value of sociology most effectively when they see theory and methods as tools for answering consequential questions about the social world. My teaching pursues three related goals: helping students connect individual experiences to social structures, making quantitative reasoning accessible without sacrificing rigor, and preparing students to analyze evidence responsibly and communicate it clearly.

In substantive courses like Medical Sociology, I use think-pair-share activities, small-group discussion, and structured writing assignments to give students of different backgrounds and preparation multiple ways to develop and demonstrate sociological arguments. In quantitative and computational methods courses, I organize learning around the full research process — from framing a sociological question through model specification, diagnostics, and substantive interpretation — using scaffolded assignments, annotated example code in R and Stata, and an emphasis on reproducible workflows.

I am equally committed to mentorship: I have mentored junior graduate students in research design and analysis, guided undergraduate and graduate researchers through data collection and scholarly writing, and helped create a mentor–mentee program pairing senior and junior graduate students in the Purdue Sociology graduate program.

## Courses & Teaching Experience

{% for post in site.teaching reversed %}
  {% include archive-single.html %}
{% endfor %}
