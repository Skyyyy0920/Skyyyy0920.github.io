---
title: "Semi-supervised concept bottleneck models"
layout: publication-detail-page
collection: publications
category: conferences
permalink: /publication/SSCBM
excerpt: "Lijie Hu&dagger;, **Tianhao Huang&dagger;**, Huanyi Xie, Xilin Gong, Chenyang Ren, Zhengyu Hu, Lu Yu, Ping Ma, Di Wang&Dagger;"
date: 2025-07-24
venue: 'ICCV'
#slidesurl: 'http://skyyyy0920.github.io//files/slides1.pdf'
paperurl: 'https://arxiv.org/pdf/2406.18992'
#bibtexurl: 'http://skyyyy0920.github.io//files/bibtex1.bib'
---

Concept Bottleneck Models (CBMs) have garnered increasing attention due to their ability to provide concept-based explanations for black-box deep learning models while achieving high final prediction accuracy using human-like concepts. However, the training of current CBMs heavily relies on the accuracy and richness of annotated concepts in the dataset. These concept labels are typically provided by experts, which can be costly and require significant resources and effort. Additionally, concept saliency maps frequently misalign with input saliency maps, causing concept predictions to correspond to irrelevant input features - an issue related to annotation alignment. To address these limitations, we propose a new framework called SSCBM (Semi-supervised Concept Bottleneck Model). Our SSCBM is suitable for practical situations where annotated data is scarce. By leveraging joint training on both labeled and unlabeled data and aligning the unlabeled data at the concept level, we effectively solve these issues. We proposed a strategy to generate pseudo labels and an alignment loss. Experiments demonstrate that our SSCBM is both effective and efficient. With only 10% labeled data, our model's concept and task accuracy on average across four datasets is only 2.44% and 3.93% lower, respectively, compared to the best baseline in the fully supervised learning setting.