# Multi-rate-Directed-T-GCN
    Aggregate Together We See Through: 
    WiFi-based Through-wall2D Human Pose Estimation via Multi-rate Directed T-GCN


* [Architecture](#architecture)

* [Visulization](#visulization)

* [Result](#result)

## Architecture
![image](https://github.com/fingerk28/MDT-GCN/blob/master/img/Architecture.png)

## Visulization
Our demo for wifi based 2D human pose estimation

Proposed Model | Baseline[2]
---|---
![image](https://github.com/fingerk28/MDT-GCN/blob/master/img/proposed_model.gif)|![image](https://github.com/fingerk28/MDT-GCN/blob/master/img/baseline.gif)


![image](https://github.com/fingerk28/MDT-GCN/blob/master/img/result.png)

## Result
The PCK@20(Percentage of Correct Keypoint)of provided models are shown here:
|Method|single-person|multi-people|                       
| :------| :------: | :------: |
|WiSPPN[1]|  69.82%    | X   |
|person in Wifi[2] | 77.06% | 61.58%|
|**MDT-GCN(ours)**|**82.26%**|**71.58%**|

|Method|through-wall|
| :------| :------: |
|WiSPPN[1]|  58.86%    |
|person in Wifi[2] | 73.67%|
|**MDT-GCN(ours)**|**80.72**%|

[1] Fei Wang, Stanislav Panev, Ziyi Dai, Jinsong Han, and Dong Huang. 2019. Canwifi estimate person pose?arXiv preprint arXiv:1904.00277(2019).

[2] Fei Wang, Sanping Zhou, Stanislav Panev, Jinsong Han, and Dong Huang. 2019.Person-in-WiFi: Fine-grained person perception using WiFi. InProceedings of theIEEE International Conference on Computer Vision. 5452–5461.
