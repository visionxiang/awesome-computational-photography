# Computational Photography via Deep Learning

A curated list of awesome resources for topics related to computational photography via deep learning, including but not limited to image matching, image alignment/registration, image stitching and stabilization. 

:heavy_exclamation_mark:Updated 2022-07.



--------------------------------------------------------------------------------------

<!--TOC-->

## Contents:

- [Image Stitching](#Image-Stitching)
- [Image Matching](#Image-Matching)
- [Image Alignment](#Image-Alignment)
- [Color Harmonization](#Color-Harmonization)
- [Low-Light Enhancement](#Low-Light-Enhancement)
- [Stabilization](#Stabilization)
- [Beyond](#Beyond)
- [Appendix](#Appendix)

--------------------------------------------------------------------------------------


## Image Stitching

**2022**

| **Year** | **Pub.** | **Title**       | **Links**                |
| :------: | :------: | :----------------------------------------------------------- | :----------------------------------------------------------- |
|   --     |  arXiv | Warped Convolution Networks for Homography Estimation <br> <sub><sup>*Xinrui Zhan, Jianke Zhu, et al.*</sup><sub> | [Paper](https://arxiv.org/abs/2206.11657)/Code
|   --     |  arXiv | Deep Rotation Correction without Angle Prior <br> <sub><sup>*Lang Nie, Shuaicheng Liu, et al.*</sup><sub>  | [Paper](https://arxiv.org/abs/2207.03054)/[Code](https://github.com/nie-lang/RotationCorrection)
|   --     |  arXiv | Natural Image Stitching Using Depth Maps  <br> <sub><sup>*Tianli Liao, Nan Li*</sup><sub>  | [Paper](https://arxiv.org/pdf/2202.06276.pdf)/Code 
|   --     |  arXiv | Pixel-wise Deep Image Stitching  <br> <sub><sup>*Hyeokjun Kweon, et al.*</sup><sub>  | [Paper](https://arxiv.org/abs/2112.06171)/Code
|   2022   |  CVPR  | Geometric Structure Preserving Warp for Natural Image Stitching  <br> <sub><sup>*Peng Du, Jifeng Ning, et al.*</sup><sub>  | [Paper](https://openaccess.thecvf.com/content/CVPR2022/html/Du_Geometric_Structure_Preserving_Warp_for_Natural_Image_Stitching_CVPR_2022_paper.html)/[Code](https://github.com/flowerDuo/GES-GSP-Stitching) 
|   2022   |  CVPR  | Automatic Color Image Stitching Using Quaternion Rank-1 Alignment <br> <sub><sup>*Jiaxue Li, Yicong Zhou*</sup><sub> | [Paper](https://openaccess.thecvf.com/content/CVPR2022/html/Li_Automatic_Color_Image_Stitching_Using_Quaternion_Rank-1_Alignment_CVPR_2022_paper.html)/Code
|   2022   |  CVPR  | Deep Rectangling for Image Stitching: A Learning Baseline <br> <sub><sup>*Lang Nie, Chunyu Lin, et al.*</sup><sub>  | [Paper](https://arxiv.org/abs/2203.03831)/[Code](https://github.com/nie-lang/DeepRectangling)
|   2022   |  CVPR  | Unsupervised Homography Estimation With Coplanarity-Aware GAN <br> <sub><sup>*Mingbo Hong, Shuaicheng Liu, et al.*</sup><sub>  | [Paper](https://openaccess.thecvf.com/content/CVPR2022/html/Hong_Unsupervised_Homography_Estimation_With_Coplanarity-Aware_GAN_CVPR_2022_paper.html)/[Code](https://github.com/megvii-research/HomoGAN)
|   2022   |  CVPR  | Iterative Deep Homography Estimation  <br> <sub><sup>*Si-Yuan Cao, Jianxin Hu, et al.*</sup><sub>  | [Paper](https://openaccess.thecvf.com/content/CVPR2022/html/Cao_Iterative_Deep_Homography_Estimation_CVPR_2022_paper.html)/[Code](https://github.com/imdumpl78/IHN)
|   2022   | TCSVT  | Depth-Aware Multi-Grid Deep Homography Estimation with Contextual Correlation   <br> <sub><sup>*Lang Nie, Shuaicheng Liu, et al.*</sup><sub>     | [Paper](https://arxiv.org/pdf/2107.02524.pdf)/[Code](https://github.com/nie-lang/Multi-Grid-Deep-Homogarphy) |
|  2022   |  NeuCom | Learning edge-preserved image stitching from multi-scale deep homography <br> <sub><sup>*Lang Nie, Chunyu Lin, et al.*</sup><sub>  | [Paper](https://www.sciencedirect.com/science/article/pii/S0925231221018701?casa_token=Ipwo0k75uHYAAAAA:xuMPfZ_BU8mG-zbrHcYKnsNAv4hRnvflFysjigPfRIeDQ17ep6g958A7QZVYzUxnm2TcfF3hWg)/Code 


**2021**

| **Year** | **Pub.** | **Title**                                                    | **Links**                                                    |
| :------: | :------: | :----------------------------------------------------------- | :----------------------------------------------------------- |
|   2021   | ICCV  | Minimal Solutions for Panoramic Stitching Given Gravity Prior  <br> <sub><sup>*Yaqing Ding, Daniel Barath, Zuzana Kukelova*</sup><sub>           | [Paper](https://arxiv.org/abs/2012.00465)/Code               |
|   2021   | ICCV  | Motion Basis Learning for Unsupervised Deep Homography Estimation with Subspace Projection `DH`   <br> <sub><sup>*Nianjin Ye, Shuaicheng Liu, et al.*</sup><sub>     | [Paper](https://openaccess.thecvf.com/content/ICCV2021/html/Ye_Motion_Basis_Learning_for_Unsupervised_Deep_Homography_Estimation_With_Subspace_ICCV_2021_paper.html)/[Code](https://github.com/megvii-research/BasesHomo) |
|   2021   |   CVPR   | <span style="white-space:nowrap;">Leveraging Line-Point Consistence To Preserve Structures for Wide Parallax Image Stitching&emsp; </span> <br> <sub><sup>*Qi Jia, ZhengJun Li, et al.*</sup><sub> | [Paper](https://openaccess.thecvf.com/content/CVPR2021/papers/Jia_Leveraging_Line-Point_Consistence_To_Preserve_Structures_for_Wide_Parallax_Image_CVPR_2021_paper.pdf)/[Code](https://github.com/dut-media-lab/Image-Stitching) |
|   2021   |   CVPR   | Deep Lucas-Kanade Homography for Multimodal Image Alignment  <br> <sub><sup>*Yiming Zhao, Xinming Huang, Ziming Zhang*</sup><sub>             | [Paper](https://arxiv.org/abs/2104.11693)/[Code](https://github.com/placeforyiming/CVPR21-Deep-Lucas-Kanade-Homography) |
|   2021   |   CVPR   | Deep Homography for Efficient Stereo Image Compression       <br> <sub><sup>*Xin Deng, Mai Xu, et al.*</sup><sub>     | [Paper](https://openaccess.thecvf.com/content/CVPR2021/papers/Deng_Deep_Homography_for_Efficient_Stereo_Image_Compression_CVPR_2021_paper.pdf)/[Code](https://github.com/ywz978020607/HESIC)                                                   |
|   2021   |   PAMI   | Rolling Shutter Homography and its Applications              <br> <sub><sup>*Yizhen Lao, Omar Ait-Aider*</sup><sub>   | [Paper](https://ieeexplore.ieee.org/abstract/document/9020067?casa_token=wY4f6AyKIm8AAAAA:HqPuYmhaCYKwkXV0szDhSJVPC1cpyUF_mza3du9CjRvDfVvYpza-kiXscNGbD3emJjt4PUAR)/Code     |
|   2021   |   TIP    | Unsupervised Deep Image Stitching: Reconstructing Stitched Features to Images `DH`   <br> <sub><sup>*Lang Nie, Shuaicheng Liu, et al.*</sup><sub>            | [Paper](https://arxiv.org/abs/2106.12859)/[Code](https://github.com/nie-lang/UnsupervisedDeepImageStitching) |
|   2021   |   TIP    | Image Stitching Based on Semantic Planar Region Consensus    <br> <sub><sup>*Aocheng Li, Jie Guo, Yanwen Guo*</sup><sub>        | [Paper](https://ieeexplore.ieee.org/document/9448359)/Code                                                   |
|   2021   |   TVCG   | Content-Preserving Image Stitching With Piecewise Rectangular Boundary Constraints   <br> <sub><sup>*Yun Zhang, Yu-Kun Lai, Fang-Lue Zhang*</sup><sub>       | [Paper](https://ieeexplore.ieee.org/document/8954740)/Code                                                   |
|   2021   |    PR    | Edge-guided Composition Network for Image Stitching          <br> <sub><sup>*Qinyan Dai, Faming Fang, Juncheng Li, Guixu Zhang, Aimin Zhou*</sup><sub>            | [Paper](https://www.sciencedirect.com/science/article/abs/pii/S0031320321002065)/Code |
|   2021   |    PR    | Image stitching based on angle-consistent warping     <br> <sub><sup>*Yinqi Chen, Huicheng Zheng, Yiyan Ma, Zhiwei Yan*</sup><sub>      | [Paper](https://www.sciencedirect.com/science/article/abs/pii/S0031320321001801)/Code |
|   2021   |   SPL    | End-to-End Image Stitching Network via Multi-Homography Estimation   <br> <sub><sup>*Dae-Young Song, et al.*</sup><sub>       | [Paper](https://ieeexplore.ieee.org/abstract/document/9393563)/Code |
|   2021   |  NeuCom | Image stitching via deep homography estimation   <br> <sub><sup>*Qiang Zhao, Yike Ma, Chen Zhu, Chunfeng Yao, Bailan Feng, Feng Dai*</sup><sub>  | [Paper](https://www.sciencedirect.com/science/article/abs/pii/S0925231221004859)/Code




**2020**

| **Year** | **Pub.** | **Title**                                                    | **Links**                                                    |
| :------: | :------: | :----------------------------------------------------------- | :----------------------------------------------------------- |
|   --   | arXiv  | Vanishing Point Guided Natural Image Stitching     <br> <sub><sup>*Kai Chen, Jian Yao, et al.*</sup><sub>                  | [Paper](https://arxiv.org/abs/2004.02478)/[Proj](https://cvrs.whu.edu.cn/vpgstitching/)          |
|   2020   |   ECCV   | Image Stitching and Rectification for Hand-Held Cameras    <br> <sub><sup>*Bingbing Zhuang, Quoc-Huy Tran*</sup><sub>    | [Paper](https://www.nec-labs.com/uploads/Documents/Media-Analytics/research-papers/Image_Stitching_and_Rectification_for_Hand-Held_Cameras.pdf)/[Proj](https://www.nec-labs.com/~mas/RS-APAP/) |
|   2020   |   ECCV   | Content-Aware Unsupervised Deep Homography Estimation   `DH`    <br> <sub><sup>*Jirong Zhang, Shuaicheng Liu, et al.*</sup><sub>   | [Paper](https://arxiv.org/abs/1909.05983)/[Code](https://github.com/JirongZhang/DeepHomography?utm_source=catalyzex.com) |
|   2020   |    MM    | SRHEN: Stepwise-Refining Homography Estimation Network via Parsing Geometric Correspondences in Deep Latent Space <br> <sub><sup>*Yi Li, Wenjie Pei, Zhenyu He*</sup><sub>    | [Paper](https://dl.acm.org/doi/pdf/10.1145/3394171.3413870)/Code |
|   2020   |   CVPR   | <span style="white-space:nowrap;">Warping Residual Based Image Stitching for Large Parallax&emsp; </span> <br> <sub><sup>*Kyu-Yul Lee, Jae-Young Sim*</sup><sub>     | [Paper](https://openaccess.thecvf.com/content_CVPR_2020/papers/Lee_Warping_Residual_Based_Image_Stitching_for_Large_Parallax_CVPR_2020_paper.pdf)/Code |
|   2020   |   CVPR   | Deep Homography Estimation for Dynamic Scenes  `DH`       <br> <sub><sup>*Hoang Le, Feng Liu, et al.*</sup><sub>            | [Paper](https://openaccess.thecvf.com/content_CVPR_2020/papers/Le_Deep_Homography_Estimation_for_Dynamic_Scenes_CVPR_2020_paper.pdf)/[Code](https://github.com/lcmhoang/hmg-dynamics) |
|   2020   |   CVPR   | Robust Homography Estimation via Dual Principal Component Pursuit  <br> <sub><sup>*Tianjiao Ding, et al.*</sup><sub>    | [Paper](https://openaccess.thecvf.com/content_CVPR_2020/papers/Ding_Robust_Homography_Estimation_via_Dual_Principal_Component_Pursuit_CVPR_2020_paper.pdf)/Code                                                   |
|   2020   |   PAMI   | CrossNet++: Cross-scale Large-parallax Warping for Reference-based Super-resolution <br> <sub><sup>*Yang Tan, et al.*</sup><sub>            | Paper/Code                                                   |
|   2020   |   TIP    | Parallax Tolerant Light Field Stitching for Hand-Held Plenoptic Cameras <br> <sub><sup>*Xin Jin, Pei Wang, Qionghai Dai*</sup><sub>          | Paper/Code                                                   |
|   2020   |   TIP    | An Unordered Image Stitching Method Based on Binary Tree and Estimated Overlapping Area    <br> <sub><sup>*Zhong Qu, et al.*</sup><sub>       | Paper/Code                                                   |
|   2020   |   TIP    | Single-Perspective Warps in Natural Image Stitching       <br> <sub><sup>*Tianli Liao, Nan Li*</sup><sub>             | [Paper](https://arxiv.org/abs/1802.04645)/[Code1](https://github.com/tlliao/Single-perspective-warps)<br>[Code2](https://github.com/tlliao/Single-perspective-warps-multiple) |
|   2020   |   TMM    | Stereoscopic Image Stitching via Disparity-Constrained Warping and Blending   <br> <sub><sup>*Xiaoting Fan, et al.*</sup><sub>        | Paper/Code                                                   |
|   2020   |   TMM    | Image-Only Real-Time Incremental UAV Image Mosaic for Multi-Strip Flight  <br> <sub><sup>*Fangbing Zhang, et al.*</sup><sub>          | Paper/Code                                                   |
|   2020   |  JSTSP   | Attentive Deep Stitching and Quality Assessment for 360° Omnidirectional Images  <br> <sub><sup>*Jia Li, et al.*</sup><sub>   | [Paper](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=8903278&casa_token=-GdkCo2qmfIAAAAA:GbByoLo8XDRu7PCBD-kH-bvgT6R9Zl9_P9KtnTRz47jMbAqDPBve9UrBWTkA9sGpwa1OgLc&tag=1)/Code |   
<!-- |   --   | arXiv  | Learning Edge-Preserved Image Stitching from Large-Baseline Deep Homography   <br> <sub><sup>*Lang Nie, Chunyu Lin, Kang Liao, Shuaicheng Liu, Yao Zhao*</sup><sub>      | [Paper](https://arxiv.org/pdf/2012.06194.pdf)/Code           |  -->




**2019**

| **Year** | **Pub.** | **Title**                                                    | **Links**                                                    |
| :------: | :------: | :----------------------------------------------------------- | :----------------------------------------------------------- |
|   2019   |   ICCV   | Homography From Two Orientation- and Scale-Covariant Features   <br> <sub><sup>*Daniel Barath, Zuzana Kukelova*</sup><sub>     | [Paper](https://arxiv.org/pdf/1906.11927.pdf)/[Code](https://github.com/danini/homography-from-sift-features) |
|   2019   |   BMVC   | Video Stitching for Linear Camera Arrays <span style="color:blue;">`CNNStitch`</span>   <br> <sub><sup>*Wei-Sheng Lai, et al.*</sup><sub>     | [Paper](https://jankautz.com/publications/VideoStitching_BMVC19.pdf)/[arXiv](https://arxiv.org/abs/1907.13622)<br>[Proj](http://vllab.ucmerced.edu/wlai24/video_stitching/) |
|   2019   |   TIP    | Robust Alignment for Panoramic Stitching Via an Exact Rank Constraint   <br> <sub><sup>*Yuelong Li, Mohammad Tofighi, Vishal Monga*</sup><sub>         | [Paper](https://ieeexplore.ieee.org/document/8684316)/[Code](http://signal.ee.psu.edu/research/BRAS.html) |
|   2019   |   TMM    | A Novel Projective-Consistent Plane Based Image Stitching Method   <br> <sub><sup>*Jin Zheng, et al.*</sup><sub>    | Paper/Code                                                   |
|   2019   |   TMM    | <span style="white-space:nowrap;">Shape-Optimizing and Illumination-Smoothing Image Stitching&emsp; </span>   <br> <sub><sup>*Shiguang Liu, Qingpeng Chai*</sup><sub>              | Paper/Code                                                   |
|   2019   |   GRSM   | Remote Sensing Image Mosaicking: Achievements and Challenges   <br> <sub><sup>*Xinghua Li, Ruitao Feng, et al.*</sup><sub>    | [Paper](https://ieeexplore.ieee.org/document/8937068)/Code   | 



**2018**

| **Year** | **Pub.** | **Title**                                                    | **Links**                                                    |
| :------: | :------: | :----------------------------------------------------------- | :----------------------------------------------------------- |
|   2018   |   ECCV   | Object-centered image stitching     <br> <sub><sup>*Charles Herrmann, Ramin Zabih, et al.*</sup><sub>  |  [Paper](https://openaccess.thecvf.com/content_ECCV_2018/papers/Charles_Herrmann_Object-centered_image_stitching_ECCV_2018_paper.pdf)/Code                                                   |
|   2018   |   ECCV   | Robust image stitching with multiple registrations    <br> <sub><sup>*Herrmann, Charles, Zabih, Ramin, et al.*</sup><sub>  | [Paper](https://openaccess.thecvf.com/content_ECCV_2018/papers/Charles_Herrmann_Robust_image_stitching_ECCV_2018_paper.pdf)/Code   |
|   2018   |   TIP    | Dynamic Video Stitching via Shakiness Removing               <br> <sub><sup>*Yongwei Nie, et al.*</sup><sub>               | [Paper](https://ieeexplore.ieee.org/document/8003352)/[Code](https://github.com/SuTanTank/VideoStitchingViaShakinessRemoving) |
|   2018   |   TMM    | Parallax-Tolerant Image Stitching Based on Robust Elastic Warping  <br> <sub><sup>*Jing Li, Zhengming Wang, Shiming Lai, Yongping Zhai, Maojun Zhang*</sup><sub>   | [Paper](https://ieeexplore.ieee.org/document/8119833)/[Code](https://github.com/gain2217/Robust_Elastic_Warping) |
|   2018   |   TMM    | Quasi-Homography Warps in Image Stitching    <br> <sub><sup>*Nan Li, Yifang Xu, Chao Wang*</sup><sub>   |  [Paper](https://ieeexplore.ieee.org/document/8101022)/Code   |
|   2018   |   PR   | Image Stitching by Line-guided Local Warping with Global Similarity Constraint   <br> <sub><sup>*Tian-Zhu Xiang, Gui-Song Xia, Xiang Bai, Liangpei Zhang*</sup><sub> | [Paper](https://arxiv.org/abs/1702.07935)/Code
|   2018   |  RA-L  | Unsupervised deep homography: A fast and robust homography estimation model `DH`    <br> <sub><sup>*Ty Nguyen, et al.*</sup><sub> | [Paper](https://arxiv.org/abs/1709.03966)/[Code](https://github.com/tynguyen/unsupervisedDeepHomographyRAL2018)  |



**2017**

| **Year** | **Pub.** | **Title**                                                    | **Links**                                                    |
| :------: | :------: | :----------------------------------------------------------- | :----------------------------------------------------------- |
|   2017   |  ICCVW  | Homography Estimation from Image Pairs with Hierarchical Convolutional Networks `DH`   <br> <sub><sup>*F E Nowruzi, et al.*</sup><sub> | [Paper](https://openaccess.thecvf.com/content_ICCV_2017_workshops/w17/html/Nowruzi_Homography_Estimation_From_ICCV_2017_paper.html)/Code
|   2017   |  CVPR  | Direct Photometric Alignment by Mesh Deformation             <br> <sub><sup>*Kaimo Lin, Shuaicheng Liu, et al.*</sup><sub>   | [Paper](https://openaccess.thecvf.com/content_cvpr_2017/papers/Lin_Direct_Photometric_Alignment_CVPR_2017_paper.pdf)/[Code](https://github.com/lxlscut/optical2.0)                                                   |



**2016**

| **Year** | **Pub.** | **Title**                                                    | **Links**                                                    |
| :------: | :------: | :----------------------------------------------------------- | :----------------------------------------------------------- |
|   2016   |   RSS-W   |  Deep Image Homography Estimation `DH`   <br> <sub><sup>*Daniel DeTone, et al.*</sup><sub>  | [Paper](https://arxiv.org/abs/1606.03798)/[Code](https://github.com/mazenmel/Deep-homography-estimation-Pytorch)
|   2016   |   ECCV   | SEAGULL: Seam-Guided Local Alignment for Parallax-Tolerant Image Stitching   <br> <sub><sup>*Kaimo Lin, Nianjuan Jiang, et al.*</sup><sub>    | [Paper](https://link.springer.com/chapter/10.1007/978-3-319-46487-9_23)/[Proj](http://linkaimo.com/publications/ImageStitching/ImageStitching.html)                                                   |
|   2016   |   ECCV   | Natural Image Stitching with the Global Similarity Prior    <br> <sub><sup>*Y.-S. Chen, Yung-Yu Chuang*</sup><sub> | [Paper](https://link.springer.com/chapter/10.1007/978-3-319-46454-1_12)/[Code](https://github.com/nothinglo/NISwGSP) |
|   2016   |   TOG    | Jump: Virtual reality video        <br> <sub><sup>*Robert Anderson, et al.*</sup><sub>      | [Paper](https://dl.acm.org/doi/pdf/10.1145/2980179.2980257)/Code        |



**2015 & before**

| **Year** | **Pub.** | **Title**                                                    | **Links**                                                    |
| :------: | :------: | :----------------------------------------------------------- | :----------------------------------------------------------- |
|   2015   |   ICCV   |  Dual-Feature Warping-Based Motion Model Estimation  <br> <sub><sup>*Shiwei Li, Lu Yuan, Jian Sun, Long Quan*</sup><sub> | [Paper](https://openaccess.thecvf.com/content_iccv_2015/html/Li_Dual-Feature_Warping-Based_Motion_ICCV_2015_paper.html)/Code
|   2015   |   CVPR   | Adaptive As-Natural-As-Possible Image Stitching  <br> <sub><sup>*Chung-Ching Lin, S. U. Pankanti, K. N. Ramamurthy, and Aleksandr Y. Aravkin*</sup><sub> | [Paper](https://openaccess.thecvf.com/content_cvpr_2015/papers/Lin_Adaptive_As-Natural-As-Possible_Image_2015_CVPR_paper.pdf)/[Code](https://github.com/YaqiLYU/AANAP)
|   2014   |   CVPR   |  Shape-preserving half-projective warps for image stitching <br> <sub><sup>*Che-Han Chang, Yoichi Sato, Yung-Yu Chuang*</sup><sub> | [Paper](https://www.cv-foundation.org/openaccess/content_cvpr_2014/html/Chang_Shape-Preserving_Half-Projective_Warps_2014_CVPR_paper.html)/Code
|   2014   |   CVPR  |  Parallax-tolerant Image Stitching  <br> <sub><sup>*Fan Zhang and Feng Liu*</sup><sub>  | [Paper](https://openaccess.thecvf.com/content_cvpr_2014/papers/Zhang_Parallax-tolerant_Image_Stitching_2014_CVPR_paper.pdf)
|   2013   |   CVPR   |  As-Projective-As-Possible Image Stitching with Moving DLT  <br> <sub><sup>*Julio Zaragoza, Tat-Jun Chin, Michael S. Brown, David Suter*</sup><sub>  | [Paper](https://www.cv-foundation.org/openaccess/content_cvpr_2013/papers/Zaragoza_As-Projective-As-Possible_Image_Stitching_2013_CVPR_paper.pdf)/[Code](https://cs.adelaide.edu.au/~tjchin/apap/)<br>[Ext](https://ieeexplore.ieee.org/document/6682890) |
|   2013   |  EG | Seam-Driven Image Stitching   <br> <sub><sup>*Junhong Gao, Yu Li, Tat-Jun Chin, Michael S. Brown*</sup><sub>  |  [Paper](https://yu-li.github.io/paper/eg13_stitching.pdf)/Code
|   2012   |   TOG    | Panorama weaving: fast and flexible seam processing      <br> <sub><sup>*Brian Summa, et al.*</sup><sub>           | [Paper](http://www.sci.utah.edu/~bsumma/projects/weaving/index.html)/[Proj](http://www.sci.utah.edu/~bsumma/projects/weaving/index.html) |
|   2011   | CVPR  | Smoothly varying affine stitching   <br> <sub><sup>*Wen-Yan Lin, Siying Liu, Y Matsushita, Tian-Tsong Ng, Loong-Fah Cheong*</sup><sub>  | [Paper](https://ieeexplore.ieee.org/document/5995314)/[Code](https://sites.google.com/site/laoszefei81/home/code-1/code-for-smoothly-varying-affine-stitching)
|   2011   | CVPR | Constructing image panoramas using dual-homography warping <br> <sub><sup>*Junhong Gao, Seon Joo Kim, Michael S. Brown*</sup><sub>   | [Paper](https://ieeexplore.ieee.org/document/5995433)/Code
|   2007  |  IJCV | Automatic panoramic image stitching using invariant features <br> <sub><sup>*Matthew Brown and David G. Lowe*</sup><sub>  | [Paper](http://matthewalunbrown.com/papers/ijcv2007.pdf)/[Demo](http://matthewalunbrown.com/autostitch/autostitch.html)
|   2006  | FTCGV |  Image alignment and stitching: a tutorial <br> <sub><sup>*Richard Szeliski*</sup><sub> | [Paper](https://ieeexplore.ieee.org/document/8187154?arnumber=8187154)




#### Stitching Evaluation

| **Year** | **Pub.** | **Title**                                                    | **Links**                                                    |
| :------: | :------: | :----------------------------------------------------------- | :----------------------------------------------------------- |
|   2019   |    MM    | Cross-Reference Stitching Quality Assessment for 360° Omnidirectional Images    <br> <sub><sup>*Jia Li, et al.*</sup><sub>    | [Paper](http://cvteam.net/papers/2019-ACMMM-Cross-Reference%20Stitching%20Quality%20Assessment%20for%20360%C2%B0%20Omnidirectional%20Images.pdf)/[Proj](http://cvteam.net/projects/MM19-CROSS/MM2019.html) |
|   2020   |   TIP    | A Metric for Video Blending Quality Assessment        <br> <sub><sup>*Zhe Zhu, et al.*</sup><sub>                     | Paper/Code                                                   |
|   2019   |   TIP    | <span style="white-space:nowrap;">Subjective and Objective Quality Assessment of Stitched Images for Virtual Reality&emsp; </span>    <br> <sub><sup>*Pavan C. Madhusudana, Rajiv Soundararajan*</sup><sub>   | [Paper](https://ieeexplore.ieee.org/document/8736985)/Code    |




#### Stitching Beyond

| **Year** | **Pub.** | **Title**                                                    | **Links**                                                  |
| :------: | :------: | :----------------------------------------------------------- | :--------------------------------------------------------- |
|   2018   |   ECCV   | <span style="white-space:nowrap;">GridFace: Face Rectification via Learning Local Homography Transformations &emsp; </span> <br> <sub><sup>*Erjin Zhou, Zhimin Cao, Jian Sun*</sup><sub>     | [Paper](https://openaccess.thecvf.com/content_ECCV_2018/papers/Zhou_GridFace_Face_Rectification_ECCV_2018_paper.pdf)/Code |
|   2020   |   PAMI   | Ambiguity-Free Radiometric Calibration for Internet Photo Collections    <br> <sub><sup>*Zhipeng Mo, Yasuyuki Matsushit, et al.*</sup><sub>      | [Paper](https://ieeexplore.ieee.org/document/8651349)/Code |
|   2019   |   TOG    | Video Extrapolation Using Neighboring Frames                 <br> <sub><sup>*Sangwoo Lee, et al.*</sup><sub>           | [Paper](https://dl.acm.org/doi/10.1145/3196492)/Code       |
|   2019   |   TIP    | <span style="white-space:nowrap;">Panoramic Background Image Generation for PTZ Cameras&emsp; </span>   <br> <sub><sup>*Hongwei Yong, et al.*</sup><sub>   | [Paper](https://ieeexplore.ieee.org/document/8625516)/Code                 | 








## Image Matching

Part curated paper list for deep learning-based image matching.

#### Overview

| **Year** | **Pub.** | **Title**                                                    | **Author**                                                   | **Links**                                                    |
| :------: | :------: | :----------------------------------------------------------- | :----------------------------------------------------------- | :----------------------------------------------------------- |
|   2021   |   IJCV   | Image Matching from Handcrafted to Deep Features: A Survey   | Jiayi Ma, Xingyu Jiang, et al.                               | Paper/Code                                                   |
|   2021   |  INFFUS  | A review of multimodal image matching: methods and applications | Xingyu Jiang, Jiayi Ma, et al.                               | Paper/[Data](https://github.com/StaRainJ/Multi-modality-image-matching-database-metrics-methods) |
|   2021   |   ICCV   | <span style="white-space:nowrap;">Matching in the Dark: A Dataset for Matching Image Pairs of Low-light Scenes&emsp; </span> | <span style="white-space:nowrap;">W. Song, Takayuki Okatani, et al.&emsp; </span> | [Paper](https://arxiv.org/abs/2109.03585)/Code               |


#### 2022  

| **Pub.** | **Title**                                                    | **Author**                                                   | **Links**                                                    |
| :------: | :----------------------------------------------------------- | :----------------------------------------------------------- | :----------------------------------------------------------- |
|   ECCV   | <span style="white-space:nowrap;">ECO-TR: Efficient Correspondences Finding Via Coarse-to-Fine <br>Refinement &emsp; </span> | <span style="white-space:nowrap;">Dongli Tan, Rongrong Ji, et al. </span> | Paper/Code                                                   | 
|   AAAI   |  Guide Local Feature Matching by Overlap Estimation  | Ying Chen, Dihe Huang, et al. | [Paper](https://aaai-2022.virtualchair.net/poster_aaai7556)/[Code](https://github.com/AbyssGaze/OETR)




#### 2021 

| **Pub.** | **Title**                                                    | **Author**                                                   | **Links**                                                    |
| :------: | :----------------------------------------------------------- | :----------------------------------------------------------- | :----------------------------------------------------------- |
|   PAMI   | <span style="white-space:nowrap;">Joint detection and matching of feature points in multimodal images&emsp; </span> | <span style="white-space:nowrap;">Elad Ben Baruch, Yosi Keller&emsp; </span> | Paper/Code                                                   |
|   TIP    | Multi-Relation Attention Network for Image Patch Matching    | Dou Quan, et al.                                             | Paper/Code                                                   |
|   ICCV   | COTR: Correspondence Transformer for Matching Across Images  | Wei Jiang, Eduard Trulls, et al.                             | [Paper](https://arxiv.org/abs/2103.14167)/[Code](https://github.com/ubc-vision/COTR) |
|   ICCV   | Warp Consistency for Unsupervised Learning of Dense Correspondences | Prune Truong, Luc Van Gool, et al.                           | [Paper](https://arxiv.org/abs/2104.03308)/[Code](https://github.com/PruneTruong/DenseMatching) |
|   CVPR   | LoFTR: Detector-Free Local Feature Matching with Transformers | Jiaming Sun, Xiaowei Zhou, et al. | [Paper](https://arxiv.org/abs/2104.00680)/[Code](https://github.com/zju3dv/LoFTR)<br>[Proj](https://zju3dv.github.io/loftr/) |
|   CVPR   | SOLD2: Self-supervised Occlusion-aware Line Description and Detection | Rémi Pautrat, Marc Pollefeys, et al. | [Paper](https://arxiv.org/abs/2104.03362)/[Code](https://github.com/cvg/SOLD2)
|   CVPR   | Convolutional Hough Matching Networks                        |                                                              | [Paper](https://arxiv.org/abs/2103.16831)/[Proj](http://cvlab.postech.ac.kr/research/CHM/) |
|   CVPR   | Learning to Match Features with Seeded Graph Matching Network |                                                              | [Paper](https://arxiv.org/abs/2108.08771)/[Code](https://github.com/vdvchen/SGMNet) |
|   CVPR   | Co-Attention for Conditioned Image Matching                  | Olivia Wiles, S. Ehrhardt, Andrew Zisserman | [Paper](https://openaccess.thecvf.com/content/CVPR2021/html/Wiles_Co-Attention_for_Conditioned_Image_Matching_CVPR_2021_paper.html)/[Proj](https://www.robots.ox.ac.uk/~ow/coam.html)  |                                                 |
|   CVPR   | Learning Optical Flow From a Few Matches                     | Shihao Jiang, Yao Lu, Hongdong Li, Richard Hartley | [Paper](https://openaccess.thecvf.com/content/CVPR2021/papers/Jiang_Learning_Optical_Flow_From_a_Few_Matches_CVPR_2021_paper.pdf)/[Code](https://github.com/zacjiang/scv) |                                                   |
|   CVPR   | SuperGlue: Learning Feature Matching With Graph Neural Networks | P. Sarlin, D. DeTone, T. Malisiewicz, Andrew Rabinovich | [Paper](https://openaccess.thecvf.com/content_CVPR_2020/html/Sarlin_SuperGlue_Learning_Feature_Matching_With_Graph_Neural_Networks_CVPR_2020_paper.html)/[Code](https://github.com/magicleap/SuperGluePretrainedNetwork)<br>[arXiv](https://arxiv.org/abs/1911.11763) |
|   CVPR   | Patch2Pix: Epipolar-Guided Pixel-Level Correspondences | Qunjie Zhou, Torsten Sattler, Laura Leal-Taixe | [Paper](https://arxiv.org/abs/2012.01909)/[Code](https://github.com/GrumpyZhou/patch2pix)


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
|   2021   | arXiv07  | Precise Aerial Image Matching based on Deep Homography Estimation |                                                              | [Paper](https://arxiv.org/pdf/2107.08768.pdf)/Code           |
|   2021   |  arXiv05 | Attention for Image Registration (AiR): an unsupervised Transformer approach | Zihao Wang, Hervé Delingette | [Paper](https://arxiv.org/abs/2105.02282)/Code
|   2021   |   CVPR   | Learning-based Image Registration with Meta-Regularization   | Ebrahim Al Safadi, Xubo Song                                 | [Paper](https://openaccess.thecvf.com/content/CVPR2021/papers/Safadi_Learning-Based_Image_Registration_With_Meta-Regularization_CVPR_2021_paper.pdf)/[Code]() |
|   2020   |   TIP    | Cross-Weather Image Alignment via Latent Generative Model with Intensity Consistency | Huabing Zhou, Jiayi Ma, et al.                               | Paper/Code                                                   |
|   2020   |   TIP    | Boosting Structure Consistency for Multispectral and Multimodal Image Registration | Si-Yuan Cao, Hui-Liang Shen, Shu-Jie Chen, Chunguang Li      | Paper/Code                                                   |
|   2020   |   TIP    | Local-Adaptive Image Alignment Based on Triangular Facet Approximation | Jing Li, et al.                                              | Paper/Code                                                   |
|   2020   |   ECCV   | RANSAC-Flow: Generic Two-stage Image Alignment               |                                                              | Paper/Code                                                   |
|   2020   |   ECCV   | Aligning Videos in Space and Time                            |                                                              | Paper/Code                                                   |
|   2020   |   CVPR   | Unsupervised Multi-Modal Image Registration via Geometry Preserving Image-to-Image Translation | Moab Arar, Yiftach Ginger, et al.                            | [Paper](https://openaccess.thecvf.com/content_CVPR_2020/papers/Arar_Unsupervised_Multi-Modal_Image_Registration_via_Geometry_Preserving_Image-to-Image_Translation_CVPR_2020_paper.pdf)/Code |
|   2019   |   TIP    | Online Subspace Learning from Gradient Orientations for Robust Image Alignment | Qingqing Zheng, Yi Wang, Pheng Ann Heng                      | Paper/Code                                                   |
|   2019   |   ICCV   | Jointly Aligning Millions of Images With Deep Penalised Reconstruction Congealing | Roberto Annunziata, Christos Sagonas, Jacques Cali           | [Paper](https://openaccess.thecvf.com/content_ICCV_2019/papers/Annunziata_Jointly_Aligning_Millions_of_Images_With_Deep_Penalised_Reconstruction_Congealing_ICCV_2019_paper.pdf)/Code |
|   2018   |   PAMI   | Hierarchical Sparse Representation for Robust Image Registration | Yeqing Li, et al.                                            | Paper/Code                                                   |
|   2018   |  ISPRSJ  | A deep learning framework for remote sensing image registration | Shuang Wang, Licheng Jiao, et al.                            | [Paper](https://www.sciencedirect.com/science/article/abs/pii/S0924271617303891)/Code |
|   2018   |   ECCV   | Multimodal image alignment through a multiscale chain of neural networks with application to remote sensing |                                                              | Paper/Code                                                   |
|   2017   |   CVPR   | <span style="white-space:nowrap;">CLKN: Cascaded Lucas-Kanade Networks for Image Alignment&emsp; </span> | <span style="white-space:nowrap;">Che-Han Chang, Chun-Nan Chou, Edward Y. Chang&emsp; </span> | [Paper](https://openaccess.thecvf.com/content_cvpr_2017/papers/Chang_CLKN_Cascaded_Lucas-Kanade_CVPR_2017_paper.pdf)/Code |





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





## Color Harmonization

| **Year** | **Pub.** | **Title**                            | **Author**                         | **Links**  |
| :------: | :------: | :----------------------------------- | :--------------------------------- | :--------- |
|   2021   |   ICCV   | Image Harmonization With Transformer | Zonghui Guo, Dongsheng Guo, et al. | Paper/Code |


## Low-Light Enhancement

| **Year** | **Pub.** | **Title**                            | **Author**                         | **Links**  |
| :------: | :------: | :----------------------------------- | :--------------------------------- | :--------- |
2021 | arXiv04 | Low-Light Image and Video Enhancement Using Deep Learning: A Survey | Chongyi Li, Chen Change Loy, et al. | [Paper](https://arxiv.org/abs/2104.10729)/[Proj](https://github.com/Li-Chongyi/Lighting-the-Darkness-in-the-Deep-Learning-Era-Open) 


## Stabilization

| **Year** | **Pub.** | **Title**                                                    | **Author**                                                   | **Links**                                                    |
| :------: | :------: | :----------------------------------------------------------- | :----------------------------------------------------------- | :----------------------------------------------------------- |
|   2021   |   ICCV   | Out-of-boundary View Synthesis Towards Full-Frame Video Stabilization | Yufei Xu, Jing Zhang, Dacheng Tao | [Paper](https://arxiv.org/abs/2108.09041)/[Code](https://github.com/Annbless/OVS_Stabilization) |
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



## Beyond  

| **Year** | **Pub.** | **Title**                                                    | **Author**                                                   | **Links**                                                    |
| :------: | :------: | :----------------------------------------------------------- | :----------------------------------------------------------- | :----------------------------------------------------------- |
2021 | arXiv10 | InfinityGAN: Towards Infinite-Pixel Image Synthesis | C. Lin, Ming-Hsuan Yang, et al. | [Paper](https://arxiv.org/abs/2104.03963)/[Code](https://hubert0527.github.io/infinityGAN/)  
2021 | PAMI | CrossNet++: Cross-Scale Large-Parallax Warping for Reference-Based Super-Resolution | Yang Tan, et al. | [Paper](https://ieeexplore.ieee.org/document/9099445?source=tocalert&dld=Z21haWwuY29t)/Code


## Appendix

- [Awesome Image Alignment and Stitching](https://github.com/tzxiang/awesome-image-alignment-and-stitching)



