---
title: "PATR: Periodicity-Aware Trajectory Recovery for Express System via Seq2Seq Model"
collection: publications
permalink: /publications/2022-12-04-paper-patr
date: 2022-12-04
venue: 'IEEE Globecom'
paperurl: 'https://ieeexplore.ieee.org/abstract/document/10001476'
citation: 'Zhang, X., Liang, X., Wang, H., Wang, S., & He, T. (2022, December). PATR: Periodicity-Aware Trajectory Recovery for Express System via Seq2Seq Model. In GLOBECOM 2022-2022 IEEE Global Communications Conference (pp. 486-491). IEEE.'
---
The analysis of express trajectory is essential for delivery service optimization and courier management. Express trajectory consists of a large amount of community paths which is different from the trajectory of transportation tools such as taxis which run in the main road of a city. Due to the complexity of the community road networks and the energy constraint of devices, trajectories are collected under a low sampling rate and accuracy. These trajectories need to be recovered and mapped to the road networks for further analysis. Current recovery approaches utilize two-stage or end-to-end models to generate the upsampled trajectories. These methods fail to fully exploit the periodicity relation in historical data, which leads to accuracy losses for complex community road networks. In this paper, we design PATR, a periodicity-aware Seq2Seq model, to recover the couriers' trajectories by leveraging the periodical patterns of the historical data. We conduct experimental evaluations based on real-world GPS data of JD logistics consisting of 836,959 points and 25,726 road segments, and our model outperforms the state-of-the-art baselines by reducing recovery error by 2.4%-21.9%.

[Download paper here](https://ieeexplore.ieee.org/abstract/document/10001476)

Recommended citation: Zhang, X., Liang, X., Wang, H., Wang, S., & He, T. (2022, December). PATR: Periodicity-Aware Trajectory Recovery for Express System via Seq2Seq Model. In <i>GLOBECOM 2022-2022 IEEE Global Communications Conference</i> (pp. 486-491). IEEE.