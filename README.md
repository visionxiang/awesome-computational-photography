# Computational Photography via Deep Learning

A curated list of awesome resources for topics related to computational photography via deep learning, including but not limited to image mathing, image alignment/registration, image stitching and stabilization. 

We will keep updating it. 

:heavy_exclamation_mark:Updated 2021-09-20.



--------------------------------------------------------------------------------------

<!--TOC-->

## Contents:

- [Image Matching](#Image-Matching)
- [Image Alignment](#Image-Alignment)
- [Image Stitching](#Image-Stitching)
- [Color Harmonization](#Color-Harmonization)
- [Low-Light Enhancement](#Low-Light-Enhancement)
- [Stabilization](#Stabilization)
- [Appendix](#Appendix)

--------------------------------------------------------------------------------------




## Image Matching

Part curated paper list for deep learning-based image matching.

#### Overview

| **Year** | **Pub.** | **Title**                                                    | **Author**                                                   | **Links**                                                    |
| :------: | :------: | :----------------------------------------------------------- | :----------------------------------------------------------- | :----------------------------------------------------------- |
|   2021   |   IJCV   | Image Matching from Handcrafted to Deep Features: A Survey   | Jiayi Ma, Xingyu Jiang, et al.                               | Paper/Code                                                   |
|   2021   |  INFFUS  | A review of multimodal image matching: methods and applications | Xingyu Jiang, Jiayi Ma, et al.                               | Paper/[Data](https://github.com/StaRainJ/Multi-modality-image-matching-database-metrics-methods) |
|   2021   |   ICCV   | <span style="white-space:nowrap;">Matching in the Dark: A Dataset for Matching Image Pairs of Low-light Scenes&emsp; </span> | <span style="white-space:nowrap;">W. Song, Takayuki Okatani, et al.&emsp; </span> | [Paper](https://arxiv.org/abs/2109.03585)/Code               |


#### 2021 

| **Pub.** | **Title**                                                    | **Author**                                                   | **Links**                                                    |
| :------: | :----------------------------------------------------------- | :----------------------------------------------------------- | :----------------------------------------------------------- |
|   PAMI   | <span style="white-space:nowrap;">Joint detection and matching of feature points in multimodal images&emsp; </span> | <span style="white-space:nowrap;">Elad Ben Baruch, Yosi Keller&emsp; </span> | Paper/Code                                                   |
|   TIP    | Multi-Relation Attention Network for Image Patch Matching    | Dou Quan, et al.                                             | Paper/Code                                                   |
|   ICCV   | COTR: Correspondence Transformer for Matching Across Images  | Wei Jiang, Eduard Trulls, et al.                             | [Paper](https://arxiv.org/pdf/2103.14167.pdf)/[Code](https://github.com/ubc-vision/COTR) |
|   ICCV   | Warp Consistency for Unsupervised Learning of Dense Correspondences | Prune Truong, Luc Van Gool, et al.                           | [Paper](https://arxiv.org/abs/2104.03308)/[Code](https://github.com/PruneTruong/DenseMatching) |
|   CVPR   | LoFTR: Detector-Free Local Feature Matching with Transformers | Jiaming Sun, Xiaowei Zhou, et al. | [Paper](https://arxiv.org/abs/2104.00680)/[Code](https://github.com/zju3dv/LoFTR)<br>[Proj](https://zju3dv.github.io/loftr/) |
|   CVPR   | SOLD2: Self-supervised Occlusion-aware Line Description and Detection | Rémi Pautrat, Marc Pollefeys, et al. | [Paper](https://arxiv.org/abs/2104.03362)/[Code](https://github.com/cvg/SOLD2)
|   CVPR   | Convolutional Hough Matching Networks                        |                                                              | [Paper](https://arxiv.org/abs/2103.16831)/[Proj](http://cvlab.postech.ac.kr/research/CHM/) |
|   CVPR   | Learning to Match Features with Seeded Graph Matching Network |                                                              | [Paper](https://arxiv.org/abs/2108.08771)/[Code](https://github.com/vdvchen/SGMNet) |
|   CVPR   | Co-Attention for Conditioned Image Matching                  |                                                              | Paper/Code                                                   |
|   CVPR   | Learning Optical Flow From a Few Matches                     |                                                              | Paper/Code                                                   |
|   CVPR   | SuperGlue: Learning Feature Matching With Graph Neural Networks |                                                              | Paper/Code                                                   |

#### 2020

| **Pub.** | **Title**                                                    | **Author**                                                   | **Links**                                                    |
| :------: | :----------------------------------------------------------- | :----------------------------------------------------------- | :----------------------------------------------------------- |
|   IJCV   | Is There Anything New to Say About SIFT Matching?            | Fabio Bellavia, Carlo Colombo                                | [Paper](https://link.springer.com/article/10.1007/s11263-020-01297-z)/Code |
|   TIP    | Robust Feature Matching Using Spatial Clustering with Heavy Outliers | Xingyu Jiang, Jiayi Ma                                       | Paper/[Code](https://github.com/StaRainJ/RFM-SCAN)           |
|   TIP    | Image Feature Correspondence Selection: A Comparative Study and a New Contribution | Chen Zhao, et al.                                            | Paper/Code                                                   |
|   TIP    | <span style="white-space:nowrap;">A Grassmannian Graph Approach to Affine Invariant Feature Matching&emsp; </span> | <span style="white-space:nowrap;">Mark Moyou, et al.&emsp; </span> | Paper/Code                                                   |

#### 2019

| **Pub.** | **Title**                                                    | **Author**                                                   | **Links**                                                    |
| :------: | :----------------------------------------------------------- | :----------------------------------------------------------- | :----------------------------------------------------------- |
|   IJCV   | Locality Preserving Matching                                 | Jiayi Ma, et al.                                             | [Paper](https://link.springer.com/article/10.1007/s11263-018-1117-z)/[Code](https://github.com/jiayi-ma/LPM) |
|   IJCV   | Cross-Domain Image Matching with Deep Feature Maps           | Bailey Kong, et al.                                          | [Paper](https://link.springer.com/article/10.1007/s11263-018-01143-3#Abs1)/[Code](http://github.com/bkong/MCNCC) |
|   ICCV   | Deep Matching Prior: Test-Time Optimization for Dense Correspondence | Sunghwan Hong, Seungryong Kim                                | Paper/Code                                                   |
|   ICCV   | <span style="white-space:nowrap;">AFD-Net: Aggregated Feature Difference Learning for Cross-Spectral Image Patch Matching&emsp; </span> | <span style="white-space:nowrap;">Dou Quan, Licheng Jiao, et al.&emsp; </span> | [Paper](https://openaccess.thecvf.com/content_ICCV_2019/html/Quan_AFD-Net_Aggregated_Feature_Difference_Learning_for_Cross-Spectral_Image_Patch_Matching_ICCV_2019_paper.html)/Code |
|   ICCV   | GLAMpoints: Greedily Learned Accurate Match Points           |                                                              |                                                              |
|   ICCV   | Fully Convolutional Geometric Features                       | Christopher Choy, Jaesik Park, Vladlen Koltun                | [Paper](http://jaesik.info/publications/data/19_iccv.pdf)/[Code](https://github.com/chrischoy/FCGF) |

#### 2018

| **Pub.** | **Title**                                                    | **Author**                                                   | **Links**                                      |
| :------: | :----------------------------------------------------------- | :----------------------------------------------------------- | :--------------------------------------------- |
|   TIP    | Automatic Registration of Images With Inconsistent Content Through Line-Support Region Segmentation and Geometrical Outlier Removal | Ming Zhao, et al.                                            | Paper/Code                                     |
|   TGRS   | <span style="white-space:nowrap;">Guided Locality Preserving Feature Matching for Remote Sensing Image Registration&emsp; </span> | <span style="white-space:nowrap;">Jiayi Ma, Junjun Jiang, et al.&emsp; </span> | Paper/[Code](https://github.com/jiayi-ma/GLPM) |
|   CVPR   | On the Convergence of PatchMatch and Its Variants            |                                                              | Paper/Code                                     |
|   CVPR   | Learning to Detect Features in Texture Images                |                                                              | Paper/Code                                     |


#### 2017

| **Pub.** | **Title**                                                    | **Author**                                                   | **Links**                                                    |
| :------: | :----------------------------------------------------------- | :----------------------------------------------------------- | :----------------------------------------------------------- |
|   TIP    | Establishing Keypoint Matches on Multimodal Images With Bootstrap Strategy and Global Information | Yong Li, Hongbin Jin, Jiatao Wu, Jie Liu                     | Paper/Code                                                   |
|   ICCV   | Progressive Large Scale-Invariant Image Matching in Scale Space | Lei Zhou, Long Quan                                          | Paper/Code                                                   |
|   ICCV   | Practical and Efficient Multi-View Matching                  |                                                              | Paper/Code                                                   |
|   ICCV   | Misalignment-Robust Joint Filter for Cross-Modal Image Pairs |                                                              | Paper/Code                                                   |
|   CVPR   | <span style="white-space:nowrap;">Convolutional neural network architecture for geometric matching&emsp; </span> | <span style="white-space:nowrap;">I. Rocco, R. Arandjelović,<br>J. Sivic&emsp; </span> | [Paper](https://openaccess.thecvf.com/content_cvpr_2017/papers/Rocco_Convolutional_Neural_Network_CVPR_2017_paper.pdf)/[PAMI19](https://ieeexplore.ieee.org/document/8434328)<br>[Code](https://github.com/ignacio-rocco/cnngeometric_pytorch) |
|   CVPR   | Deep Semantic Feature Matching                               |                                                              | Paper/Code                                                   |
|   CVPR   | HPatches: A Benchmark and Evaluation of Handcrafted and Learned Local Descriptors | Vassileios Balntas, et al.                                   | [Paper](https://arxiv.org/abs/1704.05939)/[Proj](https://hpatches.github.io/) |


#### 2016

| **Pub.** | **Title**                                                    | **Author**                                                   | **Links**                                                    |
| :------: | :----------------------------------------------------------- | :----------------------------------------------------------- | :----------------------------------------------------------- |
|   ECCV   | LIFT: Learned Invariant Feature Transform                    | K. M. Yi, Pascal Fua, et al.                                 | Paper/Code                                                   |
|   ECCV   | Learning Image Matching by Simply Watching Video             |                                                              | Paper/Code                                                   |
|   ECCV   | Novel Coplanar Line-Points Invariants for Robust Line Matching Across Views |                                                              | Paper/Code                                                   |
|   ECCV   | <span style="white-space:nowrap;">Deep Self-correlation Descriptor for Dense Cross-Modal Correspondence&emsp; </span> | <span style="white-space:nowrap;"> S. Kim, Dongbo Min, S. Lin, Kwanghoon Sohn&emsp; </span> | [Paper](https://link.springer.com/chapter/10.1007/978-3-319-46484-8_41)/Code |




## Image Alignment

<!--Image alignment, image registration, homography estimation -->

#### Image Registration

| **Year** | **Pub.** | **Title**                                                    | **Author**                                                   | **Links**                                                    |
| :------: | :------: | :----------------------------------------------------------- | :----------------------------------------------------------- | :----------------------------------------------------------- |
|   2021   |  arXiv05 | Attention for Image Registration (AiR): an unsupervised Transformer approach | Zihao Wang, Hervé Delingette | [Paper](https://arxiv.org/abs/2105.02282)/Code
|   2021   |   CVPR   | Learning-based Image Registration with Meta-Regularization   | Ebrahim Al Safadi, Xubo Song                                 | [Paper](https://openaccess.thecvf.com/content/CVPR2021/papers/Safadi_Learning-Based_Image_Registration_With_Meta-Regularization_CVPR_2021_paper.pdf)/[Code]() |
|   2020   |   TIP    | Cross-Weather Image Alignment via Latent Generative Model with Intensity Consistency | Huabing Zhou, Jiayi Ma, et al.                               | Paper/Code                                                   |
|   2020   |   TIP    | Boosting Structure Consistency for Multispectral and Multimodal Image Registration | Si-Yuan Cao, Hui-Liang Shen, Shu-Jie Chen, Chunguang Li      | Paper/Code                                                   |
|   2020   |   TIP    | Local-Adaptive Image Alignment Based on Triangular Facet Approximation | Jing Li, et al.                                              | Paper/Code                                                   |
|   2020   |   TIP    | Boosting Structure Consistency for Multispectral and Multimodal Image Registration | Si-Yuan Cao, et al.                                          | Paper/Code                                                   |
|   2020   |   ECCV   | RANSAC-Flow: Generic Two-stage Image Alignment               |                                                              | Paper/Code                                                   |
|   2020   |   ECCV   | Aligning Videos in Space and Time                            |                                                              | Paper/Code                                                   |
|   2020   |   CVPR   | Unsupervised Multi-Modal Image Registration via Geometry Preserving Image-to-Image Translation | Moab Arar, Yiftach Ginger, et al.                            | [Paper](https://openaccess.thecvf.com/content_CVPR_2020/papers/Arar_Unsupervised_Multi-Modal_Image_Registration_via_Geometry_Preserving_Image-to-Image_Translation_CVPR_2020_paper.pdf)/Code |
|   2019   |   TIP    | Online Subspace Learning from Gradient Orientations for Robust Image Alignment | Qingqing Zheng, Yi Wang, Pheng Ann Heng                      | Paper/Code                                                   |
|   2019   |   ICCV   | Jointly Aligning Millions of Images With Deep Penalised Reconstruction Congealing | Roberto Annunziata, Christos Sagonas, Jacques Cali           | [Paper](https://openaccess.thecvf.com/content_ICCV_2019/papers/Annunziata_Jointly_Aligning_Millions_of_Images_With_Deep_Penalised_Reconstruction_Congealing_ICCV_2019_paper.pdf)/Code |
|   2018   |   PAMI   | Hierarchical Sparse Representation for Robust Image Registration | Yeqing Li, et al.                                            | Paper/Code                                                   |
|   2018   |  ISPRSJ  | A deep learning framework for remote sensing image registration | Shuang Wang, Licheng Jiao, et al.                            | [Paper](https://www.sciencedirect.com/science/article/abs/pii/S0924271617303891)/Code |
|   2018   |   ECCV   | Multimodal image alignment through a multiscale chain of neural networks with application to remote sensing |                                                              | Paper/Code                                                   |
|   2017   |   CVPR   | <span style="white-space:nowrap;">CLKN: Cascaded Lucas-Kanade Networks for Image Alignment&emsp; </span> | <span style="white-space:nowrap;">Che-Han Chang, Chun-Nan Chou, Edward Y. Chang&emsp; </span> | [Paper](https://openaccess.thecvf.com/content_cvpr_2017/papers/Chang_CLKN_Cascaded_Lucas-Kanade_CVPR_2017_paper.pdf)/Code |


#### Deep Homography Estimation

| **Year** | **Pub.** | **Title**                                                    | **Author**                                                   | **Links**                                                    |
| :------: | :------: | :----------------------------------------------------------- | :----------------------------------------------------------- | :----------------------------------------------------------- |
|   2021   | arXiv07  | Precise Aerial Image Matching based on Deep Homography Estimation |                                                              | [Paper](https://arxiv.org/pdf/2107.08768.pdf)/Code           |
|   2021   | arXiv07  | Depth-Aware Multi-Grid Deep Homography Estimation with Contextual Correlation |                                                              | [Paper](https://arxiv.org/pdf/2107.02524.pdf)/[Code](https://github.com/nie-lang/Multi-Grid-Deep-Homogarphy) |
|   2021   | arXiv03  | Motion Basis Learning for Unsupervised Deep Homography Estimation with Subspace Projection | Nianjin Ye, Shuaicheng Liu, et al.                           | [Paper](https://arxiv.org/pdf/2103.15346.pdf)/[Code](https://github.com/megvii-research/BasesHomo) |
|   2021   |   PAMI   | Rolling Shutter Homography and its Applications              | Yizhen Lao;Omar Ait-Aider                                    | Paper/Code                                                   |
|   2021   |   CVPR   | Deep Lucas-Kanade Homography for Multimodal Image Alignment  | Yiming Zhao, Xinming Huang, Ziming Zhang                     | [Paper](https://arxiv.org/abs/2104.11693)/[Code](https://github.com/placeforyiming/CVPR21-Deep-Lucas-Kanade-Homography) |
|   2021   |   CVPR   | Deep Homography for Efficient Stereo Image Compression       |                                                              | Paper/Code                                                   |
|   2020   |   ECCV   | Content-Aware Unsupervised Deep Homography Estimation        | Jirong Zhang, Shuaicheng Liu, et al.                         | [Paper](https://arxiv.org/abs/1909.05983)/[Code](https://github.com/JirongZhang/DeepHomography?utm_source=catalyzex.com) |
|   2020   |    MM    | SRHEN: Stepwise-Refining Homography Estimation Network via Parsing Geometric Correspondences in Deep Latent Space |                                                              | [Paper](https://dl.acm.org/doi/pdf/10.1145/3394171.3413870)/Code |
|   2020   |   CVPR   | Robust Homography Estimation via Dual Principal Component Pursuit |                                                              | Paper/Code                                                   |
|   2020   |   CVPR   | Deep Homography Estimation for Dynamic Scenes                | Hoang Le, Feng Liu, et al.                                   | [Paper](https://openaccess.thecvf.com/content_CVPR_2020/papers/Le_Deep_Homography_Estimation_for_Dynamic_Scenes_CVPR_2020_paper.pdf)/[Code](https://github.com/lcmhoang/hmg-dynamics) |
|   2019   |   ICCV   | Homography From Two Orientation- and Scale-Covariant Features | Daniel Barath, Zuzana Kukelova                               | [Paper](https://arxiv.org/pdf/1906.11927.pdf)/[Code](https://github.com/danini/homography-from-sift-features) |
|   2018   |   ECCV   | <span style="white-space:nowrap;">GridFace: Face Rectification via Learning Local Homography Transformations &emsp; </span> | <span style="white-space:nowrap;">Erjin Zhou, Zhimin Cao, Jian Sun&emsp; </span> | [Paper](https://openaccess.thecvf.com/content_ECCV_2018/papers/Zhou_GridFace_Face_Rectification_ECCV_2018_paper.pdf)/Code |


#### Medical Registration

| **Year** | **Pub.** | **Title**                                                    | **Author**                                                   | **Links**                                                    |
| :------: | :------: | :----------------------------------------------------------- | :----------------------------------------------------------- | :----------------------------------------------------------- |
|   2020   |   ECCV   | Deep Complementary Joint Model for Complex Scene Registration and Few-shot Segmentation on Medical Images | Yuting He, et al.                                            | [Paper](https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123630749.pdf)/Code |
|   2020   |   CVPR   | DeepFLASH: An Efficient Network for Learning-based Medical Image Registration | Jian Wang, Miaomiao Zhang                                    | [Paper](https://openaccess.thecvf.com/content_CVPR_2020/papers/Wang_DeepFLASH_An_Efficient_Network_for_Learning-Based_Medical_Image_Registration_CVPR_2020_paper.pdf)/[Code](https://github.com/jw4hv/deepflash) |
|   2020   |   CVPR   | Fast Symmetric Diffeomorphic Image Registration with Convolutional Neural Networks | Tony C.W. Mok, Albert C.S. Chung                             | [Paper](https://openaccess.thecvf.com/content_CVPR_2020/papers/Mok_Fast_Symmetric_Diffeomorphic_Image_Registration_with_Convolutional_Neural_Networks_CVPR_2020_paper.pdf)/Code |
|   2019   |   ICCV   | Recursive Cascaded Networks for Unsupervised Medical Image Registration | Shengyu Zhao, Yue Dong, et al.                               | [Paper](https://openaccess.thecvf.com/content_ICCV_2019/papers/Zhao_Recursive_Cascaded_Networks_for_Unsupervised_Medical_Image_Registration_ICCV_2019_paper.pdf)/[Code](https://github.com/zsyzzsoft/Recursive-Cascaded-Networks) |
|   2019   |   CVPR   | Networks for Joint Affine and Non-parametric Image Registration | Zhengyang Shen, Xu Han, et al.                               | [Paper](https://openaccess.thecvf.com/content_CVPR_2019/papers/Shen_Networks_for_Joint_Affine_and_Non-Parametric_Image_Registration_CVPR_2019_paper.pdf)/[Code](https://github.com/uncbiag/registration) |
|   2019   |   CVPR   | Metric Learning for Image Registration                       | M. Niethammer, R. Kwitt, François-Xavier Vialard             | [Paper](https://openaccess.thecvf.com/content_CVPR_2019/papers/Niethammer_Metric_Learning_for_Image_Registration_CVPR_2019_paper.pdf)/[Code](https://github.com/uncbiag/registration) |
|   2018   |   CVPR   | <span style="white-space:nowrap;">An Unsupervised Learning Model for Deformable Medical Image Registration&emsp; </span> | <span style="white-space:nowrap;">Guha Balakrishnan, et al.&emsp; </span> | [Paper](https://openaccess.thecvf.com/content_cvpr_2018/papers/Balakrishnan_An_Unsupervised_Learning_CVPR_2018_paper.pdf)/Code |



## Image Stitching


| **Year** | **Pub.** | **Title**                                                    | **Author**                                                   | **Links**                                                    |
| :------: | :------: | :----------------------------------------------------------- | :----------------------------------------------------------- | :----------------------------------------------------------- |
|   2021   |   TIP    | Unsupervised Deep Image Stitching: Reconstructing Stitched Features to Images | Lang Nie, Shuaicheng Liu, et al.                             | [Paper](https://arxiv.org/abs/2106.12859)/[Code](https://github.com/nie-lang/UnsupervisedDeepImageStitching) |
|   2021   |   TIP    | Image Stitching Based on Semantic Planar Region Consensus    | Aocheng Li, Jie Guo, Yanwen Guo                              | Paper/Code                                                   |
|   2021   |   TVCG   | Content-Preserving Image Stitching With Piecewise Rectangular Boundary Constraints | Yun Zhang, Yu-Kun Lai, Fang-Lue Zhang                        | Paper/Code                                                   |
|   2021   |    PR    | Edge-guided Composition Network for Image Stitching          | Qinyan Dai, et al.                                           | [Paper](https://www.sciencedirect.com/science/article/abs/pii/S0031320321002065)/Code |
|   2021   |    PR    | Image stitching based on angle-consistent warping            | Yinqi Chen, et al.                                           | [Paper](https://www.sciencedirect.com/science/article/abs/pii/S0031320321001801)/Code |
|   2021   |   SPL    | End-to-End Image Stitching Network via Multi-Homography Estimation | Dae-Young Song, et al.                                       | [Paper](https://ieeexplore.ieee.org/abstract/document/9393563)/Code |
|   2021   |   ICCV   | Minimal Solutions for Panoramic Stitching Given Gravity Prior | Yaqing Ding, Daniel Barath, Zuzana Kukelova                  | [Paper](https://arxiv.org/abs/2012.00465)/Code               |
|   2021   |   CVPR   | <span style="white-space:nowrap;">Leveraging Line-Point Consistence To Preserve Structures for Wide Parallax Image Stitching&emsp; </span> | <span style="white-space:nowrap;">Qi Jia, ZhengJun Li, et al.&emsp; </span> | [Paper](https://openaccess.thecvf.com/content/CVPR2021/papers/Jia_Leveraging_Line-Point_Consistence_To_Preserve_Structures_for_Wide_Parallax_Image_CVPR_2021_paper.pdf)/[Code](https://github.com/dut-media-lab/Image-Stitching) |
|          |          |                                                              |                                                              |                                                              |
|          |          |                                                              |                                                              |                                                              |
|   2020   | arXiv12  | Learning Edge-Preserved Image Stitching from Large-Baseline Deep Homography | Lang Nie, et al.                                             | [Paper](https://arxiv.org/pdf/2012.06194.pdf)/Code           |
|   2020   | arXiv04  | Vanishing Point Guided Natural Image Stitching               | Kai Chen, Jian Yao, et al.                                   | [Paper](https://arxiv.org/abs/2004.02478)/Code               |
|   2020   |   PAMI   | CrossNet++: Cross-scale Large-parallax Warping for Reference-based Super-resolution | Yang Tan, et al.                                             | Paper/Code                                                   |
|   2020   |   TIP    | Parallax Tolerant Light Field Stitching for Hand-Held Plenoptic Cameras | Xin Jin;Pei Wang;Qionghai Dai                                | Paper/Code                                                   |
|   2020   |   TIP    | An Unordered Image Stitching Method Based on Binary Tree and Estimated Overlapping Area | Zhong Qu, et al.                                             | Paper/Code                                                   |
|   2020   |   TIP    | Single-Perspective Warps in Natural Image Stitching          | Tianli Liao, Nan Li                                          | [Paper](https://arxiv.org/abs/1802.04645)/[Code1](https://github.com/tlliao/Single-perspective-warps)<br>[Code2](https://github.com/tlliao/Single-perspective-warps-multiple) |
|   2020   |   TMM    | Stereoscopic Image Stitching via Disparity-Constrained Warping and Blending | Xiaoting Fan, et al.                                         | Paper/Code                                                   |
|   2020   |   TMM    | Image-Only Real-Time Incremental UAV Image Mosaic for Multi-Strip Flight | Fangbing Zhang, et al.                                       | Paper/Code                                                   |
|   2020   |  JSTSP   | Attentive Deep Stitching and Quality Assessment for 360° Omnidirectional Images | Jia Li, et al.                                               | [Paper](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=8903278&casa_token=-GdkCo2qmfIAAAAA:GbByoLo8XDRu7PCBD-kH-bvgT6R9Zl9_P9KtnTRz47jMbAqDPBve9UrBWTkA9sGpwa1OgLc&tag=1)/Code |
|   2020   |   ECCV   | Image Stitching and Rectification for Hand-Held Cameras      | Bingbing Zhuang, Quoc-Huy Tran                               | [Paper](https://www.nec-labs.com/uploads/Documents/Media-Analytics/research-papers/Image_Stitching_and_Rectification_for_Hand-Held_Cameras.pdf)/[Proj](https://www.nec-labs.com/~mas/RS-APAP/) |
|   2020   |   CVPR   | <span style="white-space:nowrap;">Warping Residual Based Image Stitching for Large Parallax&emsp; </span> | <span style="white-space:nowrap;">Kyu-Yul Lee, Jae-Young Sim&emsp; </span> | [Paper](https://openaccess.thecvf.com/content_CVPR_2020/papers/Lee_Warping_Residual_Based_Image_Stitching_for_Large_Parallax_CVPR_2020_paper.pdf)/Code |
|          |          |                                                              |                                                              |                                                              |
|          |          |                                                              |                                                              |                                                              |
|   2019   |   TIP    | Robust Alignment for Panoramic Stitching Via an Exact Rank Constraint | Yuelong Li, Mohammad Tofighi, Vishal Monga                   | Paper/Code                                                   |
|   2019   |   TMM    | A Novel Projective-Consistent Plane Based Image Stitching Method | Jin Zheng, et al.                                            | Paper/Code                                                   |
|   2019   |   TMM    | <span style="white-space:nowrap;">Shape-Optimizing and Illumination-Smoothing Image Stitching&emsp; </span> | Shiguang Liu, Qingpeng Chai                                  | Paper/Code                                                   |
|   2019   |   BMVC   | Video Stitching for Linear Camera Arrays <span style="color:blue;">`CNNStitch`</span> | Wei-Sheng Lai, et al.                                        | [Paper](https://jankautz.com/publications/VideoStitching_BMVC19.pdf)/[arXiv](https://arxiv.org/abs/1907.13622)<br>[Proj](http://vllab.ucmerced.edu/wlai24/video_stitching/) |
|   2019   |   GRSM   | Remote Sensing Image Mosaicking: Achievements and Challenges | Xinghua Li, Ruitao Feng, et al.                              | [Paper](https://ieeexplore.ieee.org/document/8937068)/Code   |
|   2018   |   TIP    | Dynamic Video Stitching via Shakiness Removing               | Yongwei Nie, et al.                                          | [Paper](https://ieeexplore.ieee.org/document/8003352)/[Code](https://github.com/SuTanTank/VideoStitchingViaShakinessRemoving) |
|   2018   |   TMM    | Parallax-Tolerant Image Stitching Based on Robust Elastic Warping | Jing Li, et al.                                              | [Paper](https://ieeexplore.ieee.org/document/8119833)/[Code](https://github.com/gain2217/Robust_Elastic_Warping) |
|   2018   |   TMM    | Quasi-Homography Warps in Image Stitching                    | Nan Li, Yifang Xu, Chao Wang                                 | Paper/Code                                                   |
|   2018   |   ECCV   | Object-centered image stitching                              | Charles Herrmann, Ramin Zabih, et al                         | Paper/Code                                                   |
|   2018   |   ECCV   | Robust image stitching with multiple registrations           | Herrmann, Charles, Zabih, Ramin, et al.                      | Paper/Code                                                   |
|   2017   |  CVPR17  | Direct Photometric Alignment by Mesh Deformation             |                                                              | Paper/Code                                                   |
|   2016   |   ECCV   | SEAGULL: Seam-Guided Local Alignment for Parallax-Tolerant Image Stitching |                                                              | Paper/Code                                                   |
|   2016   |   ECCV   | Natural Image Stitching with the Global Similarity Prior     | <span style="white-space:nowrap;">Y.-S. Chen, Yung-Yu Chuang&emsp; </span> | [Paper](https://link.springer.com/chapter/10.1007/978-3-319-46454-1_12)/[Code](https://github.com/nothinglo/NISwGSP) |
|   2016   |   TOG    | Jump: Virtual reality video                                  |                                                              | Paper/Code                                                   |
|   2012   |   TOG    | Panorama weaving: fast and flexible seam processing          | Brian Summa, et al.                                          | [Paper](http://www.sci.utah.edu/~bsumma/projects/weaving/index.html)/[Proj](http://www.sci.utah.edu/~bsumma/projects/weaving/index.html) |


#### Stitching Evaluation

| **Year** | **Pub.** | **Title**                                                    | **Author**                                                   | **Links**                                                    |
| :------: | :------: | :----------------------------------------------------------- | :----------------------------------------------------------- | :----------------------------------------------------------- |
|   2020   |   TIP    | A Metric for Video Blending Quality Assessment               | Zhe Zhu, et al.                                              | Paper/Code                                                   |
|   2019   |   TIP    | <span style="white-space:nowrap;">Subjective and Objective Quality Assessment of Stitched Images for Virtual Reality&emsp; </span> | <span style="white-space:nowrap;">Pavan C. Madhusudana, Rajiv Soundararajan&emsp; </span> | Paper/Code                                                   |
|   2019   |    MM    | Cross-Reference Stitching Quality Assessment for 360° Omnidirectional Images | Jia Li, et al.                                               | [Paper](http://cvteam.net/papers/2019-ACMMM-Cross-Reference%20Stitching%20Quality%20Assessment%20for%20360%C2%B0%20Omnidirectional%20Images.pdf)/[Proj](http://cvteam.net/projects/MM19-CROSS/MM2019.html) |


#### Stitching Beyond

| **Year** | **Pub.** | **Title**                                                    | **Author**                                                   | **Links**                                                  |
| :------: | :------: | :----------------------------------------------------------- | :----------------------------------------------------------- | :--------------------------------------------------------- |
|   2020   |   PAMI   | Ambiguity-Free Radiometric Calibration for Internet Photo Collections | Zhipeng Mo, Yasuyuki Matsushit, et al.                       | [Paper](https://ieeexplore.ieee.org/document/8651349)/Code |
|   2019   |   TOG    | Video Extrapolation Using Neighboring Frames                 | Sangwoo Lee, et al.                                          | [Paper](https://dl.acm.org/doi/10.1145/3196492)/Code       |
|   2019   |   TIP    | <span style="white-space:nowrap;">Panoramic Background Image Generation for PTZ Cameras&emsp; </span> | <span style="white-space:nowrap;">Hongwei Yong, et al.&emsp; </span> | Paper/Code                                                 |



## Color Harmonization

| **Year** | **Pub.** | **Title**                            | **Author**                         | **Links**  |
| :------: | :------: | :----------------------------------- | :--------------------------------- | :--------- |
|   2021   |   ICCV   | Image Harmonization With Transformer | Zonghui Guo, Dongsheng Guo, et al. | Paper/Code |


## Low-Light Enhancement

| **Year** | **Pub.** | **Title**                            | **Author**                         | **Links**  |
2021 | arXiv04 | Low-Light Image and Video Enhancement Using Deep Learning: A Survey | Chongyi Li, Chen Change Loy, et al. | [Paper](https://arxiv.org/abs/2104.10729)/[Proj](https://github.com/Li-Chongyi/Lighting-the-Darkness-in-the-Deep-Learning-Era-Open) 


## Stabilization

| **Year** | **Pub.** | **Title**                                                    | **Author**                                                   | **Links**                                                    |
| :------: | :------: | :----------------------------------------------------------- | :----------------------------------------------------------- | :----------------------------------------------------------- |
|   2021   |   ICCV   | Hybrid Neural Fusion for Full-Frame Video Stabilization      | Yu-Lun Liu, Wei-Sheng Lai, et al.                            | [Paper](https://arxiv.org/pdf/2102.06205.pdf)/[Code](https://github.com/alex04072000/FuSta)<br>[Proj](https://alex04072000.github.io/FuSta/) |
|   2021   |   CVPR   | Real-Time Selfie Video Stabilization                         |                                                              | [Paper](https://openaccess.thecvf.com/content/CVPR2021/papers/Yu_Real-Time_Selfie_Video_Stabilization_CVPR_2021_paper.pdf)/[Code](https://github.com/jiy173/selfievideostabilization) |
|   2021   |   CVPR   | Digital Gimbal: End-to-End Deep Image Stabilization With Learnable Exposure Times |                                                              | Paper/Code                                                   |
|   2020   |   TIP    | PWStableNet: Learning Pixel-Wise Warping Maps for Video Stabilization | Minda Zhao;Qiang Ling                                        | Paper/[Code](https://github.com/mindazhao/pix-pix-warping-video-stabilization) |
|   2020   |   CVPR   | Learning Video Stabilization Using Optical Flow              |                                                              | Paper/Code                                                   |
|   2019   |   CVPR   | <span style="white-space:nowrap;">Robust Video Stabilization by Optimization in CNN Weight Space&emsp; </span> | <span style="white-space:nowrap;">J. Yu, Ravi Ramamoorthi&emsp; </span> | [Paper](https://openaccess.thecvf.com/content_CVPR_2019/papers/Yu_Robust_Video_Stabilization_by_Optimization_in_CNN_Weight_Space_CVPR_2019_paper.pdf)/Code |
|   2019   |   SIGA   | Deep Iterative Frame Interpolation for Full-frame Video Stabilization |                                                              | Paper/Code                                                   |
|   2019   |   TIP    | Deep Online Video Stabilization With Multi-Grid Warping Transformation Learning | Miao Wang, et al.                                            | [Paper](https://ieeexplore.ieee.org/document/8554287)/[Code](https://github.com/cxjyxxme/deep-online-video-stabilization) |
|   2019   |   TOG    | Joint Stabilization and Direction of 360° Videos             | C. Tang, Feng Liu, et al.                                    | [Paper](https://dl.acm.org/doi/abs/10.1145/3211889)/Code     |
|   2018   |   ECCV   | Selfie Video Stabilization                                   |                                                              | Paper/Code                                                   |
|   2018   |   CGF    | Deep Video Stabilization Using Adversarial Networks          | Sen-Zhe Xu, Jun Hu, et al.                                   | [Paper](https://onlinelibrary.wiley.com/doi/abs/10.1111/cgf.13566)/Code |



## Appendix

- [Awesome Image Alignment and Stitching](https://github.com/tzxiang/awesome-image-alignment-and-stitching)


