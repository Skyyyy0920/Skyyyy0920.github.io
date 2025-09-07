---
title: "Faithful interpretation for graph neural networks"
layout: publication-detail-page
collection: publications
category: conferences
permalink: /publication/FGAI
excerpt: "Lijie Hu&dagger;, **Tianhao Huang&dagger;**, Lu Yu, Wanyu Lin, Tianhang Zheng, Di Wang&Dagger;"
date: 2025-04-03
venue: 'TMLR'
#slidesurl: 'http://skyyyy0920.github.io//files/slides1.pdf'
paperurl: 'https://openreview.net/pdf?id=Y8EspxaksH'
bibtexurl: 'https://jmlr.org/tmlr/papers/bib/Y8EspxaksH.bib'
---

Currently, attention mechanisms have garnered increasing attention in Graph Neural Networks (GNNs), such as Graph Attention Networks (GATs) and Graph Transformers (GTs). It is not only due to the commendable boost in performance they offer but also its capacity to provide a more lucid rationale for model behaviors, which are often viewed as inscrutable. However, Attention-based GNNs have demonstrated instability in interpretability when subjected to various sources of perturbations during both training and testing phases, including factors like additional edges or nodes. In this paper, we propose a solution to this problem by introducing a novel notion called Faithful Graph Attention-based Interpretation (FGAI). In particular, FGAI has four crucial properties regarding stability and sensitivity to interpretation and final output distribution. Built upon this notion, we propose an efficient methodology for obtaining FGAI, which can be viewed as an ad hoc modification to the canonical Attention-based GNNs. To validate our proposed solution, we introduce two novel metrics tailored for graph interpretation assessment. Experimental results demonstrate that FGAI exhibits superior stability and preserves the interpretability of attention under various forms of perturbations and randomness, which makes FGAI a more faithful and reliable explanation tool.