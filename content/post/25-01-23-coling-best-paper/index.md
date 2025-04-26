---
title: BrockNLP Lab Authors Win Best Dataset Paper
date: 2025-01-23
image:
  focal_point: 'top'
---

Congratulations to BrockNLP Researchers **Angel Yahir Loredo Lopez** (Mitacs Globalink Intern 2024), **Tyler McDonald** (Undergraduate Researcher), and **Ali Emami** (Director) on receiving the **COLING 2025 Best Dataset Paper Award** for their work, *NYT-Connections: A Deceptively Simple Text Classification Task that Stumps System-1 Thinkers*!

*NYT-Connections* is a dataset formed of daily Connections word puzzles published by the New York Times. Testing reveals that state-of-the-art LLMs still **fall short of human benchmarks,** with advanced prompting techniques like Chain-of-Thought Prompting offering **diminishing returns as task difficulty increases.**

You can read the paper [here](https://arxiv.org/pdf/2412.01621) and can access the dataset [here!](https://huggingface.co/datasets/tm21cy/NYT-Connections)

**Abstract:**

Large Language Models (LLMs) have shown impressive performance on various benchmarks, yet their ability to engage in deliberate reasoning remains questionable. We present NYT-Connections, a collection of 358 simple word classification puzzles derived from the New York Times Connections game. This benchmark is designed to penalize quick, intuitive "System 1" thinking, isolating fundamental reasoning skills. We evaluated six recent LLMs, a simple machine learning heuristic, and humans across three configurations: single-attempt, multiple attempts without hints, and multiple attempts with contextual hints. Our findings reveal a significant performance gap: even top-performing LLMs like GPT-4 fall short of human performance by nearly 30%. Notably, advanced prompting techniques such as Chain-of-Thought and Self-Consistency show diminishing returns as task difficulty increases. NYT-Connections uniquely combines linguistic isolation, resistance to intuitive shortcuts, and regular updates to mitigate data leakage, offering a novel tool for assessing LLM reasoning capabilities.
