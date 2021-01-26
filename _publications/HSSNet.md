---
title: "Hierarchical Spatial-aware Siamese Network for Thermal Infrared Object Tracking"
collection: publications
permalink: /publication/HSSNet
excerpt: 'In this paper, we cast the thermal infrared (TIR) object tracking problem as a similarity verification task, which is coupled well to the objective of the tracking task. We propose a TIR tracker via a Hierarchical Spatial-aware Siamese Convolutional Neural Network, named HSSNet. '
date: 2019-02-15
venue: 'Knowledge-Based Systems'
paperurl: 'https://www.researchgate.net/publication/329872126_Hierarchical_Spatial-aware_Siamese_Network_for_Thermal_Infrared_Object_Tracking'

---
Most thermal infrared (TIR) tracking methods are discriminative, treating the tracking problem as a classification task. 
However, the objective of the classifier (label prediction) is not coupled to the objective of the tracker (location estimation). 
The classification task focuses on the between-class difference of the arbitrary objects, while the tracking task mainly deals with the within-class difference of the same objects.
In this paper, we cast the TIR tracking problem as a similarity verification task, which is coupled well to the objective of the tracking task. 
We propose a TIR tracker via a Hierarchical Spatial-aware Siamese Convolutional Neural Network (CNN), named HSSNet. 
To obtain both spatial and semantic features of the TIR object, we design a Siamese CNN that coalesces the multiple hierarchical convolutional layers. 
Then, we propose a spatial-aware network to enhance the discriminative ability of the coalesced hierarchical feature. 
Subsequently, we train this network end to end on a large visible video detection dataset to learn the similarity between paired objects before we transfer the network into the TIR domain. 
Next, this pre-trained Siamese network is used to evaluate the similarity between the target template and target candidates. 
Finally, we locate the candidate that is most similar to the tracked target. 
Extensive experimental results on the benchmarks VOT-TIR 2015 and VOT-TIR 2016 show that our proposed method achieves favorable performance compared to the state-of-the-art methods.

[Download paper here](https://www.researchgate.net/publication/329872126_Hierarchical_Spatial-aware_Siamese_Network_for_Thermal_Infrared_Object_Tracking) 
and [Code from here](https://github.com/QiaoLiuHit/HSSNet)

## Citation
If you use the code, please consider citing our paper.
```
@article{HSSNet,
  title={Hierarchical spatial-aware siamese network for thermal infrared object tracking},
  author={Li, Xin and Liu, Qiao and Fan, Nana and He, Zhenyu and Wang, Hongzhi},
  journal={Knowledge-Based Systems},
  volume={166},
  pages={71--81},
  year={2019}
}
```
