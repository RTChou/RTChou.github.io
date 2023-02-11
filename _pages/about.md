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

I am a Computational Biology Ph.D. candidate with over 6 years of experience in machine learning, data science, and statistical data analysis. My research is focused on addressing a broad spectrum of biological problems, including multifunctional peptide engineering for drug delivery, malaria vaccine antigen candidate identification, and the application of interpretable machine learning in biomedical research.

My passion lies in developing cutting-edge AI and machine learning solutions to improve the quality of life in various fields. I constantly stay up-to-date with the latest technology advancements, including cloud computing and parallel processing for large-scale data analysis. I place a strong emphasis on model interpretability in my work, ensuring that the results of my research are transparent and understandable.

Research projects
======

{% include base_path %}

{% for post in site.portfolio %}
  {% include archive-single.html %}
  <hr class="solid">
{% endfor %}
