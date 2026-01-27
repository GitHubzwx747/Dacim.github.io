---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<span class='anchor' id='about-me'></span>

曾德炉，博士，教授，博士生导师/硕士生导师。曾在相关领域发表论文100余篇，包括IEEE等著名会刊，如IEEE Trans. Neural Networks and Learning Systems, IEEE Trans. Image Processing, IEEE Geoscience and Remote Sensing Letters, IEEE Signal Processing Letters ，及ICML，AAAI，IJCAI，ICCV，CVPR，ICASSP等视频处理模式识别顶级会议。主持国家及省部级项目多项：包括国家自然科学基金项目3项，中国博士后基金项目等；参与国家及省部级项目多项等；主持横向项目多项。

学术义务工作：ACM会员，CCF会员，IEEE会员，参与NSFC评审等；并参与多个国际期刊审稿，包括IEEE TIP，IEEE ITS，IEEE TNNLS，IEEE TII， IEEE TEI，IEEE TMM，IEEE SMCb，Neural Networks，Neurocomputing等。
## 工作经历

- **2022.02 – 至今**　华南理工大学，电子与信息学院，教授  
- **2018.09 – 2021.01**　华南理工大学，数学学院信息与计算科学系，教授  
- **2018.11 – 2019.11**　哥伦比亚大学数据科学学院，访问学者（国家公派 CSC）  
- **2018.08 – 2018.09**　奥卢大学 CMVS，研究科学家（访问学者）  
- **2017.07 – 2017.09**　哥伦比亚大学数据科学学院，访问学者  
- **2016.07 – 2018.08**　华南理工大学，数学学院信息与计算科学系，副教授  
- **2013.04 – 2016.07**　厦门大学，信息科学与技术学院，副教授  
- **2010.02 – 2013.03**　华南理工大学，电子与信息学院，博士后（2011.09 获副研究员/副高资格）

## 教育经历

- **2005.09 – 2009.12**　华南理工大学，信号与信息处理，博士研究生  
  （研究方向：迭代学习理论、控制理论、信号与信息处理等）  
- **2003.09 – 2005.07**　华南理工大学，应用数学，硕士研究生  
  （研究方向：非线性发展方程及应用）  
- **2005.07 – 2005.09**　中山大学，全国数学暑期学习班，非学历培训  
  （学习主题：偏微分方程与微分几何）  
- **1999.09 – 2003.07**　华南理工大学，数学与应用数学，本科 / 学士

## 研究领域

- **主要领域**：图像处理与模式识别、大数据处理与分析、（统计）机器学习、偏微分方程应用  
- **其他涉及领域**：工程数学建模、人工智能与感知推理、最优化理论及应用、情感计算、通信／生物医学信息处理、物联网及软件定义网络等

# 🔥 News
- *2026.1*: Our paper about *Diffusion Bridge Variational Inference for Deep Gaussian Processes* is accepted to International Conference on Learning Representations (ICLR).
- *2026.1*: Our paper about *Don't Forget Its Variance! The Minimum Path Variance Principle for Accurate and Stable Score-Based Density Ratio* is accepted to  International Conference on Learning Representations (ICLR).
- *2025.10*: Our paper about *diffusion informer for time series modeling* is accepted to Expert Systems With Applications (ESWA).
- *2025.10*: Our paper about *wavelet diffusion for time series modeling* is accepted to IEEE TIM.
- *2025.09*: Our paper about *diffusion modeling acceleration* is accepted to NeurIPS 2025.
- *2025.09*: Our paper about *normalizing flow* is accepted to Pattern Recognition (PR).
- *2025.08*: Our paper about *diffusion models for low-level CV* is accepted to Neurocomputing.
- *2025.10*: Our paper about *time series modeling* is accepted to IEEE Transactions on Instrumentation & Measurement (TIM).
- *2025.05*: Our paper about *stable & efficient density ratio estimation* is accepted to ICML 2025.
- *2024.06*: Our paper about *Sparse Inducing Points in Deep Gaussian Processes: Enhancing Modeling with Denoising Diffusion Variational Inference* is accepted to ICML 2024. 
- *2022.02*: Our paper about *efficient continuous normalizing flow* is accepted to CVPR 2022. 

