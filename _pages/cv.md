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
* Ph.D in Computer Science, Ecole Polytechnique Federale de Lausanne (EPFL), 2022 (expected)
* M.S. in Computer Science, Christian-Albrechts-University Kiel, 2018
* B.S. in Computer Science, Christian-Albrechts-University Kiel, 2015

Work experience
======

* Since October 2018: Research assistant
  * Natural Language Understanding Group, Idiap Research Institute, Martigny, Switzerland
  * Duties: Doctoral thesis on text representation learning and teaching NLP classes

* March 2018 - July 2017: Research assistant
  * Knowledge Discovery Group, Leibniz Information Centre for Economics (ZBW), Kiel, Germany
  * Duties: develop a sentence representation learning method based on the Compositional Matrix-Space Model of Language, paper writing

* June 2017 - November 2017: Student research assistant
  * Knowledge Discovery Group, Leibniz Information Centre for Economics (ZBW), Kiel, Germany
  * Duties: citation recommendation via (adversarial) denoising autoencoders in Tensorflow, paper writing

* April 2016 - January 2017: Student research assistant
  * Knowledge Discovery Group, Leibniz Information Centre for Economics (ZBW), Kiel, Germany
  * Duties: implementation of pipeline for information retrieval experiments, query expansion based on YAGO/Google Knowledge Graph, probabilistic language models and paragraph vector models for information retrieval, paper writing

* August 2013 - February 2014: Embedded software development internship
    * Mercedes-Benz Research & Development, Sunnyvale, USA
    * Duties: prototyping of technologies for smartphone integration within cars ('AppleCarPlay', 'MirrorLink')

* July - October 2012: Embedded software development internship
    * Jambit GmbH, Munich, Germany
    * Duties: client-side implementation of protocols for smartphone integration within cars ('MirrorLink')

Skills
======
* Programming expertise:
  * Python 3 (very proficient): PyTorch, pandas, TensorFlow
  * Java (proficient)
  * C, C++, R, Haskell, MATLAB, JavaScript (experienced)
  * comfortable with Linux and Git
* Languages
  * German (native proficiency)
  * English (full professional proficiency)
  * French (limited working proficiency)

Publications
======
  <ul>{% for post in site.publications %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Hackathons and competitions
======
Microsoft Hack@Home Hackathon Kiel
* goal: prediction of asset prices by applying NLP techniques to news or social media
* approach: crawl hourly oil prices and tweets from influential Twitter accounts from the oil business, predict price change via LSTM
* 1st place
[FakeNewsChallenge FNC-1](http://www.fakenewschallenge.org/):
* goal: predict whether a headline and an article body agree
* approach: LSTM and MLP approaches using Keras using several text representation features (Bag-of-Words, word2vec, doc2vec), similarity, and handcrafted features
* 6th place out of 50
[CAU-FLS-Coding Challenge](https://www.algo.informatik.uni-kiel.de/de/programmierwettbewerb/cau-fls-2015):
* goal: develop an algorithm for an online Travelling-Salesman-Problem
* approach: use polynomial regression to predict the starting parameters of our algorithm, then use a heuristic
* 3rd place
