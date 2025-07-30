---
title: "GeM: Gaussian embeddings with Multi-hop graph transfer for next POI recommendation"
collection: publications
permalink: /publication/GeM
date: 2025-02
venue: 'Neural Network'
paperurl: 'http://Liujyuan.github.io//me/files/paper2.pdf'
citation: 'Wenqian Mu* , Jiyuan Liu*, Yongshun Gong, et al. (*equcation contribution) '
---

In this work, we present GeM, the first POI recommendation model that exploits Gaussian embedding and multi-hop graph transfer mechanisms. We introduce Gaussian distribution assumptions to capture the asymmetrical relation of POIs, and Mahalanobis distance is adopted to calculate the conditional probability distribution for recommendation. Furthermore, based on the global trajectory graph we constructed, we adopt a self-attention layer to obtain a basic transfer matrix, and the final recommendation based on the last ten POIs is obtained through a multi-hop aggregation layer, thus enhancing the learning of the objective connections inherent in POI. Matrix factorization is also used to obtain objective transfer distributions of POI about users. Finally, both subjective and objective aspects are integrated to produce complementary recommendations. We conducted a comprehensive ablation study and stability study in the experimental section to demonstrate the role of each component on recall and MRR metrics. The effect of variations in hyper-parameters on model performance was analyzed. Through a series of experiments on two real datasets, our model significantly outperformed all current state-of-the-art models on the two datasets.
