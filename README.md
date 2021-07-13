# AI_ComplexEnv
Object Detection and Recognition in Complex Environmental Conditions

## 小方向
- 去沙尘算法（无数据集，需要自己做）
- 光照处理算法（尽量兼容低光和高光）
- 运动模糊处理算法（公共数据集多为单反相机拍摄）
- 极小目标的目标检测算法
- 小目标的超分辨率算法
- 对遮挡鲁棒的目标检测算法
- 关键帧及关键区域提取算法
- 场景分类算法（自动判断是哪种恶劣天气）


## 大方向
干扰恶劣环境下降质视频的重建及识别

### Paper
#### Image/Video Quality Assessment
- [MM2019] [Quality Assessment of In-the-Wild Videos](https://arxiv.org/abs/1908.00375) [[Code](https://github.com/lidq92/VSFA)]
  - 无参考视频质量评价神经网络算法


#### Restoration 图像修复
- [ECCV2020] [Learning Disentangled Feature Representation for Hybrid-distorted Image Restoration](https://arxiv.org/pdf/2007.11430.pdf)
- [CVPR2020] [Learning Invariant Representation for Unsupervised Image Restoration](https://arxiv.org/abs/2003.12769)


#### Quality Enhancement 质量增强
- [CVPR2018] [Multi Frame Quality Enhancement for Compressed Video](https://link.zhihu.com/?target=http%3A//arxiv.org/abs/1803.04680) [[Code](github.com/ryangBUAA/MFQE.git)]


#### Reconstruction 重建
- [CVPR2020] [EventSR: From Asynchronous Events to Image Reconstruction, Restoration, and Super-Resolution via End-to-End Adversarial Learning](https://arxiv.org/abs/2003.07640)



### Blog
- [图像质量评价和视频质量评价(IQA/VQA)](https://www.cnblogs.com/buyizhiyou/p/12090605.html)
- [视频/图像质量评价综述] [[1](https://zhuanlan.zhihu.com/p/54539091)] [[2](https://zhuanlan.zhihu.com/p/54950132)] [[3](https://zhuanlan.zhihu.com/p/55101558)] [[4](https://zhuanlan.zhihu.com/p/55111820)] [[5](https://zhuanlan.zhihu.com/p/55189941)]
- [CVPR2021视频质量增强竞赛：数据库、方法及结果汇总](https://zhuanlan.zhihu.com/p/368256419)