---
title: "Calibrated Target-Aware Data Selection for Continual Mid-Training in Streams"
layout: publication-detail-page
collection: publications
category: conferences
permalink: /publication/CATS
excerpt: "Ke Wan, Tianyi Zhao, **Tianhao Huang**, Guanghui Min, Chen Chen"
authors: "Ke Wan, Tianyi Zhao, <b>Tianhao Huang</b>, Guanghui Min, Chen Chen"
date: 2026-07-10
venue: 'ICML Workshop'
topics: [llm]
topic_label: 'Data selection'
paperurl: 'https://openreview.net/forum?id=IhwYrJs9Ht'
---
Ke Wan, Tianyi Zhao, **Tianhao Huang**, Guanghui Min, Chen Chen

*Continual Adaptation at Scale: Towards Sustainable AI (CATS) Workshop at ICML 2026.*

Target-aware data selection aims to improve performance on a specific target objective by selecting training samples that are most beneficial to a small target set. Existing methods largely assume static access to the full candidate set, enabling global scoring and ranking. However, such offline access is rarely available in practice: candidate data typically arrives as a data stream over time, which precludes global re-scoring and highlights the need for online target-aware data selection, in which selection and model updates are performed repeatedly on small incoming batches. This regime introduces two key challenges: (i) the target-side signal used to guide selection, typically instantiated via target gradients, drifts as the model evolves; reusing stale signals leads to misaligned selection decisions, while frequent recomputation from a small target set yields high-variance and destabilizing estimates; and (ii) the online training dynamics may become non-convergent, resulting in late-stage performance degradation on the target even when the selection rule is repeatedly refreshed. To address these challenges, we analyze the dynamics of online target-aware selection and identify a bias-variance tradeoff in tracking drifting target signals, as well as structural sources of non-convergence. Guided by this analysis, we propose a lightweight stabilization framework that refreshes the target signal only when target performance plateaus and applies exponential moving average smoothing to control estimation variance.
