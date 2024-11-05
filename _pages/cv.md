---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
* Ph.D in Computer Science and AI, Ecole Polytechnique, 2025 (expected)
* M.S. in Data science, Ecole Polytechnique, 2020
* B.S. in Mathematics, Université Grenoble ALpes, 2018

Work experience
======
* Research Engineer , July 2022 - Now
  * Linagora
  * Conducted engineering Research work alongside Ph.D studies, contributing to various tasks related to language model development
  * Curated, collected, and organized datasets from diverse sources to support training and evaluation of Large Language Models.
  * Implement pre-training and fine-tuning of Large Language Models using distributed computing frameworks.
  * Advanced research in dialogue summarization, utilizing linguistic and discourse-based graph structures.

* Natural Language Processing and Graph Research Engineer, April 2020 - July 2022
  * Ecole Polytechnique, LiX
  * Developed and trained models on graph-structured networks to enhance understanding of edge representations.
  * Trained a BERT style model for the classification and analysis of French tweets.
  * Analyzed shifts in offensive language on Twitter, with a focus on changes emerging during the COVID-19 pandemic.
  
Skills and Languages
======
* Machine Learning; Pytorch, Keras, Transformers, Scikit-learn, Pytorch Geometric
* Programming : Python, R, MATLaB, Numpy, C
* Languages : French (Native), English (C2), German (A2), Greek (Notions)
* Hobbies : Board Games, Powerlifting, Climbing

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
