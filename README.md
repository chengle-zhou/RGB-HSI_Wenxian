#### Wenxian | Sentinel-2 & Gaofen-5 | RGB-HSI dataset
---
## Wenxian Dataset for Spectral Super-Resolution from RGB to HSI

***Chengle Zhou, Yunfei Li, and Long Yu***

*April 2024*

---

![image](https://github.com/chengle-zhou/MY-IMAGE/blob/29310b9f10654bcac872d91b97311271a577d6e9/Wenxian/image-2.png)

Fig. 1. Wenxian RGB-HSI dataset. RGB (Sentinel-2), HSI (Gaofen-5), and Groundtruth.

## Introduction

Wenxian dataset is our newly released Wenxin RGB-HSI. The RGB image and the HSI are respectively captured by Sentinel-2 (on November 14, 2019) and GaoFen-5 (on November 10, 2019) over Wenxian, Zhengzhou, Henan Province. Note that, Sentinel-2 data contains 12 spectral bands with three spatial resolutions (i.e., 10, 30, and 60 m). We selected the R, G, and B bands with 10 m spatial resolution to construct an RGB image with 30 m spatial resolution based on mean aggregation downsampling. GaoFen-5 data are collected by the Advanced Hyperspectral Imager (AHSI) sensor, with an image spatial resolution of 30 m and 330 spectral bands from the spectral range 400-2500 nm. For the Wenxian dataset, 78 spectral bands with high signal-to-noise ratio (400-730 nm) in the V-NIR spectral range were selected as the HSI, and the ground-truth (comprising 6 land-cover classes) is made available by us. Soon we will organize and release the full Wenxian dataset.


## Citation

If you find our data helpful in your work, please cite our papers.

* Chengle Zhou, Zhi He*, Liwei Zou, Yunfei Li, Antonio Plaza. HSACT: A Hierarchical Semantic-Aware CNN-Transformer for Remote Sensing Image Spectral Super-Resolution, ***Neurocomputing***, 2025. 636: 129925, doi: 10.1016/j.neucom.2025.129990.
* Chengle Zhou, Zhi He*, Guanglin Lai, and Antonio Plaza. A Selective Semantic Transformer for Spectral Super-Resolution of Multispectral Imagery, ***IEEE Journal of Selected Topics in Applied Earth Observations and Remote Sensing***, 2025, 18:7436-7450. doi: 10.1109/JSTARS.2025.3545039.
* Long Yu, Jun Li, Lin He, Antonio Plaza, Lizhe Wang, and Zhonghui Tang. dSPG: A New Discriminant Superpixel Graph Regularizer and Convolutional Network for Hyperspectral Image Classification, IEEE Transactions on Geoscience and Remote Sensing, 2024, 62:1-18, 5526118. doi: 10.1109/TGRS.2024.3439434.

