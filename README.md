# Face-Recogniton
人脸识别相关

## Table of Contents
* [总综述](https://github.com/Qingcsai/Face-Recogniton#%E6%80%BB%E7%BB%BC%E8%BF%B0)
* [人脸检测](https://github.com/Qingcsai/Face-Recogniton#%E4%BA%BA%E8%84%B8%E6%A3%80%E6%B5%8B)
  * Survey
  * Papers
  * Talks
* [大规模训练](https://github.com/Qingcsai/Face-Recogniton#%E5%A4%A7%E8%A7%84%E6%A8%A1%E8%AE%AD%E7%BB%83)
  * Survey
  * Papers
  * Talks
* [不确定性](https://github.com/Qingcsai/Face-Recogniton#%E4%B8%8D%E7%A1%AE%E5%AE%9A%E6%80%A7)
  * Survey
  * Papers
    * Model uncertainty 
    * Data uncertainty 
  * Talks
* [噪声](https://github.com/Qingcsai/Face-Recogniton#%E5%99%AA%E5%A3%B0)
  * Survey
  * Papers
  * Talks

## 总综述
* 2020 | [The Elements of End-to-end Deep Face Recognition: A Survey of Recent Advances](https://arxiv.org/abs/2009.13290) | Hang Du, Tao Mei | 
* 2021 | [FaceX-Zoo: A PyTorch Toolbox for Face Recognition](https://arxiv.org/abs/2101.04407) | Jun Wang, Tao Mei | [github](https://github.com/JDAI-CV/FaceX-Zoo)

## 人脸检测
### Survey
### Papers
* 2019 | [PFLD: A Practical Facial Landmark Detector](https://arxiv.org/abs/1902.10859) | Xiaojie Guo, Haibin Ling | 
### Talks

## 大规模训练
### Survey
### Papers
* 2020 | [Partial FC: Training 10 Million Identities on a Single Machine](https://arxiv.org/abs/2010.05222) | Xiang An, Ying Fu | [github](https://github.com/deepinsight/insightface/tree/master/recognition/partial_fc)
### Talks

## 不确定性
### Survey
* 2016 | [Uncertainty in Deep Learning](http://mlg.eng.cam.ac.uk/yarin/blog_2248.html) | YARIN GAL
* 2017 NIPS | [What Uncertainties Do We Need in Bayesian Deep Learning for Computer Vision?](https://arxiv.org/abs/1703.04977) | Alex Kendall, Yarin Gal | 
* 2020 arXiv | [Face Image Quality Assessment: A Literature Survey](https://arxiv.org/abs/2009.01103) | Torsten Schlett, Christoph Busch
### Papers
#### Model uncertainty 
* 2019 EURASIP
Journal on Image and Video Processing | [Face recognition with Bayesian convolutional networks for robust surveillance systems](https://link.springer.com/article/10.1186/s13640-019-0406-y) | Umara Zafar, et al. | 
* 2019 CVPR | [Striking the Right Balance With Uncertainty](https://openaccess.thecvf.com/content_CVPR_2019/html/Khan_Striking_the_Right_Balance_With_Uncertainty_CVPR_2019_paper.html) | Salman Khan, Ling Shao
* 2019 | [On the Capacity of Face Representation](https://arxiv.org/abs/1709.10433) | Sixue Gong, Anil K. Jain | \
#### Data uncertainty 
* 2019 ICCV | [Probabilistic Face Embeddings](https://openaccess.thecvf.com/content_ICCV_2019/html/Shi_Probabilistic_Face_Embeddings_ICCV_2019_paper.html) | Yichun Shi, Anil K. Jain | [github](https://github.com/seasonSH/Probabilistic-Face-Embeddings)
* 2020 CVPR | [Data Uncertainty Learning in Face Recognition](https://openaccess.thecvf.com/content_CVPR_2020/html/Chang_Data_Uncertainty_Learning_in_Face_Recognition_CVPR_2020_paper.html) | Jie Chang, Zhonghao Lan, Yichen Wei | [github(not official)](https://github.com/Ontheway361/dul-pytorch)
* 2021 arXiv | [Reliable Probabilistic Face Embeddings in the Wild](https://arxiv.org/abs/2102.04075) | Kai Chen, Zhengming Yi | [github](https://github.com/KaenChan/ProbFace)

### Others
#### Semantic segmentation  
* 2017 IEEE INISTA | [Deep convolutional encoder-decoder network with model uncertainty for semantic segmentation](https://ieeexplore.ieee.org/abstract/document/8001187) 
* 2015 BMVC | [Bayesian segnet: Model uncertainty in deep convolutional encoder-decoder architectures for scene understanding](https://arxiv.org/abs/1511.02680) | Alex Kendall, Roberto Cipolla

#### Object detection
* 2019 ICCV | [Gaussian YOLOv3: An Accurate and Fast Object Detector Using Localization Uncertainty for Autonomous Driving](https://openaccess.thecvf.com/content_ICCV_2019/html/Choi_Gaussian_YOLOv3_An_Accurate_and_Fast_Object_Detector_Using_Localization_ICCV_2019_paper.html) | 
* 2019 IEEE ITSC | [Uncertainty Estimation in One-Stage Object Detection](https://ieeexplore.ieee.org/abstract/document/8917494/) | 
#### Person Re-ID
* 2019 ICCV | [Robust Person Re-Identification by Modelling Feature Uncertainty](https://openaccess.thecvf.com/content_ICCV_2019/html/Yu_Robust_Person_Re-Identification_by_Modelling_Feature_Uncertainty_ICCV_2019_paper.html) | Tianyuan Yu, Tao Xiang
* 2020 arXiv | [Exploiting Sample Uncertainty for Domain Adaptive Person Re-Identification](https://arxiv.org/abs/2012.08733) | Kecheng Zheng, Zheng-Jun Zha


## 噪声
### Survey
* 2020 | [Learning from Noisy Labels with Deep Neural Networks: A Survey](https://arxiv.org/abs/2007.08199) | Hwanjun Song, Jae-Gil Lee | 
### Papers
* 2018 IEEE Transactions on Information Forensics and Security | [A Light CNN for Deep Face Representation With Noisy Labels](https://ieeexplore.ieee.org/abstract/document/8353856) | Xiang Wu, Tieniu Tan
* 2018 ECCV | [The Devil of Face Recognition is in the Noise](https://openaccess.thecvf.com/content_ECCV_2018/html/Liren_Chen_The_Devil_of_ECCV_2018_paper.html) | Fei Wang, Chen Change Loy  |
* 2019 ICCV | [Co-Mining: Deep Face Recognition With Noisy Labels](https://openaccess.thecvf.com/content_ICCV_2019/html/Wang_Co-Mining_Deep_Face_Recognition_With_Noisy_Labels_ICCV_2019_paper.html) |Xiaobo Wang, Tao Mei |
* 2019 CVPR | [Noise-Tolerant Paradigm for Training Face Recognition CNNs](https://openaccess.thecvf.com/content_CVPR_2019/html/Hu_Noise-Tolerant_Paradigm_for_Training_Face_Recognition_CNNs_CVPR_2019_paper.html) | Wei Hu, Ruirui Li | 
* 2020 CVPR | [Global-Local GCN: Large-Scale Label Noise Cleansing for Face Recognition
](https://openaccess.thecvf.com/content_CVPR_2020/html/Zhang_Global-Local_GCN_Large-Scale_Label_Noise_Cleansing_for_Face_Recognition_CVPR_2020_paper.html) | Yaobin Zhang, Dongchao Wen |
* 2020 ECCV | [Semi-Siamese Training for Shallow Face Learning](https://link.springer.com/chapter/10.1007/978-3-030-58548-8_3) | Hang Du, Tao Mei | [github](https://github.com/dituu/Semi-Siamese-Training)

* Out of distribution
  * 2018 | [A Baseline for Detecting Misclassified and Out-of-Distribution Examples in Neural Networks](https://arxiv.org/abs/1610.02136) | Dan Hendrycks, Kevin Gimpel |
### Talks

