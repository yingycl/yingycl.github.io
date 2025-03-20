---
title: "A Multiobjective Evolutionary Approach for Solving Large-Scale Network Reconstruction Problems via Logistic Principal Component Analysis"
collection: publications
category: manuscripts
permalink: /publication/2009-10-01-paper-title-number-1
excerpt: '**Chaolong Ying**, Jing Liu, Kai Wu, and Chao Wang'
date: 2021-09-14
venue: 'IEEE Transactions on Cybernetics'
slidesurl: #'http://academicpages.github.io/files/slides1.pdf'
paperurl: 'https://ieeexplore.ieee.org/abstract/document/9537739?casa_token=O3KX_GGriU8AAAAA:r1EKubUQ9SRLknsbp9p67jsAEwZ0CNHocjcnKyUoxU4xWRoR7SUR5gMLYKVuIhLSCNyoBL1UBEM'
citation: 'C. Ying, J. Liu, K. Wu and C. Wang, "A Multiobjective Evolutionary Approach for Solving Large-Scale Network Reconstruction Problems via Logistic Principal Component Analysis," in IEEE Transactions on Cybernetics, vol. 53, no. 4, pp. 2137-2150, April 2023, doi: 10.1109/TCYB.2021.3109914.'
---

Currently, the problem of uncovering complex network structure and dynamics from time series is prominent in many fields. Despite the recent progress in this area, reconstructing large-scale networks from limited data remains a tough problem. Existing works treat connections of nodes as continuous values, leaving a challenge of setting a proper cut-off value to distinguish whether the connections exist or not. Besides, their performances on large-scale networks are far from satisfactory. Considering the reconstruction error and sparsity as two objectives, this article proposes a subspace learning-based evolutionary multiobjective network reconstruction algorithm, called SLEMO-NR, to solve the aforementioned problems. In the evolutionary process, we assume that binary-coded individuals obey the Bernoulli distribution and can use the probability and natural parameter as alternative representations. Moreover, our approach utilizes the logistic principal component analysis (LPCA) to learn a subspace containing the features of the network structure. The offspring solutions are generated in the learned subspace and then can be mapped back to the original space via LPCA. Benefitting from the alternative representations, a preference-based local search operator (PLSO) is proposed to concentrate on finding solutions approximate to the true sparsity. The experimental results on synthetic networks and six real-world networks demonstrate that, due to the well-learned network structure subspace and the preference-based strategy, our approach is effective in reconstructing large-scale networks compared to six existing methods.