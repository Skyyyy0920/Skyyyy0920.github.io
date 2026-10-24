---
title: "Prompt-SAW: Leveraging Relation-Aware Graphs for Textual Prompt Compression"
layout: publication-detail-page
collection: publications
category: conferences
permalink: /publication/PromptSAW
excerpt: "Muhammad Asif Ali, Zhengping Li, Shu Yang, Keyuan Cheng, Yang Cao, **Tianhao Huang**, Guimin Hu, Weimin Lyu, Lijie Hu, Lu Yu, Di Wang"
authors: "Muhammad Asif Ali, Zhengping Li, Shu Yang, Keyuan Cheng, Yang Cao, <b>Tianhao Huang</b>, Guimin Hu, Weimin Lyu, Lijie Hu, Lu Yu, Di Wang"
# arXiv v1 is dated 2024-03-30; the date below only controls list order (keeps it below the AAAI paper).
date: 2024-03-01
venue: 'arXiv'
topics: [llm]
topic_label: 'Prompt compression'
paperurl: 'https://arxiv.org/abs/2404.00489'
---
Muhammad Asif Ali, Zhengping Li, Shu Yang, Keyuan Cheng, Yang Cao, **Tianhao Huang**, Guimin Hu, Weimin Lyu, Lijie Hu, Lu Yu, Di Wang

Large Language Models (LLMs) have shown exceptional abilities for multiple different natural language processing tasks. While prompting is a crucial tool for LLM inference, we observe that there is a significant cost associated with exceedingly lengthy prompts. Existing attempts to compress lengthy prompts lead to substandard results in terms of readability/interpretability of the compressed prompt, with a detrimental impact on prompt utility. To address this, we propose PromptSAW: Prompt compresSion via Relation AWare graphs, an effective strategy for prompt compression over task-agnostic and task-aware prompts. Prompt-SAW uses the prompt's textual information to build a graph and later extracts key information elements in the graph to come up with the compressed prompt. We also propose GSM8K-aug, i.e., an extended version of the existing GSM8K benchmark for task-agnostic prompts in order to provide a comprehensive evaluation platform. Experimental evaluation using benchmark datasets shows that prompts compressed by Prompt-SAW are not only better in terms of readability, but they also outperform the best-performing baseline models by up to 10.1 and 77.1, respectively, for task-agnostic and task-aware settings while compressing the original prompt text by 34.9 and 56.7.
