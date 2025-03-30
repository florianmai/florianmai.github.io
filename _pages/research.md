---
layout: single
title: "Research"
permalink: /research/
author_profile: true
---

My research focuses on advancing the field of Artificial Intelligence, with particular emphasis on:



1. **(Super)-Alignment of Language Models and Advanced AI** (2025 - ongoing)
   - As AIs are becoming increasingly advanced, it becomes harder for humans to effectively oversee them. A common approach is to have other AIs provide the supervision. But how do you avoid a lock-in effect, where the values of today's AIs are preserved indefinitely? In our paper, [Superalignment with Dynamic Human Values](https://arxiv.org/abs/2503.13621), we propose a framework to align AIs with dynamically evolving human values.

2. **Planning and Reasoning in Language Models** (2023 - ongoing)
   - LLMs are so successful because they are trained from huge amounts of unlabeled data. Most existing approaches to planning and reasoning in LLMs use advanced prompting techniques or finetune on domain-specific tasks, which do not exploit the strengths of unlabeled data. I am interested in developing new methods to leverage the strengths of unlabeled data to improve planning and reasoning in LLMs in general.
   - To make LLMs more robust and reliable, they need to be able to reason effectively. If we can leverage unlabeled data to learn a model of what would happen when taking an action in a certain context, we can leverage this model to make better decisions.
   - In our [COLM 2024 paper](https://arxiv.org/abs/2404.00614), we learn to predict abstract writing actions from unlabeled data and use them to control the future writing process of the LM. Furthermore, we extended this approach to [predicting multiple steps into the future](https://arxiv.org/abs/2409.00070) and [making the process end-to-end differentiable](https://arxiv.org/abs/2410.12492).

3. **Efficient Text Representation Learning** (2018 - 2023)
   - My PhD thesis focused on reducing the costs of natural language understanding in terms of processing time, required labeled data, and hyperparameter tuning. This research interest encompasses:
     - Developing a fast and order-sensitive sentence embedding method ([ICLR 2019](https://arxiv.org/abs/1902.06423))
     - Creating frameworks for learning conditional text generation tasks with less labeled data ([EMNLP 2020](https://arxiv.org/abs/2010.02983), [AACL 2022](https://arxiv.org/abs/2110.07002))
     - Proposing evaluation protocols for deep learning optimizers to reduce hyperparameter tuning ([ICML 2020](https://arxiv.org/abs/1910.11758))
     - Introducing efficient token mixing architectures as alternatives to the attention mechanism ([ACL 2024](https://arxiv.org/abs/2203.03691), [InterSpeech 2024](https://arxiv.org/abs/2305.18281))
   - These approaches aim to make NLP more accessible to research teams with limited resources and enable further scaling of language models and other AI systems.

4. **Deep Learning in Digital Libraries** (2016-2018)
   - To enable the efficient use of digital libraries, data needs to be easily accessible, requiring categorization of articles, indexing, and retrieval, and recommendations.
   - With the rise of Deep Learning techniques for text, new ways to improve the efficiency of these tasks are being offered. I have contributed to the adoption of these techniques in the field of digital libraries in several ways:
      - Text categorization methods ([JCDL 2018](https://arxiv.org/abs/1801.06717), [KCAP 2017](https://arxiv.org/pdf/1705.05311))
      - Recommender systems ([UMAP 2018](https://arxiv.org/abs/1907.12366), [RecSys 2019 Workshop](https://dl.acm.org/doi/10.1145/3267471.3267476)