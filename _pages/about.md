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



# 🎖 Honors and Awards


# 📖 Educations
 

# 💬 Invited Talks


# 💻 Internships
  - 
