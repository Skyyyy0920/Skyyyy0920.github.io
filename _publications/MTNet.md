---
title: "Learning time slot preferences via mobility tree for next poi recommendation"
layout: publication-detail-page
collection: publications
category: conferences
permalink: /publication/MTNet
excerpt: "**Tianhao Huang&dagger;**, Xuan Pan&dagger;, Xiangrui Cai&Dagger;, Ying Zhang, Xiaojie Yuan"
date: 2024-03-24
venue: 'AAAI'
slidesurl: 'http://skyyyy0920.github.io//files/MTNet-slides.pptx'
paperurl: 'https://ojs.aaai.org/index.php/AAAI/article/view/28697'
bibtexurl: 'https://arxiv.org/src/2403.12100'
# citation: 'Tianhao Huang, Xuan Pan, Xiangrui Cai, Ying Zhang, Xiaojie Yuan. "Learning time slot preferences via mobility tree for next poi recommendation." Proceedings of the AAAI Conference on Artificial Intelligence. Vol. 38. No. 8. 2024.'
---

Next Point-of-Interests (POIs) recommendation task aims to provide a dynamic ranking of POIs based on users' current check-in trajectories. The recommendation performance of this task is contingent upon a comprehensive understanding of users' personalized behavioral patterns through Location-based Social Networks (LBSNs) data. While prior studies have adeptly captured sequential patterns and transitional relationships within users' check-in trajectories, a noticeable gap persists in devising a mechanism for discerning specialized behavioral patterns during distinct time slots, such as noon, afternoon, or evening. In this paper, we introduce an innovative data structure termed the ``Mobility Tree'', tailored for hierarchically describing users' check-in records. The Mobility Tree encompasses multi-granularity time slot nodes to learn user preferences across varying temporal periods. Meanwhile, we propose the Mobility Tree Network (MTNet), a multitask framework for personalized preference learning based on Mobility Trees. We develop a four-step node interaction operation to propagate feature information from the leaf nodes to the root node. Additionally, we adopt a multitask training strategy to push the model towards learning a robust representation. The comprehensive experimental results demonstrate the superiority of MTNet over eleven state-of-the-art next POI recommendation models across three real-world LBSN datasets, substantiating the efficacy of time slot preference learning facilitated by Mobility Tree.