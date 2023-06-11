## Awesome-Depth-Estimation



本仓库由[公众号【自动驾驶之心】](https://mp.weixin.qq.com/s?__biz=Mzg2NzUxNTU1OA==&mid=2247542481&idx=1&sn=c6d8609491a128233c3c3b91d68d22a6&chksm=ceb80b18f9cf820e789efd75947633aec9d2f1e8b58c29e5051c05a64b21ae63c244d54886a1&token=11182364&lang=zh_CN#rd) 团队整理，欢迎关注，一览最前沿的技术分享！

自动驾驶与AI学习社区：欢迎加入国内首个自动驾驶开发者社区！这里有最全面有效的自动驾驶与AI学习路线（感知/定位/融合）和自动驾驶与AI公司内推机会！



## 一、综述 Survey

Deep Learning based Monocular Depth Prediction_ Datasets, Methods and Applications

Single Image Depth Estimation An Overview

Outdoor Monocular Depth Estimation A Research Review

A Survey on Deep Learning Techniques for Stereo-based Depth Estimation

On the Synergies between Machine Learning and Binocular Stereo for Depth Estimation from Images: a Survey

Deep Depth Completion from Extremely SparseData: A Survey

## 二、单目深度估计

### 1. 监督学习

BTS: From Big to Small

[[Code]](https://github.com/cleinc/bts)

Boosting monocular depth with panoptic segmentation maps (WACV2021)

Lightweight Monocular Depth Estimation

### 2. 自监督学习

Digging Into Self-Supervised Monocular Depth Estimation

[[Code]](https://github.com/nianticlabs/monodepth2)

SuperDepth: Self-Supervised, Super-Resolved Monocular Depth Estimation

On the uncertainty of self-supervised monocular depth estimation (CVPR2020)

[[Code]](https://github.com/mattpoggi/mono-uncertainty)

Self-Supervised Sparse-to-Dense: Self-Supervised Depth Completion from LiDAR and Monocular Camera

[[Code]](https://github.com/fangchangma/self-supervised-depth-completion)

Transformers in Self-Supervised Monocular Depth Estimation with Unknown Camera Intrinsics

BiFuse++ : Self-supervised and Efficient Bi-projection Fusion for 360°Depth Estimation

### 3. 半监督学习

Semi-supervised deep learning for monocular depth map prediction (CVPR2017)

Semi-Supervised Learning with Mutual Distillation for Monocular Depth Estimation

### 4. 无监督学习

Unsupervised Learning of Depth, Optical Flow and Pose with Occlusion from 3D Geometry (TIP2020)

[[Code]](https://github.com/guangmingw/DOPlearning)

Unsupervised Monocular Depth Estimation with Left-Right Consistency

LightDepth: A Resource Efficient Depth Estimation Approach for Dealing with Ground Truth Sparsity viaCurriculum Learning

[[Code]](https://github.com/fatemehkarimii/LightDepth)

## 三、基于双目计算的深度估计

### 1. 监督学习

Occlusions, Motion and Depth Boundaries with a Generic Network for Disparity, Optical Flow or Scene FlowEstimation (ECCV2018)

GA-Net: Guided Aggregation Net for End-to-End Stereo Matching (CVPR2019)

Learning for Disparity Estimation Through Feature Constancy (CVPR2018)

OmniMVS: End-to-End Learning for Omnidirectional Stereo Matching (ICCV2019)

MVSCRF: Learning Multi-View Stereo With Conditional Random Fields (ICCV2019)

Multi-View Stereo by Temporal Nonparametric Fusion (ICCV2019)

Depth Estimation maps of lidar and stereo images

## 2. 无监督学习

Practical deep stereo (pds):Toward applications-friendly deep stereo matching (NIPS2018)

End-to-end learning of geometry and context for deep stereo regression (ICCV2017)

Pyramid stereo matching network (CVPR2018)

[[Code]](https://github.com/JiaRenChang/PSMNet)

Unsupervised adaptation for deep stereo (ICCV2017)

[[Code]](https://github.com/CVLAB-Unibo/Unsupervised-Adaptation-for-Deep-Stereo)

### 3. 自监督学习

SegStereo: Exploiting semantic information for disparity estimation(ECCV2018)

[[Code]](https://github.com/yangguorun/SegStereo)

### 四、多方法深度估计

Unifying Flow,Stereo and Depth Estimation

[[Code]](https://github.com/autonomousvision/unimatch)