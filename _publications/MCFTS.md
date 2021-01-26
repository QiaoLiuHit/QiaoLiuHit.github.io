---
title: "Deep Convolutional Neural Networks for Thermal Infrared Object Tracking"
collection: publications
permalink: /publication/MCFTS
excerpt: 'In this paper, we propose a correlation filter based ensemble tracker with multi-layer convolutional features for thermal infrared tracking (MCFTS).'
date: 2017-11-15
venue: 'Knowledge-Based Systems'
paperurl: 'https://www.researchgate.net/publication/318714772_Deep_Convolutional_Neural_Networks_for_Thermal_Infrared_Object_Tracking'

---
Unlike the visual object tracking, thermal infrared object tracking can track a target object in total darkness. 
Therefore, it has broad applications, such as in rescue and video surveillance at night. 
However, there are few studies in this field mainly because thermal infrared images have several unwanted attributes, which make it difficult to obtain the discriminative features of the target. 
Considering the powerful representational ability of convolutional neural networks and their successful application in visual tracking, we transfer the pre-trained convolutional neural networks based on visible images to thermal infrared tracking. 
We observe that the features from the fully-connected layer are not suitable for thermal infrared tracking due to the lack of spatial information of the target, while the features from the convolution layers are. 
Besides, the features from a single convolution layer are not robust to various challenges. 
Based on this observation, we propose a correlation filter based ensemble tracker with multi-layer convolutional features for thermal infrared tracking (MCFTS). 
Firstly, we use pre-trained convolutional neural networks to extract the features of the multiple convolution layers of the thermal infrared target. 
Then, a correlation filter is used to construct multiple weak trackers with the corresponding convolution layer features. 
These weak trackers give the response maps of the target’s location. 
Finally, we propose an ensemble method that coalesces these response maps to get a stronger one. 
Furthermore, a simple but effective scale estimation strategy is exploited to boost the tracking accuracy. 
To evaluate the performance of the proposed tracker, we carry out experiments on two thermal infrared tracking benchmarks: VOT-TIR 2015 and VOT-TIR 2016. 
The experimental results demonstrate that our tracker is effective and achieves promising performance.

[Download paper here](https://www.researchgate.net/publication/318714772_Deep_Convolutional_Neural_Networks_for_Thermal_Infrared_Object_Tracking) 
and [Code from here](https://github.com/QiaoLiuHit/MCFTS)

## Citation
If you use the code, please consider citing our paper.
```
@article{MCFTS,
  title={Deep convolutional neural networks for thermal infrared object tracking},
  author={Liu, Qiao and Lu, Xiaohuan and He, Zhenyu and Zhang, Chunkai and Chen, Wen-Sheng},
  journal={Knowledge-Based Systems},
  volume={134},
  pages={189--198},
  year={2017}
}
```
