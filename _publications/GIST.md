---
title: "GIST: Targeted Data Selection for Instruction Tuning via Coupled Optimization Geometry"
layout: publication-detail-page
collection: publications
category: conferences
permalink: /publication/GIST
excerpt: "Guanghui Min, **Tianhao Huang**, Ke Wan, Chen Chen"
authors: "Guanghui Min, <b>Tianhao Huang</b>, Ke Wan, Chen Chen"
date: 2026-07-13
venue: 'ICML'
topics: [llm]
topic_label: 'Data selection'
paperurl: 'https://arxiv.org/abs/2602.18584'
---
Guanghui Min, **Tianhao Huang**, Ke Wan, Chen Chen

Targeted data selection has emerged as a crucial paradigm for efficient instruction tuning, aiming to identify a small yet influential subset of training examples for a specific target task. In practice, influence is often measured through the effect of an example on parameter updates. To make selection scalable, many approaches leverage optimizer statistics (e.g., Adam states) as an axis-aligned surrogate for update geometry (i.e., diagonal precondition), implicitly treating parameters as coordinate-wise independent. We show that this assumption breaks down in parameter-efficient fine-tuning (PEFT) methods such as LoRA. In this setting, the induced optimization geometry exhibits strong cross-parameter coupling with non-trivial off-diagonal interactions, while the task-relevant update directions are confined to a low-dimensional subspace. Motivated by this mismatch, we propose GIST (Gradient Isometric Subspace Transformation), a simple yet principled alternative that replaces axis-aligned scaling with robust subspace alignment. GIST recovers a task-specific subspace from validation gradients via singular value decomposition (SVD), projects training gradients into this coupled subspace, and scores examples by their alignment with target directions. Extensive experiments have demonstrated that GIST matches or outperforms the state-of-the-art baseline with only 0.29% of the storage and 25% of the computational time under the same selection budget.
