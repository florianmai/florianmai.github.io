---
permalink: /
title: "About me"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

## Short Biography

Florian is a Junior Research Group Leader at the [CAISA group at University of Bonn](https://caisa-lab.github.io/), led by Lucie Flek, as part of [The Lamarr Institute for Machine Learning and Artificial Intelligence](https://lamarr-institute.org/).
His focus is on learning planning components for language models from unlabeled data, and the use of planning for improving the performance and safety of LLM-based agents.

Previously, he was a Postdoctoral Research Fellow at the [Language Intelligence & Information Retrieval lab at KU Leuven](https://liir.cs.kuleuven.be/people.php), led by Marie-Francine Moens, where he worked on learning planning components for [language modeling from unlabeled data](https://arxiv.org/abs/2404.00614).
He received his PhD from EPFL and worked in the Natural Language Understanding group at Idiap Research Institute led by James Henderson. [His PhD thesis](https://infoscience.epfl.ch/entities/publication/da7832d4-78b9-43db-b2fa-098893e27677) aims to decrease the costs of natural language understanding in terms of processing time ([CMOW sentence embeddings](https://arxiv.org/abs/1902.06423) and [HyperMixer](https://arxiv.org/abs/2203.03691)), required [labeled data](https://arxiv.org/abs/2010.02983), and [hyperparameter tuning](https://arxiv.org/abs/1910.11758).

During his master's studies, he worked as a student research assistant with Ansgar Scherp at Leibniz Information Centre for Economics - ZBW. He studied several NLP-related topics like [topical document classification in digital libraries](https://arxiv.org/abs/1801.06717) and [citation recommendation](https://arxiv.org/abs/1907.12366).

## Current Research Interest

Language models have become so successful because we can train them effectively from large amounts of diverse, unlabeled data, which enables them to acquire a wide variety of skills and knowledge. This is a reflection of the ['bitter lesson'](http://www.incompleteideas.net/IncIdeas/BitterLesson.html?ref=blog.heim.xyz): Any algorithmic approach to AI needs to be able to easily scale to large amounts of (unlabeled) data.

Planning and reasoning remains a core challenge for LLMs. However, despite the teachings of the bitter lesson, the vast majority of current approaches to planning and reasoning in LLMs do not try make use of the unlabeled data. In my opinion, taking the self-supervised learning approach to the level of planning and reasoning is the key to unlocking the full potential of LLMs.

During my time as a postdoc at KU Leuven, I led a project to learn planning components for language modeling from unlabeled data. In [our first published work](https://arxiv.org/abs/2404.00614), we learn a planning component to predict an abstract writing action of the next sentence, which guides the language model in its predictions of the future writing process. We are currently investigating how to generalize this approach to reasoning with concrete planning paths, and how to use the resulting planning component for improving the performance and safety of LLM-based agents.