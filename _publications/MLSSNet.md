---
title: "Learning Deep Multi-Level Similarity for Thermal Infrared Object Tracking"
collection: publications
permalink: /publication/MLSSNet
excerpt: 'Existing deep Thermal InfraRed (TIR) trackers only use semantic features to represent the TIR object, which lack the sufficient discriminative capacity for handling distractors. This becomes worse when the feature extraction network is only trained on RGB images. To address this issue, we propose a multi-level similarity model under a Siamese framework for robust TIR object tracking.'
date: 2020-07-12
venue: 'IEEE Transactions on Multimedia'
paperurl: 'https://www.researchgate.net/publication/342859300_Learning_Deep_Multi-Level_Similarity_for_Thermal_Infrared_Object_Tracking'
---
Existing deep Thermal InfraRed (TIR) trackers only use semantic features to represent the TIR object, which lack the sufficient discriminative capacity for handling distractors. This becomes worse when the feature extraction network is only trained on RGB images. To address this issue, we propose a multi-level similarity model under a Siamese framework for robust TIR object tracking. Specifically, we compute different pattern similarities using the proposed multi-level similarity network. One of them focuses on the global semantic similarity and the other computes the local structural similarity of the TIR object. These two similarities complement each other and hence enhance the discriminative capacity of the network for handling distractors. In addition, we design a simple while effective relative entropy based ensemble subnetwork to integrate the semantic and structural similarities. This subnetwork can adaptive learn the weights of the semantic and structural similarities at the training stage. To further enhance the discriminative capacity of the tracker, we propose a large-scale TIR video sequence dataset for training the proposed model. To the best of our knowledge, this is the first and the largest TIR object tracking training dataset to date. The proposed TIR dataset not only benefits the training for TIR object tracking but also can be applied to numerous TIR visual tasks. Extensive experimental results on three benchmarks demonstrate that the proposed algorithm performs favorably against the state-of-the-art methods.

[Download paper here](https://www.researchgate.net/publication/342859300_Learning_Deep_Multi-Level_Similarity_for_Thermal_Infrared_Object_Tracking) and [Code from here](https://github.com/QiaoLiuHit/MLSSNet)

## Citation
If you use the code or dataset, please consider citing our paper.
```
@article{MLSSNet,
  title={Learning deep multi-level similarity for thermal infrared object tracking},
  author={Liu, Qiao and Li, Xin and He, Zhenyu and Fan, Nana and Yuan, Di and Wang, Hongpeng},
  journal={IEEE Transactions on Multimedia},
  year={2020}
}
```
