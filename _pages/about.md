---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

About me
======

I am a Computational Biology Ph.D. student with five years of experience in machine learning and statistical data analysis. My dissertation research focuses on multifunctional peptide engineering, malaria vaccine antigen identification, and interpretable machine learning. I am specifically passionate about developing ML/AI-based analytical methodologies to improve the quality of life, and have been collaborating with scientists at UMD School of Medicine and Johns Hopkins School of Medicine.

Research projects
======

{% include base_path %}

{% for post in site.portfolio %}
  {% include archive-single.html %}
  <hr class="solid">
{% endfor %}
