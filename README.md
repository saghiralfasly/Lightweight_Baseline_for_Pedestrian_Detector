## Lightweight_Baseline_Pedestrian_Detection
Caffe prototext file of the lightweight baseline for pedestrian detection proposed in [Auto-Zooming CNN-Based Framework for Real-Time Pedestrian Detection in Outdoor Surveillance Videos](https://ieeexplore.ieee.org/document/8781786)
by:

`Saghir Alfasly, Beibei Liu, Yongjian Hu, Yufei Wang, Chang-Tsun Li.`


## Overview
The feature extractor consists of one convolutional layer followed by seven sequenced depthwise separable convolutional layers. The following figure illustrates the proposed model and its characteristics.
With the exception of the first layer that uses regular convolution, we employ depthwise separable convolution for the rest layers. We rebuilt Caffe with [depthwise layer](https://github.com/farmingyard/caffe-mobilenet). The baseline structure is explain in detail in the [paper.](https://ieeexplore.ieee.org/document/8781786).


Far pedestrian detection performance is shown in the video demo in [IEEE Xplore.](https://ieeexplore.ieee.org/document/8781786) 


![alt text](https://github.com/saghiralfasly/Lightweight_Baseline_for_Pedestrian_Detector/blob/master/images/Lightweight-detector.png)


Note: the prototext file contains the baseline without prediction part.

### Work citation
```
@ARTICLE{8781786, 
author={S. {Alfasly} and B. {Liu} and Y. {Hu} and Y. {Wang} and C. {Li}}, 
journal={IEEE Access}, 
title={Auto-Zooming CNN-Based Framework for Real-Time Pedestrian Detection in Outdoor Surveillance Videos}, 
year={2019}, 
volume={7}, 
pages={105816-105826}, 
doi={10.1109/ACCESS.2019.2931915}}
```
