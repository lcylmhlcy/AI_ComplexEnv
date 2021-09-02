# AI_ComplexEnv
Object Detection and Recognition in Complex Environmental Conditions

## Enhancement + Vison Model
### Important
- [WACV2018] UG^2: A video benchmark for assessing the impact of image restoration and enhancement on automatic visual recognition [[paper](https://arxiv.org/abs/1710.02909)] [[Dataset](http://cvpr2021.ug2challenge.org/program18/dataset18.html)]
- [TPAMI2020] Bridging the Gap Between Computational Photography and Visual Recognition [[paper](https://arxiv.org/abs/1901.09482)]
  - UG2 Challenge CVPR2021 [[website](http://cvpr2021.ug2challenge.org/)]
    - TRACK 1: OBJECT DETECTION IN POOR VISIBILITY ENVIRONMENTS [[Website](http://cvpr2021.ug2challenge.org/dataset21_t1.html)]
      - SUB-CHALLENGE 1.1: OBJECT DETECTION IN THE HAZY CONDITION
      - SUB-CHALLENGE 1.2: FACE DETECTION IN THE LOW-LIGHT CONDITION



### Vison model directly training on degraded image
- [ICCV2011] Blurred target tracking by Blur-driven Tracker [[paper](https://ieeexplore.ieee.org/abstract/document/6126357)]
- [CVPR2016] Studying Very Low Resolution Recognition Using Deep Networks [[paper](https://arxiv.org/abs/1601.04153)]
- [ICIP2016] Fine-to-coarse Knowledge Transfer For Low-Res Image Classification [[paper](https://arxiv.org/abs/1605.06695)]
- [PNAS2016] Atoms of recognition in human and computer vision [[paper](http://klab.tch.harvard.edu/academia/classes/Neuro230/FinalExam/gk7410.pdf)]
- [ICCCN2017] A Study and Comparison of Human and Deep Learning Recognition Performance Under Visual Distortions [[paper](https://arxiv.org/abs/1705.02498)]
- [2017] Examining the Impact of Blur on Recognition by Convolutional Networks [[paper](https://arxiv.org/abs/1611.05760)]
- [ECCV2018] Does haze removal help cnn-based image classification? [[paper](https://arxiv.org/abs/1810.05716)]
- [CVPR2018] Attentive generative adversarial network for raindrop removal from a single image [[paper](https://arxiv.org/abs/1711.10098)]
- [CVPR2018] Domain Adaptive Faster R-CNN for Object Detection in the Wild [[paper](https://arxiv.org/abs/1803.03243)]
- [ECCV2018] Model Adaptation with Synthetic and Real Data for Semantic Dense Foggy Scene Understanding [[paper](https://arxiv.org/abs/1803.03243)]
- [TIP2019] Benchmarking single-image dehazing and beyond [[paper](https://arxiv.org/abs/1712.04143)]
  - dataset (Standard and Extended)  [[google](https://sites.google.com/site/boyilics/website-builder/reside)]
  - Belong to TRACK 1: SUB-CHALLENGE 1.1: OBJECT DETECTION IN THE HAZY CONDITION
- [CVIU2019] Getting to Know Low-light Images with The Exclusively Dark Dataset [[paper](https://arxiv.org/abs/1805.11227)] [[Code](https://github.com/cs-chan/Exclusively-Dark-Image-Dataset)]
- [ICLR2019] Benchmarking Neural Network Robustness to Common Corruptions and Perturbations [[paper](https://arxiv.org/abs/1903.12261)] [[Code](https://github.com/hendrycks/robustness)] [[Superseded](https://arxiv.org/abs/1807.01697)]
- [ICCV2019] Dual Directed Capsule Network for Very Low Resolution Image Recognition [[paper](https://arxiv.org/abs/1908.10027)]
- [ICCV2019] Guided Curriculum Model Adaptation and Uncertainty-Aware Evaluation for Semantic Nighttime Image Segmentation [[paper](https://arxiv.org/abs/1901.05946)]



### Vison model training on enhanced degraded image
- [CVPR2010] Deconvolutional networks  [[paper](https://ieeexplore.ieee.org/abstract/document/5539957)]
- [ICCV2011] Adaptive deconvolutional networks for mid and high level feature learning [[paper](https://ieeexplore.ieee.org/abstract/document/6126474)]
- [VCIP2011] Systematic evaluation of super-resolution using classification [[paper](https://ieeexplore.ieee.org/abstract/document/6115959)]
- [WACV2016] Is image super-resolution helpful for other vision tasks? [[paper](https://arxiv.org/abs/1509.07009)]
- [QoMEX2016] Understanding how image quality affects deep neural networks [[paper](https://arxiv.org/abs/1604.04004)]
- [2016] An empirical study on the effects of different types of noise in image classification tasks [[paper](https://arxiv.org/abs/1609.02781)]
- [ICMLA2017] Google's Cloud Vision API Is Not Robust To Noise [[paper](https://arxiv.org/abs/1704.05051)]
- [ICCV2017] Enhancenet: Single image super-resolution through automated texture synthesis [[paper](https://arxiv.org/abs/1612.07919)]
- [CVPR2018] DeblurGAN: Blind Motion Deblurring Using Conditional Adversarial Networks [[paper](https://arxiv.org/abs/1711.07064)] [[Code](https://github.com/KupynOrest/DeblurGAN)]
- [ECCV2018] The unreasonable effectiveness of texture transfer for single image super-resolution [[paper](https://link.springer.com/chapter/10.1007/978-3-030-11021-5_6)]
- [ECCV2018] Wilddash - creating hazard-aware benchmarks [[paper](https://link.springer.com/chapter/10.1007/978-3-030-01231-1_25)]
- [NIPS2018] Comparing deep neural networks against humans: object recognition when the signal gets weaker [[paper](https://arxiv.org/abs/1706.06969)]
- [2018] Task-Driven Super Resolution: Object Detection in Low-resolution Images [[paper](https://arxiv.org/abs/1803.11316)]
- [TPAMI2018] PsyPhy: A Psychophysics Driven Evaluation Framework for Visual Recognition [[paper](https://ieeexplore.ieee.org/abstract/document/8395028)]
- [MODA2019] Image Quality and Super Resolution Effects on Object Recognition Using Deep Neural Networks [[paper](https://doi.org/10.1117/12.2518524)]
- [CVPRW2019] The effects of super-resolution on object detection performance in satellite imagery [[paper](https://arxiv.org/abs/1812.04098)]
- [CVPR2019] Single image deraining: A comprehensive benchmark analysis](https://arxiv.org/abs/1903.08558) [[paper] [[Code](https://github.com/lsy17096535/Single-Image-Deraining)]
  - aim at visual enhancement, not improve recognition
- [2021] Dirty Pixels: Towards End-to-End Image Processing and Perception [[paper](https://arxiv.org/abs/1701.06487)]



### One model (enhancement + Vision)
- [NIPS2013] Adaptive multi-column deep neural networks with application to robust image denoising [[paper](https://proceedings.neurips.cc/paper/2013/file/e49b8b4053df9505e1f48c3a701c0682-Paper.pdf)]
- [CVPR2016] Studying Very Low Resolution Recognition Using Deep Networks [[paper](https://arxiv.org/abs/1601.04153)]
- [ICIP2016] Joint visual denoising and classification using deep learning [[paper](https://arxiv.org/abs/1612.01075)]
- [DICTA2017] Enhancing the performance of convolutional neural networks on quality degraded datasets [[paper](https://arxiv.org/abs/1710.06805)]
- [ICCV2017] AOD-Net: All-in-One Dehazing Network [[paper](https://ieeexplore.ieee.org/abstract/document/8237773)]
- [CVPR2018] Classification-driven dynamic image enhancement [[paper](https://arxiv.org/abs/1710.07558)]
- [IJCAI2018] When image denoising meets high-level vision tasks: a deep learning approach [[paper](https://arxiv.org/abs/1706.04284)] [[Code](https://github.com/Ding-Liu/DeepDenoising)]
- [ECCV2020] URIE: Universal Image Enhancement for Visual Recognition in the Wild [[paper](https://arxiv.org/abs/2007.08979)] [[Code](https://github.com/taeyoungson/urie)]



### Application
**face recognition (deblurring, super-resolution, hallucination)  
person re-identification  
Iris recognition 虹膜识别  
fingerprint recognition**
- [ISSPA2005] Face recognition from super-resolved images [[paper](https://ieeexplore.ieee.org/abstract/document/1581026)]
- [ECBTAS2007] Multi-frame super-resolution for face recognition [[paper](https://ieeexplore.ieee.org/abstract/document/4401949/)]
- [ICB2007] Super-Resolved Faces for Improved Face Recognition from Surveillance Video [[paper](https://link.springer.com/chapter/10.1007/978-3-540-74549-5_1)]
- [CVIU2008] Improving long range and high magnification face recognition: Database acquisition, evaluation, and enhancement [[paper](https://doi.org/10.1016/j.cviu.2007.09.004)]
- [CVPR2008] Simultaneous super-resolution and feature extraction for recognition of low-resolution faces [[paper](https://ieeexplore.ieee.org/abstract/document/4587810)]
- [CVPR2009] Facial deblur inference to improve recognition of blurred faces [[paper](https://ieeexplore.ieee.org/abstract/document/5206750)]
- [TNN2010] Super-resolution method for face recognition using nonlinear mappings on coherent features [[paper](https://ieeexplore.ieee.org/abstract/document/5624630/)]
- [CVPRW2011] Face recognition in video with closed-loop super-resolution [[paper](https://ieeexplore.ieee.org/abstract/document/5981748)]
- [ICCV2011] Close the loop: Joint blind image restoration and recognition with sparse representation prior [[paper](https://ieeexplore.ieee.org/abstract/document/6126315)]
- [TPAMI2012] A Blur-Robust Descriptor with Applications to Face Recognition [[paper](https://ieeexplore.ieee.org/abstract/document/6127874)]
- [JVCIP2012] Evaluation of image resolution and super-resolution on face recognition performance [[paper](https://doi.org/10.1016/j.jvcir.2011.06.004)]
- [CVPR2015] Super-Resolution Person Re-Identification With Semi-Coupled Low-Rank Discriminant Dictionary Learning [[paper](https://openaccess.thecvf.com/content_cvpr_2015/html/Jing_Super-Resolution_Person_Re-Identification_2015_CVPR_paper.html)]
- [BMVC2015] Convolutional neural networks for direct text deblurring [[paper](http://www.bmva.org/bmvc/2015/papers/paper006/paper006.pdf)]
- [SIU2016] Facial image super resolution using sparse representation for improving face recognition in surveillance monitoring [[paper](https://ieeexplore.ieee.org/abstract/document/7495771)]
- [AMDO2016] Convolutional Neural Network Super Resolution for Face Recognition in Surveillance Monitoring [[paper](https://link.springer.com/chapter/10.1007/978-3-319-41778-3_18)]
- [ECCV2016] Learning High-Order Filters for Efficient Blind Deconvolution of Document Photographs [[paper](https://link.springer.com/chapter/10.1007/978-3-319-46487-9_45)]
- [ECCV2016] Colorful Image Colorization [[paper](https://arxiv.org/abs/1603.08511)]
- [2016] Deep joint face hallucination and recognition [[paper](https://arxiv.org/abs/1611.08091)]
- [BIOSIG2016]  How image degradations affect deep cnn-based face recognition? [[paper](https://arxiv.org/abs/1608.05246)]
- [ICIP2017] Quality-adaptive deep learning for pedestrian detection [[paper](https://ieeexplore.ieee.org/abstract/document/8297071)]
- [ICCV2017] VPGNet: Vanishing Point Guided Network for Lane and Road Marking Detection and Recognition [[paper](https://arxiv.org/abs/1710.06288)]
- [ICCV2019] Delving into Robust Object Detection from Unmanned Aerial Vehicles: A Deep Nuisance Disentanglement Approach [[paper](https://arxiv.org/abs/1908.03856)]
- [ICIP2019] Quality-adaptive deep learning for pedestrian detection [[paper](https://engineering.purdue.edu/~dgueraco/content/pedestrian-two-stages.pdf)]