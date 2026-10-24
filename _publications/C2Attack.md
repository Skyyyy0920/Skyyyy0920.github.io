---
title: "Towards Representation Backdoor on CLIP via Concept Confusion"
layout: publication-detail-page
collection: publications
category: manuscripts
permalink: /publication/C2Attack
excerpt: "Junchi Liao, Weimin Lyu, Lijie Hu, Shaopeng Fu, **Tianhao Huang**, Shu Yang, Jie Li, Di Wang"
authors: "Junchi Liao, Weimin Lyu, Lijie Hu, Shaopeng Fu, <b>Tianhao Huang</b>, Shu Yang, Jie Li, Di Wang"
date: 2026-05-01
venue: 'TMLR'
topics: [trust]
topic_label: 'Backdoor attack'
paperurl: 'https://openreview.net/forum?id=jQ91DETUIr'
---
Junchi Liao, Weimin Lyu, Lijie Hu, Shaopeng Fu, **Tianhao Huang**, Shu Yang, Jie Li, Di Wang

Backdoor attacks pose a serious threat to deep learning models by allowing adversaries to implant hidden behaviors that remain dormant on clean inputs but are maliciously triggered at inference. Existing backdoor attack methods typically rely on explicit triggers such as image patches or pixel perturbations, which makes them easier to detect and limits their applicability in complex settings. To address this limitation, we take a different perspective by analyzing backdoor attacks through the lens of concept-level reasoning, drawing on insights from interpretable AI. We show that traditional attacks can be viewed as implicitly manipulating the concepts activated within a model's latent space. This motivates a natural question: can backdoors be built by directly manipulating concepts? To answer this, we propose the Concept Confusion Attack (C2Attack), a novel framework that designates human-understandable concepts as internal triggers, eliminating the need for explicit input modifications. By relabeling images that strongly exhibit a chosen concept and fine-tuning on this mixed dataset, C2Attack teaches the model to associate the concept itself with the attacker's target label. Consequently, the presence of the concept alone is sufficient to activate the backdoor, making the attack stealthier and more resistant to existing defenses. Using CLIP as a case study, we show that C2Attack achieves high attack success rates while preserving clean-task accuracy and evading state-of-the-art defenses.
