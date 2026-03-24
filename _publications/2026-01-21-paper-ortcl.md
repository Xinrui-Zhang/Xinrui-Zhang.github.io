---
title: "ORTCL: Towards Continual Learning of Time Series Foundation Models on Streaming Data via Orthogonal Rotation"
collection: publications
permalink: /publications/2026-01-21-paper-ortcl
date: 2026-01-21
venue: "AAAI"
paperurl: "https://ojs.aaai.org/index.php/AAAI/article/view/39526"
citation: "Lin, L., <b>Zhang, X.</b>, Zhang, Q., Wang, S. &Xia, K. (2026, January). ORTCL: Towards Continual Learning of Time Series Foundation Models on Streaming Data via Orthogonal Rotation. In Proceedings of the AAAI Conference on Artificial Intelligence. 2026."
---

Time Series Foundation Models (TSFMs) have emerged as a promising approach in time series analysis. Due to the large-scale parameters of TSFMs and pretraining cost, how to adapt TDFMs in streaming data is always the key factor constraining their application effectiveness. Because streaming data often experiences data distribution and task drifts, which cannot be learnt by offline training. Existing methods typically address streaming data modeling with continuous learning through model fine-tuning or model editing. However, fine-tuning incurs significant computational costs, while editing methods can lead to shifts in the original feature space during streaming updates. To address these limitations, we propose a novel Orthogonal Rotation Transformation-based Continuous Learning method, called ORTCL, for TSFMs. Our key insight is to apply orthogonal matrix rotations to the input and output feature spaces of the TSFMs during model editing. This preserves the metric structure of the original feature space and enables new data to be directly mapped into the existing feature space of the TSFMs. Specifically, we obtain the orthogonal matrix for the input layer via singular value decomposition and derive the corresponding transfor mation matrix for the output layer through least squares optimization. Extensive experimental results demonstrate that ORTCL outperforms existing methods in both single-domain and cross-domain streaming time series forecasting tasks, effectively mitigating catastrophic forgetting.

[Download paper here](https://ojs.aaai.org/index.php/AAAI/article/view/39526)

Recommended citation: Lin, L., <b>Zhang, X.</b>, Zhang, Q., Wang, S. &Xia, K. (2026, January). ORTCL: Towards Continual Learning of Time Series Foundation Models on Streaming Data via Orthogonal Rotation. In <i>Proceedings of the AAAI Conference on Artificial Intelligence.</i> 2026.
