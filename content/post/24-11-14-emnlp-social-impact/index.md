---
title: STOP Wins Social Impact Award!
date: 2024-11-14
image:
  focal_point: 'top'
---

Congratulations to BrockNLP Researchers **Robert Morabit** (MSc. Student), **Sangmitra Madhusudan** (Undergraduate Researcher), **Tyler McDonald** (Undergraduate Researcher), and **Ali Emami** (Director) on receiving the **EMNLP 2024 Social Impact Paper Award** for their work, *STOP! Benchmarking Large Language Models with Sensitivity Testing on Offensive Progressions*!

*STOP* is a dataset formed of offensive progressions, or simulated scenarios where bias gradually becomes more severe and transitions from implicit to explicit. Through evaluating several state-of-the-art models, *STOP* reveals inconsistent detection and permission of bias across many demographics. 

You can read the paper [here](https://arxiv.org/pdf/2409.13843) and can access the dataset [here!](https://huggingface.co/datasets/Robert-Morabito/STOP)

**Abstract:**

Mitigating explicit and implicit biases in Large Language Models (LLMs) has become a critical focus in the field of natural language processing. However, many current methodologies evaluate scenarios in isolation, without considering the broader context or the spectrum of potential biases within each situation. To address this, we introduce the Sensitivity Testing on Offensive Progressions (STOP) dataset, which includes 450 offensive progressions containing 2,700 unique sentences of varying severity that progressively escalate from less to more explicitly offensive. Covering a broad spectrum of 9 demographics and 46 sub-demographics, STOP ensures inclusivity and comprehensive coverage. We evaluate several leading closed- and open-source models, including GPT-4, Mixtral, and Llama 3. Our findings reveal that even the best-performing models detect bias inconsistently, with success rates ranging from 19.3% to 69.8%. We also demonstrate how aligning models with human judgments on STOP can improve model answer rates on sensitive tasks such as BBQ, StereoSet, and CrowS-Pairs by up to 191%, while maintaining or even improving performance. STOP presents a novel framework for assessing the complex nature of biases in LLMs, which will enable more effective bias mitigation strategies and facilitates the creation of fairer language models.
