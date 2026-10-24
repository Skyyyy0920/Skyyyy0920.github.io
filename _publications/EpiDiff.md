---
title: "Bridging Dynamics and Data: A Unified Diffusion Framework for Mechanistically-Informed Epidemic Forecasting"
layout: publication-detail-page
collection: publications
category: conferences
permalink: /publication/EpiDiff
excerpt: "Guanghui Min, **Tianhao Huang**, Ke Wan, Qi R. Wang, Chen Chen"
authors: "Guanghui Min, <b>Tianhao Huang</b>, Ke Wan, Qi R. Wang, Chen Chen"
date: 2026-07-12
venue: 'ICML'
topics: [ai4sci]
topic_label: 'Epidemic forecasting'
paperurl: 'https://openreview.net/forum?id=AY7L7acRtD'
---
Guanghui Min, **Tianhao Huang**, Ke Wan, Qi R. Wang, Chen Chen

Reliable epidemic forecasting is critical for public health decision-making yet remains challenging due to data sparsity and the non-stationary nature of disease dynamics. While recent hybrid models attempt to integrate mechanistic principles with data-driven approaches, they often relegate mechanistic priors to merely auxiliary features or regularization terms. This design not only obscures the interpretability of the mechanistic contribution but also fails to inherit the capability of physical models to generalize under non-stationary dynamics, as the core architecture remains predominantly data-driven. To address these limitations, we propose EpiDiff, a unified framework that synergizes epidemiological domain knowledge with the generative power of diffusion models. Unlike methods that rigidly fuse features, EpiDiff employs a novel uncertainty-aware steering mechanism during inference. Specifically, we quantify the posterior uncertainty of mechanistic estimations and use it to dynamically modulate the diffusion process. Extensive experiments on real-world datasets demonstrate that EpiDiff consistently outperforms state-of-the-art baselines in accuracy and robustness, particularly under non-stationary distributions, while offering transparent insights into model reliance by explicitly visualizing when the forecast is governed by mechanistic laws versus data-driven patterns.
