# AI_ComplexEnv
Object Detection and Recognition in Complex Environmental Conditions

## Enhancement + Vison Model
### Vison model directly training on degraded image
- [ECCV2018] [Does haze removal help cnn-based image classification?](https://arxiv.org/abs/1810.05716)
- [CVPR2018] [Attentive generative adversarial network for raindrop removal from a single image](https://arxiv.org/abs/1711.10098)
- [TIP2018] [Benchmarking single-image dehazing and beyond](https://arxiv.org/abs/1712.04143)
- [CVIU2019] [Getting to Know Low-light Images with The Exclusively Dark Dataset](https://arxiv.org/abs/1805.11227) [[Code](https://github.com/cs-chan/Exclusively-Dark-Image-Dataset)]
- [ICLR2019] [Benchmarking Neural Network Robustness to Common Corruptions and Perturbations](https://arxiv.org/abs/1903.12261) [[Code](https://github.com/hendrycks/robustness)] [[Superseded](https://arxiv.org/abs/1807.01697)]

### Vison model training on enhanced degraded image
- [CVPR2016] [Studying Very Low Resolution Recognition Using Deep Networks](https://arxiv.org/abs/1601.04153)
- [WACV2016] [Is image super-resolution helpful for other vision tasks?](https://arxiv.org/abs/1509.07009)
- [ICCV2017] [Enhancenet: Single image super-resolution through automated texture synthesis](https://arxiv.org/abs/1612.07919)
- [ICIP2019] [Quality-adaptive deep learning for pedestrian detection](https://engineering.purdue.edu/~dgueraco/content/pedestrian-two-stages.pdf)
- [CVPR2018] [DeblurGAN: Blind Motion Deblurring Using Conditional Adversarial Networks](https://arxiv.org/abs/1711.07064) [[Code](https://github.com/KupynOrest/DeblurGAN)]
- [WACV2018] [UG^2: A video benchmark for assessing the impact of image restoration and enhancement on automatic visual recognition](https://arxiv.org/abs/1710.02909) [[Code](https://goo.gl/AjA6En)]
- [ECCV2018] [The unreasonable effectiveness of texture transfer for single image super-resolution](https://link.springer.com/chapter/10.1007/978-3-030-11021-5_6)
- [2018] [Task-Driven Super Resolution: Object Detection in Low-resolution Images](https://arxiv.org/abs/1803.11316)
- [CVPR2019] [Single image deraining: A comprehensive benchmark analysis](https://arxiv.org/abs/1903.08558) [[Code](https://github.com/lsy17096535/Single-Image-Deraining)]



### One model (enhancement + Vision)
- [DICTA2017] [Enhancing the performance of convolutional neural networks on quality degraded datasets](https://arxiv.org/abs/1710.06805)
- [ICCV2017] [AOD-Net: All-in-One Dehazing Network](https://ieeexplore.ieee.org/abstract/document/8237773)
- [CVPR2018] [Classification-driven dynamic image enhancement](https://arxiv.org/abs/1710.07558)
- [IJCAI2018] [When image denoising meets high-level vision tasks: a deep learning approach](https://arxiv.org/abs/1706.04284) [[Code](https://github.com/Ding-Liu/DeepDenoising)]
- [ICCV2019] [Dual Directed Capsule Network for Very Low Resolution Image Recognition](https://arxiv.org/abs/1908.10027)
- [MODA2019] [Image Quality and Super Resolution Effects on Object Recognition Using Deep Neural Networks](https://www.researchgate.net/profile/Christoph-Borel/publication/333068978_Image_quality_and_super_resolution_effects_on_object_recognition_using_deep_neural_networks/links/5f10707445851512999e9ba2/Image-quality-and-super-resolution-effects-on-object-recognition-using-deep-neural-networks.pdf)
- [CVPRW2019] [The effects of super-resolution on object detection performance in satellite imagery](https://arxiv.org/abs/1812.04098)
- [ECCV2020] [URIE: Universal Image Enhancement for Visual Recognition in the Wild](https://arxiv.org/abs/2007.08979) [[Code](https://github.com/taeyoungson/urie)]
- [2021] [Dirty Pixels: Towards End-to-End Image Processing and Perception](https://arxiv.org/abs/1701.06487)
- [TPAMI2020] [Bridging the Gap Between Computational Photography and Visual Recognition](https://arxiv.org/abs/1901.09482) [[UG2 Challenge](http://cvpr2021.ug2challenge.org/)]

---

- [CVPR2015] [Super-Resolution Person Re-Identification With Semi-Coupled Low-Rank Discriminant Dictionary Learning](https://openaccess.thecvf.com/content_cvpr_2015/html/Jing_Super-Resolution_Person_Re-Identification_2015_CVPR_paper.html)
- [SIU2016] [Facial image super resolution using sparse representation for improving face recognition in surveillance monitoring](https://ieeexplore.ieee.org/abstract/document/7495771)
- [AMDO2016] [Convolutional Neural Network Super Resolution for Face Recognition in Surveillance Monitoring](https://link.springer.com/chapter/10.1007/978-3-319-41778-3_18)



## Image Enhancement
### Image/Video Quality Assessment
- Quality Assessment 领域著名实验室 LIVE(Texas University) [[Website](https://live.ece.utexas.edu/research.php)]
- [AMM2014] [No-Reference Video Quality Assessment Model for Distortion Caused by Packet Loss in the Real-Time Mobile Video Services](https://www.hindawi.com/journals/am/2014/606493/)
- [QoMEX2014] [A perceptually motivated no-reference video quality assessment algorithm for packet loss artifacts](https://ieeexplore.ieee.org/document/6982296)
- [2017CSPA] [Video quality assessment: A review of full-referenced, reduced-referenced and no-referenced methods](https://ieeexplore.ieee.org/document/8064957) 
- [MM2019] [Quality Assessment of In-the-Wild Videos](https://arxiv.org/abs/1908.00375) [[Code](https://github.com/lidq92/VSFA)]
  - 无参考视频质量评价神经网络算法
- VMAF(Netflix) [[Github](https://github.com/Netflix/vmaf)] [[Wiki](https://en.wikipedia.org/wiki/Video_Multimethod_Assessment_Fusion)]


### Restoration 图像修复
- [ECCV2020] [Learning Disentangled Feature Representation for Hybrid-distorted Image Restoration](https://arxiv.org/pdf/2007.11430.pdf)
- [CVPR2020] [Learning Invariant Representation for Unsupervised Image Restoration](https://arxiv.org/abs/2003.12769)


### Quality Enhancement 质量增强
- [CVPR2018] [Multi Frame Quality Enhancement for Compressed Video](https://link.zhihu.com/?target=http%3A//arxiv.org/abs/1803.04680) [[Code](github.com/ryangBUAA/MFQE.git)]


### Reconstruction 重建
- [CVPR2020] [EventSR: From Asynchronous Events to Image Reconstruction, Restoration, and Super-Resolution via End-to-End Adversarial Learning](https://arxiv.org/abs/2003.07640)



### Blog
- [图像质量评价和视频质量评价(IQA/VQA)](https://www.cnblogs.com/buyizhiyou/p/12090605.html)
- 视频/图像质量评价综述 [[1](https://zhuanlan.zhihu.com/p/54539091)] [[2](https://zhuanlan.zhihu.com/p/54950132)] [[3](https://zhuanlan.zhihu.com/p/55101558)] [[4](https://zhuanlan.zhihu.com/p/55111820)] [[5](https://zhuanlan.zhihu.com/p/55189941)]
- [CVPR2021视频质量增强竞赛：数据库、方法及结果汇总](https://zhuanlan.zhihu.com/p/368256419)
- 视频质量评估综述 [[1](https://testerhome.com/topics/19932)] [[2](https://testerhome.com/topics/20107)]