# 📝 Publications 
## Deep Generative Modeling

<div class='paper-box'><div class='paper-box-image'><img src='images/evodiff.png' alt="sym" width="100%"></div>
<div class='paper-box-text' markdown="1">

[**EVODiff: Entropy-aware Variance Optimized Diffusion Inference**](https://openreview.net/forum?id=rKASv92Myl), Shigui Li, **`Wei Chen`**, Delu Zeng*

**NeurIPS 2025** \| [**Paper**](https://openreview.net/pdf?id=rKASv92Myl) \| [**Code**](https://github.com/ShiguiLi/EVODiff) \| [**News&#127881;**](https://mp.weixin.qq.com/s/mviiMgexMub_os4oSIdwiQ)

- Introduces an information-theoretic view: successful denoising reduces conditional entropy in reverse transitions.
- Proposes EVODiff, a reference-free diffusion inference framework that optimizes conditional variance to reduce transition and reconstruction errors, improving sample quality and reducing inference cost.
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><img src='images/eiw_flow.png' alt="sym" width="100%"></div>
<div class='paper-box-text' markdown="1">

[**Entropy-informed weighting channel normalizing flow for deep generative models**](https://doi.org/10.1016/j.patcog.2025.112442), **`Wei Chen`**#, Shian Du#, Shigui Li#, Delu Zeng*, John Paisley

**Pattern Recognition (PR) 2025** \| [**Paper**](https://doi.org/10.1016/j.patcog.2025.112442) \| [**Code**](https://github.com/ShianDu/EIW-Flow)

- Proposes Entropy-Informed Weighting Channel Normalizing Flow (EIW-Flow), enhancing multi-scale normalizing flows with a regularized, feature-dependent operation that generates channel-wise weights and shuffles latent variables before splitting.
- Empirically achieves state-of-the-art density estimation and competitive sample quality with minimal computational overhead on multiple benchmarks.
</div>
</div>


<div class='paper-box'>
<div class='paper-box-image'><img src='images/reciprocalla.png' alt="sym" width="100%"></div>
<div class='paper-box-text' markdown="1">

[**ReciprocalLA-LLIE: Low-light image enhancement with luminance-aware reciprocal diffusion process**](https://doi.org/10.1016/j.neucom.2025.131438), Zhiqi Lin, **`Wei Chen`**, Jian Xu, Delu Zeng*, Min Chen

**Neurocomputing 2025** \| [**Paper**](https://doi.org/10.1016/j.neucom.2025.131438)

- Proposes a reciprocal diffusion process (between low-light and well-exposed images) within a score-based DDPM framework via drift adjustment, with the low-light image as an endpoint state rather than only a conditional input.
- Introduces a Luminance Adjustment Block for robust global luminance control, suppressing noise and preserving details.
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><img src='images/toflow.png' alt="sym" width="100%"></div>
<div class='paper-box-text' markdown="1">

[**To-Flow: Efficient Continuous Normalizing Flows with Temporal Optimization Adjoint with Moving Speed**](https://arxiv.org/abs/2203.10335), Shian Du#, Yihong Luo#, **`Wei Chen`**#, Jian Xu, Delu Zeng*

**CVPR 2022** \| [**Paper**](https://arxiv.org/abs/2203.10335) \| [**Code**](https://github.com/ShianDu/TO-FLOW)

- Continuous normalizing flows (CNFs) via neural ODEs are costly to train on large datasets; To-Flow proposes *temporal optimization* by alternately optimizing network weights and evolutionary time (coordinate descent) with temporal regularization for stability.
- **Key result**: accelerates flow training by about 20% while maintaining performance.
</div>
</div>


## Density Ratio Estimation

<div class='paper-box'><div class='paper-box-image'><img src='images/d3re.png' alt="sym" width="100%"></div>
<div class='paper-box-text' markdown="1">

[**Dequantified Diffusion-Schrödinger Bridge for Density Ratio Estimation**](https://openreview.net/forum?id=zvyHCOcwsw), **`Wei Chen`**, Shigui Li, Jiacheng Li, Junmei Yang, John Paisley, Delu Zeng*

**ICML 2025** \| [**Paper**](https://openreview.net/forum?id=zvyHCOcwsw) \| [**Code**](https://github.com/Hoemr/Dequantified-Diffusion-Bridge-Density-Ratio-Estimation.git)

- Proposes D3RE, a unified framework for robust and stable density ratio estimation under distribution mismatch (density-chasm / support-chasm), addressing instability from divergent time scores near boundaries.
- Introduces dequantified diffusion bridge interpolant (DDBI) for support expansion and stabilized time scores; further extends to dequantified Schrödinger bridge interpolant (DSBI) to enhance accuracy and efficiency.
</div>
</div>


## Time Series Forecast

<div class='paper-box'><div class='paper-box-image'><img src='images/deepara.png' alt="sym" width="100%"></div>
<div class='paper-box-text' markdown="1">

[**DeepAR-Attention probabilistic prediction for stock price series**](https://doi.org/10.1007/s00521-024-09916-3), Jiacheng Li, **`Wei Chen`**, Zhiheng Zhou, Junmei Yang, Delu Zeng*

**Neural Computing and Applications 2024** \| [**Paper**](https://doi.org/10.1007/s00521-024-09916-3)

- Proposes a DeepAR-Attention probabilistic forecasting approach for stock price series.
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><img src='images/ODE_LSTM.png' alt="sym" width="100%"></div>
<div class='paper-box-text' markdown="1">

[**Neural ordinary differential equation networks for fintech applications using Internet of Things**](https://doi.org/10.1109/JIOT.2024.3376748), Jiacheng Li, **`Wei Chen`**, Yican Liu, Junmei Yang, Delu Zeng*, Zhiheng Zhou

**IEEE Internet of Things Journal (IoTJ) 2024** \| [**Paper**](https://doi.org/10.1109/JIOT.2024.3376748) 

- Develops neural ODE network approaches for fintech applications in IoT settings.
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><img src='images/evolvinformer.png' alt="sym" width="100%"></div>
<div class='paper-box-text' markdown="1">

[**Integrating Ordinary Differential Equations with Sparse Attention for Power Load Forecasting**](https://doi.org/10.1109/TIM.2025.3581667), Jiacheng Li, **`Wei Chen`**, Yican Liu, Junmei Yang, Zhiheng Zhou, Delu Zeng*

**IEEE Transactions on Instrumentation and Measurement (T-IM) 2025** \| [**Paper**](https://doi.org/10.1109/TIM.2025.3581667)

- Proposes EvolvInformer: integrates an ODE solver into a ProbSparse self-attention decoder to model continuous-time hidden state dynamics for nonstationary long-sequence load forecasting.
- Reports a 29.7% MSE reduction versus state-of-the-art baselines while preserving logarithmic memory complexity.
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><img src='images/diffinformer.jpg' alt="sym" width="100%"></div>
<div class='paper-box-text' markdown="1">

[**Diffinformer: Diffusion Informer model for long sequence time-series forecasting**](https://doi.org/10.1016/j.eswa.2025.129944), Jiacheng Li, **`Wei Chen`**, Yican Liu, Junmei Yang, Zhiheng Zhou, Delu Zeng*

**Expert Systems with Applications (ESWA) 2025** \| [**Paper**](https://doi.org/10.1016/j.eswa.2025.129944)

- Proposes Diffinformer: combines conditional diffusion models with Informer’s ProbSparse attention distilling mechanism, incorporating diffusion outputs into the decoder to better capture long-range dependencies.
- Demonstrates consistent improvements over corresponding baselines across five large-scale datasets under limited computational resources.
</div>
</div>

- Guo, Pengfei, Lang He, Shuangyin Liu, Delu Zeng, and Hantao Liu. "Underwater Image Quality Assessment: Subjective and Objective Methods." *IEEE Transactions on Multimedia* (2021).

- Bo Pan, Jinxuan Tao, Xianyang Bao, Jie Xiao, Hongsheng Liu, Xiaotong Zhao, and Delu Zeng. "Quantitative study of starch swelling capacity during gelatinization with an efficient automatic segmentation methodology." *Carbohydrate Polymers* 255 (2021): 117372.

- Delu Zeng, Minyu Liao, Mohammad Tavakolian, Yulan Guo, Bolei Zhou, Dewen Hu, Matti Pietikäinen, Li Liu. "Deep Learning for Scene Classification: A Survey." *arXiv preprint arXiv:2101.10531*, 2021.

- Pengfei Guo, Delu Zeng, Yunbo Tian, Shuangyin Liu, Hantao Liu, and Daoliang Li. "Multi-scale enhancement fusion for underwater sea cucumber images based on human visual system modelling." *Computers and Electronics in Agriculture* 175 (2020): 105608.

- Qianl Ma, Sen Li, Wanqing Zhuang, Sen Li, Jiabing Wang and Delu Zeng\*. "Self-Supervised Time Series Clustering With Model-Based Dynamics." *IEEE Transactions on Neural Networks and Learning Systems*, doi: [10.1109/TNNLS.2020.3016291](https://doi.org/10.1109/TNNLS.2020.3016291).

- Xiangrui Xing, Xian Yu, Wenao Ma, Vue Huang, Delu Zeng, Xinghao Ding. "Bindctnet: A Simple Binary Dct Network for Image Classification." *2018 IEEE International Conference on Acoustics, Speech and Signal Processing (ICASSP)*.

- Yixuan He, Tianyi Hu, Delu Zeng\*. "Scan-flood Fill (SCAFF): an Efficient Automatic Precise Region Filling Algorithm for Complicated Regions." *Proceedings of the IEEE Conference on Computer Vision and Pattern Recognition Workshops*, 2019.

- Tao Zheng, Bo Li, Delu Zeng, Zhiheng Zhou. "Delving into the Impact of Saliency Detector: A GeminiNet for Accurate Saliency Detection." *International Conference on Artificial Neural Networks*, 2019.

- Shulian Cai, Jiabin Huang, Jing Chen, Yue Huang, Xinghao Ding, **Delu Zeng\***. "Prominent edge detection with deep metric expression and multi-scale features." *Multimedia Tools and Applications*, 2018. [PDF](https://link.springer.com/article/10.1007/s11042-018-6581-5)

- Shulian Cai, Jiabin Huang, **Delu Zeng\***, Xinghao Ding, John Paisley. "MEnet: A Metric Expression Network for Salient Object Segmentation." *International Joint Conference on Artificial Intelligence (IJCAI)*, 2018, Stockholm, Sweden. [PDF](http://www.columbia.edu/～jwp2128/Papers/CaiHuangZengetal2018.pdf) | [Code/Ref](https://github.com/scutDACIM/MEnet)

- WU Jiawen, LIU Qinting, **Delu Zeng**, Ding Xinghao, Li Lin. "Speech Enhancement Based on Nonparametric Bayesian Method." *Journal of Xiamen University (Natural Science)*, 2017, 56(03): 423–428. [PDF](http://202.38.236.221/e:/images/JXUM0831.jpg)

- Yun Zhang, Juilee Thakara, David J. Topham, Ann R. Falsey, **Delu Zeng**, and Xing Qiu\*. "Certain equivalence relationships of regularized regressions." *Mathematics for Applications*, Nov. 23, 2017 (Accepted). [PDF](http://202.38.236.221/e:/images/JXUM0831.jpg)

- Xin He, **Delu Zeng\***. "Real-time Pedestrian Warning System on Highway using Deep Learning Methods." *ISPACS 2017 - International Symposium on Intelligent Signal Processing and Communication Systems*, Nov. 6–9, 2017 (EI). [PDF](https://ispacs2017.hqu.edu.cn/)

- Shulian Cai, Jiabin Huang, Xinghao Ding and **Delu Zeng\***. "Semantic Edge Detection Based on Deep Metric Learning." *ISPACS 2017*, Nov. 6–9, 2017 (EI). [PDF](https://ispacs2017.hqu.edu.cn/)

- Hong Tang, **Delu Zeng\***, Xin Liu, Jiabin Huang and Yinghao Liao. "Resource Allocation and Optimization Based on Queuing Theory and BP Network." *ICONIP 2017 - The 24th International Conference on Neural Information Processing*, Nov. 14–18, 2017 (EI). [PDF](http://www.iconip2017.org/)

- Jinxuan Tao, Jiabin Huang, Long Yu, Zikang Li, Hongsheng Liu, Bo Yuan, **Delu Zeng**. "A new methodology combining microscopy observation with Artificial Neural Networks for the study of starch gelatinization." *Food Hydrocolloids* 74 (2017): 151–158. (JCR1) [PDF](https://www.sciencedirect.com/science/article/pii/S0268005X17308032)

- X. Fu, J. Huang, **D. Zeng**, Y. Huang, X. Ding, J. Paisley. "Removing rain from single images via a deep detail network." *IEEE Conference on Vision and Pattern Recognition (CVPR)*, Honolulu, HI, USA, 2017. [PDF](http://www.columbia.edu/～jwp2128/Papers/FuHuangetal2017.pdf)

- Lin Li, Jiawen Wu, Xinghao Ding, Qingyang Hong, **Delu Zeng\***. "Speech Enhancement Based on Nonparametric Factor Analysis." *ISCSLP 2016 - The 10th International Symposium on Chinese Spoken Language Processing*, 2016 (EI). [PDF](https://ieeexplore.ieee.org/document/7918427)

- Xiaobo Shi, Yixue Hao, **Delu Zeng\***, Lu Wang, M. Shamim Hossain, Sk Md Mizanur Rahman, Abdulhameed Alelaiwi. "Cloud-Assisted Mood Fatigue Detection System." *Mobile Networks and Applications* 21, no. 5 (2016): 744–752. (SCI) [PDF](https://link.springer.com/article/10.1007/s11036-016-0757-x)

- **Delu Zeng**, Yuwen Hu, Yue Huang, Zhiliang Xu, Xinghao Ding. "Pan-sharpening with structural consistency and l_1/2 gradient prior." *Remote Sensing Letters* 7, no. 12 (2016): 1170–1179. (SCI, JCR3) [PDF](https://www.tandfonline.com/doi/abs/10.1080/2150704X.2016.1222098) | [Code](http://smartdsp.xmu.edu.cn/)

- Xinghao Ding, Liqin Chen, Yue Huang, **Delu Zeng\***. "Single image rain and snow removal via guided L0 smoothing filter." *Multimedia Tools and Applications* 75, no. 5 (2016): 2697–2712. (SCI) [PDF](https://link.springer.com/article/10.1007/s11042-015-2657-7)

- Xueyang Fu, **Delu Zeng**, Yue Huang, Yinghao Liao, Xinghao Ding\*, and John Paisley. "A Fusion-based Enhancing Method for Weakly Illuminated Images." *Signal Processing* 129 (2016): 82–96. [PDF](http://smartdsp.xmu.edu.cn/memberpdf/fuxueyang/SP2016.pdf)

- Peixian Zhuang, Xueyang Fu, Yue Huang, **Delu Zeng**, and Xinghao Ding. "A Novel Framework Method for Non-Blind Deconvolution Using Subspace Images Priors." *Signal Processing: Image Communication* 46 (2016): 17–28. (SCI, JCR3) [PDF](http://smartdsp.xmu.edu.cn/memberpdf/fuxueyang/SPIC2016.pdf)

- Xueyang Fu, **Delu Zeng**, Yue Huang, Xiao-ping Zhang and Xinghao Ding. "A weighted variational model for simultaneous reflectance and illumination estimation." *IEEE Conference on Computer Vision and Pattern Recognition (CVPR 2016)*, Las Vegas, US, 2016. [Abstract/Code](http://smartdsp.xmu.edu.cn/cvpr2016.html)

- Tong Zhao, Lin Li, Xinghao Ding, Yue Huang, and **Delu Zeng\***. "Saliency detection with spaces of background-based distribution." *IEEE Signal Processing Letters* 23, no. 5 (2016): 683–687. [PDF](https://ieeexplore.ieee.org/document/7438788) | [Abstract/Code](http://smartdsp.xmu.edu.cn/SPL2016.html)

- Yiyong Jiang, Xinghao Ding, **Delu Zeng**, Yue Huang and John Paisley. "Pan-sharpening with a hyper-Laplacian penalty." *International Conference on Computer Vision (ICCV 2015)*, Santiago, Chile, 2015. [PDF](https://www.cv-foundation.org/openaccess/content_iccv_2015/html/Jiang_Pan-Sharpening_With_a_ICCV_2015_paper.html)

- Xueyang Fu, J. Wang, **Delu Zeng**, Yue Huang, Xinghao Ding. "Remote Sensing Image Enhancement using Regularized-Histogram Equalization and DCT." *IEEE Geoscience and Remote Sensing Letters* 12, no. 11 (2015): 2301–2305. [PDF](http://smartdsp.xmu.edu.cn/memberpdf/fuxueyang/GRSL2015.pdf)

- Xueyang Fu, Yinghao Liao, **Delu Zeng**, Yue Huang, Xiao-ping Zhang and Xinghao Ding. "A Probabilistic Method for Image Enhancement with Simultaneous Illumination and Reflectance Estimation." *IEEE Transactions on Image Processing* 24, no. 12 (2015): 4965–4977. [PDF](http://smartdsp.xmu.edu.cn/memberpdf/fuxueyang/TIP2015.pdf)

- **Delu Zeng**, Zhiheng Zhou, Shengli Xie. "Image Segmentation based on the Poincare Map Method." *IEEE Transactions on Image Processing* 21, no. 3 (2012): 946–957. [PDF](http://smartdsp.xmu.edu.cn/memberpdf/zeng/2012TIP.pdf)

- Tong Zhao, Jiawen Wu, Lin Li, **Delu Zeng\***, Zhaoshui He. "Semi-supervised shape classification based on low rank constraint active contour." *International Conference on Mechatronics and Control (ICMC)*, Jinzhou, 2014, pp. 1069–1073. [PDF](https://ieeexplore.ieee.org/document/7231717)

- **Delu Zeng**, Zhiheng Zhou, et al. "Coarse-to-fine Boundary Location with a SOM-like Method." *IEEE Transactions on Neural Networks* 21, no. 3 (2010): 481–493. [PDF](http://smartdsp.xmu.edu.cn/memberpdf/zeng/2010TNN.pdf)

- Shengli Xie, **Delu Zeng\***, Zhiheng Zhou. "Arranging and Interpolating Sparse Unorganized Feature Points With Geodesic Circular Arc." *IEEE Transactions on Image Processing* 18, no. 3 (2009): 582–595. [PDF](http://smartdsp.xmu.edu.cn/memberpdf/zeng/2009TIP.pdf)

- Weijun Liu, Jianzhong Lin, Congbo Cai, **Delu Zeng**, and Xinghao Ding. "Fast magnetic susceptibility reconstruction using L0 norm of gradient." *IEEE International Conference on Acoustics, Speech and Signal Processing (ICASSP)*, South Brisbane, QLD, 2015, pp. 907–911. [PDF](https://ieeexplore.ieee.org/document/7178101)

- Yue Huang, Xin Chen, Jun Zhang, **Delu Zeng**, Dandan Zhang, Xinghao Ding. "Single-trial ERPs denoising via collaborative filtering on ERPs images." *Neurocomputing* 174, Part B (2016): 858–865. [PDF](https://www.sciencedirect.com/science/article/abs/pii/S0925231214009801)

- Peixian Zhuang, Yue Huang, **Delu Zeng**, Xinghao Ding. "Mixed noise removal based on a novel non-parametric Bayesian sparse outlier model." *Neurocomputing* 174, Part B (2016): 858–865. [PDF](https://www.sciencedirect.com/science/article/abs/pii/S0925231215014496)

- Xueyang Fu, Yue Huang, **Delu Zeng**, Xinghao Ding and Xiao-Ping Zhang. "A fusion-based enhancing approach for single sandstorm image." *IEEE International Workshop on Multimedia Signal Processing (MMSP)*, 2014. [PDF](http://smartdsp.xmu.edu.cn/memberpdf/fuxueyang/2.pdf) | [Matlab code](http://smartdsp.xmu.edu.cn/memberpdf/fuxueyang/MMSP_code.zip)

- Xueyang Fu, **Delu Zeng**, Yue Huang, Xinghao Ding and Xiao-Ping Zhang. "A variational framework for single low light image enhancement using bright channel prior." *IEEE Global Conference on Signal and Information Processing (GlobalSIP)*, 2013. [PDF](http://smartdsp.xmu.edu.cn/memberpdf/fuxueyang/5.pdf) | [Matlab code](http://smartdsp.xmu.edu.cn/memberpdf/fuxueyang/GlobalSIP_code.zip)

- Xueyang Fu, Qin Lin, Wei Guo, Yue Huang, **Delu Zeng**, and Xinghao Ding. "A novel Retinex algorithm based on alternating direction optimization." *Sixth International Symposium on Precision Mechanical Measurements*, SPIE, 2013. [PDF](http://smartdsp.xmu.edu.cn/memberpdf/fuxueyang/6.pdf)

- **Delu Zeng**, Zhiheng Zhou, Shengli Xie. "Vector bundle constraint for particle swarm optimization and its application to active contour modeling." *Progress in Natural Science* 17, no. 10 (2007): 1220–1225. [PDF](http://d.wanfangdata.com.cn/periodical/zrkxjz-e200710015)

- **Delu Zeng**, Zhiheng Zhou, Shengli Xie. "Construction of Compact RBF Network by Refining Coarse Clusters and Widths." *Journal of Systems Engineering and Electronics* 20, no. 6 (2009): 1309–1315. [PDF](https://ieeexplore.ieee.org/document/6074585)

- **Delu Zeng**, Shengli Xie, Zhiheng Zhou. "Improved clustering and anisotropic gradient descent algorithm for compact RBF network." *ICONIP 2006*, Lecture Notes in Computer Science, vol. 4233, pp. 806–813. [PDF](http://smartdsp.xmu.edu.cn/memberpdf/zeng/ICONIP06.pdf)

- **Delu Zeng**, Zhiheng Zhou, et al. "Fast blocking artifacts reduction algorithm based on contrast enhancement technique." *International Conference on Communications, Circuits and Systems (ICCCS)*, vol. I, pp. 497–499, 2006. [PDF](https://www.infona.pl/resource/bwmeta1.element.ieee-art-000004063929)

## 科研项目

- **国家自然科学基金面上项目**，基于PDE的鲁棒视觉显著性目标感知先验的图像分割（61571005），2016/01–2019/12，主持。（备注：信息与数学领域交叉类项目）
- **国家自然科学基金青年项目**，目标检测与提取变分模型的关键问题研究（61103121），2012/01–2014/12，主持。
- **国家自然科学基金项目**，目标分割中的视觉显著先验的同质性描述（61811530271），在研，主持。
- **中央高校基本科研业务费**，基于统计先验和变分框架下的图像去雾霾方法研究，在研，主持，2018.09–2020.08。
- **广州市产业技术重大攻关计划现代产业技术专题项目**，基于深度学习的企业大脑关键技术研发与产业化，2017/09–2020/10，60/400万，单位内主持（企业联合申报）。
- **广州市科技计划一般项目**，图像去雨雾问题的大数据与深度架构逆问题建模，2018/04–2021/03，主持。
- **厦门大学校长基金**，结合贝叶斯框架的偏微分方程图像目标分割鲁棒性方法（20720150093），2015/01–2016/12，主持。
- **中国博士后基金**，变分法图像分割有效实现的几个关键问题研究（20100470923），2010/02–2012/02，主持。
- **国家自然科学基金青年项目**，变结构向量场下活动轮廓模型的研究（61003170），2011/01–2013/12，第一参与。

## 教学活动

- 机器智能与大数据分析（研究生选修）
- 深度架构逼近与变分推断（博士生选修）
- 最优化理论与应用（研究生选修）
- 数值计算方法（研究生选修）
- 工程数学与建模（本科生必修，涵盖数学物理方程，复变函数，傅立叶分析）
- 微积分（本科生公共课）
- 医用高等数学（本科生公共课）
- 信息论与编码（本科生专业必修课）
- 数理金融（本科生专业选修课）
- 计算机软件技术基础（本科生必修）
- 数字图像处理（本科生与研究生必修通选课）
- 国际数学建模（ACM／ICM）教练 
