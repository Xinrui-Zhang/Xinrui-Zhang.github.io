---
title: "A Transferable Spatio-temporal Learning Framework for Cross-city Logistics Demand Prediction"
collection: publications
permalink: /publications/2025-08-03-paper-tstl
date: 2025-08-03
venue: "ACM SIGKDD"
paperurl: "https://dl.acm.org/doi/abs/10.1145/3711896.3737186"
citation: "Xia, K., Lin, L., Zhang, X., Wang, H., Wang, S., & He, T. (2025, August). A Transferable Spatio-temporal Learning Framework for Cross-city Logistics Demand Prediction. In Proceedings of the 31st ACM SIGKDD Conference on Knowledge Discovery and Data Mining V. 2 (pp. 5071-5082)."
---

In logistic systems, demand prediction is an essential task providing the basis for improving the quality of terminal services, such as pick-up and delivery efficiency. However, the geographical scope of operations across multiple cities brings challenges due to the sparsity of user behavior data, hindering accurate predictions. Despite cross-city prediction methods potentially solving this problem by relying on the label of overlapping users in different cities, annotating these overlapping users is expensive. Additionally, the dynamic and diverse nature of user behaviors complicates feature transfer between cities. In this work, we define the logistics demand prediction problem as forecasting pick-up and delivery demand for zones, the smallest operational units in logistics systems, in different cities. To address the challenge, we propose TSTL, a Transferable Spatio-Temporal Learning framework for cross-city logistics prediction with sparse user data. TSTL advances existing methods from two aspects: (1) User-level invariant representation module extracts consistent user representations for overlapping and non-overlapping users across cities. (2) User-zone graph aggregation module enhances user embeddings by integrating dynamic interactions, such as logistics behaviors, into inherent user relations. Finally, the multi-city transfer module fine-tunes model parameters for city-invariant knowledge adoption and predicts future logistics demand. We implement and evaluate TSTL on one of the largest logistics systems. Extensive offline experiments and real-world deployment demonstrate the effectiveness of TSTL.

[Download paper here](https://dl.acm.org/doi/abs/10.1145/3711896.3737186)

Recommended citation: Xia, K., Lin, L., Zhang, X., Wang, H., Wang, S., & He, T. (2025, August). A Transferable Spatio-temporal Learning Framework for Cross-city Logistics Demand Prediction. In <i>Proceedings of the 31st ACM SIGKDD Conference on Knowledge Discovery and Data Mining</i> V. 2 (pp. 5071-5082).
