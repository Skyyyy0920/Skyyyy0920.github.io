---
title: "Efficient Text-Attributed Graph Learning through Selective Annotation and Graph Alignment"
layout: publication-detail-page
collection: publications
category: manuscripts
permalink: /publication/GAGA
excerpt: "Huanyi Xie, Lu Yu, **Tianhao Huang**, Longfei Li, Meng Li, Jun Zhou, Lijie Hu, Di Wang"
authors: "Huanyi Xie, Lu Yu, <b>Tianhao Huang</b>, Longfei Li, Meng Li, Jun Zhou, Lijie Hu, Di Wang"
date: 2026-04-01
venue: 'TMLR'
topics: [graph, llm]
topic_label: 'Text-attributed graphs'
paperurl: 'https://openreview.net/forum?id=UBIPauyTYp'
---
Huanyi Xie, Lu Yu, **Tianhao Huang**, Longfei Li, Meng Li, Jun Zhou, Lijie Hu, Di Wang

In the realm of Text-attributed Graphs (TAGs), traditional graph neural networks (GNNs) often fall short due to the complex textual information associated with each node. Recent methods have improved node representations by leveraging large language models (LLMs) to enhance node text features, but these approaches typically require extensive annotations or fine-tuning across all nodes, which is both time-consuming and costly. To overcome these challenges, we introduce GAGA, an efficient framework for TAG representation learning. GAGA reduces annotation time and cost by focusing on annotating only representative nodes and edges. It constructs an annotation graph that captures the topological relationships among these annotations. Furthermore, GAGA employs a two-level alignment module to effectively integrate the annotation graph with the TAG, aligning their underlying structures. Experiments show that GAGA achieves classification accuracies on par with or surpassing state-of-the-art methods while requiring only 1% of the data to be annotated, demonstrating its high efficiency.
