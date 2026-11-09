# 事件相机论文库 · Event Camera Papers

按 8 个学习模块归档的 **50 条文献 / 48 个 PDF**（另有 2 篇仅提供原文链接）。全部 PDF 已通过逐页完整性校验（页数、每页文本、文件尾结构），在本地阅读器中可正常打开。

## 网页里打不开 PDF 怎么办

GitHub 的 PDF 预览依赖独立域名 `viewscreen.githubusercontent.com`，国内网络下常被阻断，页面会提示 `Unable to render code block` 或显示空白——**这不是文件损坏**。三种可用方式：

1. **单篇下载**：打开文件页面后点右上角下载图标（↓），保存到本地用 PDF 阅读器打开。
2. **整仓打包下载**：
   `https://github.com/stevenzzy9/NeuroNova-Event-Cameras-Papers/archive/refs/heads/main.zip`
3. **回到原始出处**：每篇都附 arXiv / 会议官方链接，可直接在浏览器打开。

单篇 raw 下载链接格式：

```
https://github.com/stevenzzy9/NeuroNova-Event-Cameras-Papers/raw/main/EventCamera-Coding/<模块目录>/<文件名>.pdf
https://github.com/stevenzzy9/NeuroNova-Event-Cameras-Papers/archive/refs/heads/main.zip
```

## 模块目录

- **01 事件表示**（5 个 PDF）— 综述与表示谱系：事件帧/体素/时间表面/集合/图/token
- **02 事件去噪与信号质量**（7 个 PDF）— 基准、学习式去噪、真实配对数据
- **03 事件光流与运动估计**（7 个 PDF）— 对比最大化、自监督、帧事件融合
- **04 事件几何与三维视觉**（5 个 PDF）— NeRF、高斯泼溅、双目视觉惯性里程计
- **05 事件视频重建与增强**（6 个 PDF）— E2VID 谱系、HDR、去模糊、扩散先验
- **06 事件语义理解**（6 个 PDF）— 检测、开放世界识别、开放词汇分割
- **07 事件编码与脉冲神经网络**（7 个 PDF）— 频率×时间编码、SNN 表示与检测
- **08 典型应用（选学）**（5 个 PDF）— 驾驶、眼动、四足机器人、乒乓机器人

---

## 01 事件表示

综述与表示谱系：事件帧/体素/时间表面/集合/图/token。收录 6 篇。

| 编号 | 标题 | 年份 | 出处 | PDF | 原文链接 |
| --- | --- | --- | --- | --- | --- |
| 01-01 | A Systematic Survey on Event Camera Representation Learning | 2026 | arXiv 2026（预印本/在审） | [PDF](./EventCamera-Coding/01_Event-Representation/01_Systematic_Survey_Event_Representation_2026.pdf) | [原文](https://arxiv.org/abs/2606.23078) |
| 01-02 | EvRepSL: Event-Stream Representation via Self-Supervised Learning for Event-Based Vision | 2024 | IEEE TIP 2024 | [PDF](./EventCamera-Coding/01_Event-Representation/02_EvRepSL_2024.pdf) | [原文](https://arxiv.org/abs/2412.07080) |
| 01-03 | Event Voxel Set Transformer for Spatiotemporal Representation Learning on Event Streams | 2024 | IEEE TCSVT 2024 | [PDF](./EventCamera-Coding/01_Event-Representation/03_Event_Voxel_Set_Transformer_2024.pdf) | [原文](https://arxiv.org/abs/2303.03856) |
| 01-04 | EventMG: Efficient Multilevel Mamba-Graph Learning for Spatiotemporal Event Representation | 2025 | NeurIPS 2025 | 仅链接 | [原文](https://openreview.net/forum?id=OmtKcee8NA) |
| 01-05 | Event2Vec: Processing Neuromorphic Events Directly by Representations in Vector Space | 2026 | ICML 2026 | [PDF](./EventCamera-Coding/01_Event-Representation/05_Event2Vec_2026.pdf) | [原文](https://arxiv.org/abs/2504.15371) |
| 01-06 | Neural Events: Discrete Asynchronous Autoencoders for Event-Based Vision | 2026 | arXiv 2026（预印本） | [PDF](./EventCamera-Coding/01_Event-Representation/06_Neural_Events_2026.pdf) | [原文](https://arxiv.org/abs/2606.19835) |

## 02 事件去噪与信号质量

基准、学习式去噪、真实配对数据。收录 7 篇。

| 编号 | 标题 | 年份 | 出处 | PDF | 原文链接 |
| --- | --- | --- | --- | --- | --- |
| 02-01 | E-MLB: Multilevel Benchmark for Event-Based Camera Denoising | 2023 | IEEE TMM 2023（评测基准，2023） | [PDF](./EventCamera-Coding/02_Event-Denoising-and-Signal-Quality/01_EMLB_Multilevel_Benchmark_2023.pdf) | [原文](https://arxiv.org/abs/2303.11997) |
| 02-02 | Event Probability Mask (EPM) and Event Denoising Convolutional Neural Network (EDnCNN) for Neuromorphic Cameras | 2020 | CVPR 2020（奠基/必读经典） | [PDF](./EventCamera-Coding/02_Event-Denoising-and-Signal-Quality/02_EPM_EDnCNN_2020.pdf) | [原文](https://arxiv.org/abs/2003.08282) |
| 02-03 | EventZoom: Learning to Denoise and Super Resolve Neuromorphic Events | 2021 | CVPR 2021（奠基/必读经典） | [PDF](./EventCamera-Coding/02_Event-Denoising-and-Signal-Quality/03_EventZoom_2021.pdf) | [原文](https://openaccess.thecvf.com/content/CVPR2021/html/Duan_EventZoom_Learning_To_Denoise_and_Super_Resolve_Neuromorphic_Events_CVPR_2021_paper.html) |
| 02-04 | LED: A Large-scale Real-world Paired Dataset for Event Camera Denoising | 2024 | CVPR 2024 | [PDF](./EventCamera-Coding/02_Event-Denoising-and-Signal-Quality/04_LED_Denoising_Dataset_2024.pdf) | [原文](https://arxiv.org/abs/2405.19718) |
| 02-05 | Fast Window-Based Event Denoising with Spatiotemporal Correlation Enhancement | 2025 | IEEE TPAMI 2025 | [PDF](./EventCamera-Coding/02_Event-Denoising-and-Signal-Quality/05_WedNet_2025.pdf) | [原文](https://arxiv.org/abs/2402.09270) |
| 02-06 | Revealing Latent Information: A Physics-inspired Self-supervised Pre-training Framework for Noisy and Sparse Events | 2025 | ACM MM 2025 | [PDF](./EventCamera-Coding/02_Event-Denoising-and-Signal-Quality/06_Revealing_Latent_Information_2025.pdf) | [原文](https://arxiv.org/abs/2508.05507) |
| 02-07 | EDformer: Transformer-Based Event Denoising Across Varied Noise Levels | 2024 | ECCV 2024 | [PDF](./EventCamera-Coding/02_Event-Denoising-and-Signal-Quality/07_EDformer_2024.pdf) | [原文](https://www.ecva.net/papers/eccv_2024/papers_ECCV/papers/03905.pdf) |

## 03 事件光流与运动估计

对比最大化、自监督、帧事件融合。收录 7 篇。

| 编号 | 标题 | 年份 | 出处 | PDF | 原文链接 |
| --- | --- | --- | --- | --- | --- |
| 03-01 | BlinkFlow: A Dataset to Push the Limits of Event-based Optical Flow Estimation | 2023 | IROS 2023（评测基准） | [PDF](./EventCamera-Coding/03_Event-Optical-Flow-and-Motion-Estimation/01_BlinkFlow_2023.pdf) | [原文](https://arxiv.org/abs/2303.07716) |
| 03-02 | A Unifying Contrast Maximization Framework for Event Cameras, with Applications to Motion, Depth, and Optical Flow Estimation | 2018 | CVPR 2018（奠基/必读经典） | [PDF](./EventCamera-Coding/03_Event-Optical-Flow-and-Motion-Estimation/02_Contrast_Maximization_2018.pdf) | [原文](https://arxiv.org/abs/1804.01306) |
| 03-03 | Unsupervised Event-based Learning of Optical Flow, Depth, and Egomotion | 2019 | CVPR 2019（奠基/必读经典） | [PDF](./EventCamera-Coding/03_Event-Optical-Flow-and-Motion-Estimation/03_Unsupervised_Event_Flow_Depth_2019.pdf) | [原文](https://arxiv.org/abs/1812.08156) |
| 03-04 | Bridge Frame and Event: Common Spatiotemporal Fusion for High-Dynamic Scene Optical Flow | 2025 | CVPR 2025 | [PDF](./EventCamera-Coding/03_Event-Optical-Flow-and-Motion-Estimation/04_Bridge_Frame_Event_2025.pdf) | [原文](https://arxiv.org/abs/2503.06992) |
| 03-05 | BAT: Learning Event-based Optical Flow with Bidirectional Adaptive Temporal Correlation | 2026 | AAAI 2026 | [PDF](./EventCamera-Coding/03_Event-Optical-Flow-and-Motion-Estimation/05_BAT_Event_Optical_Flow_2026.pdf) | [原文](https://arxiv.org/abs/2503.03256) |
| 03-06 | EDCFlow: Exploring Temporally Dense Difference Maps for Event-based Optical Flow Estimation | 2025 | CVPR 2025 | [PDF](./EventCamera-Coding/03_Event-Optical-Flow-and-Motion-Estimation/06_EDCFlow_2025.pdf) | [原文](https://arxiv.org/abs/2506.03512) |
| 03-07 | Nonlinear Motion-Guided and Spatio-Temporal Aware Network for Unsupervised Event-Based Optical Flow | 2025 | ICRA 2025 | [PDF](./EventCamera-Coding/03_Event-Optical-Flow-and-Motion-Estimation/07_ENMSTFlow_2025.pdf) | [原文](https://arxiv.org/abs/2505.05089) |

## 04 事件几何与三维视觉

NeRF、高斯泼溅、双目视觉惯性里程计。收录 5 篇。

| 编号 | 标题 | 年份 | 出处 | PDF | 原文链接 |
| --- | --- | --- | --- | --- | --- |
| 04-01 | A Survey of 3D Reconstruction with Event Cameras | 2025 | Computational Visual Media 2025 | [PDF](./EventCamera-Coding/04_Event-Geometry-and-3D-Vision/01_Survey_Event_3D_Reconstruction_2025.pdf) | [原文](https://arxiv.org/abs/2505.08438) |
| 04-02 | ESVO2: Direct Visual-Inertial Odometry with Stereo Event Cameras | 2025 | IEEE T-RO 2025 | [PDF](./EventCamera-Coding/04_Event-Geometry-and-3D-Vision/02_EventNeRF_2023.pdf) | [原文](https://arxiv.org/abs/2410.09374) |
| 04-03 | EventNeRF: Neural Radiance Fields from a Single Colour Event Camera | 2023 | CVPR 2023（奠基/必读经典） | [PDF](./EventCamera-Coding/04_Event-Geometry-and-3D-Vision/03_ESVO2_2025.pdf) | [原文](https://arxiv.org/abs/2206.11896) |
| 04-04 | EvGGS: A Collaborative Learning Framework for Event-based Generalizable Gaussian Splatting | 2024 | ICML 2024 | [PDF](./EventCamera-Coding/04_Event-Geometry-and-3D-Vision/04_EvGGS_2024.pdf) | [原文](https://arxiv.org/abs/2405.14959) |
| 04-05 | IncEventGS: Pose-Free Gaussian Splatting from a Single Event Camera | 2025 | CVPR 2025 | [PDF](./EventCamera-Coding/04_Event-Geometry-and-3D-Vision/05_IncEventGS_2025.pdf) | [原文](https://arxiv.org/abs/2410.08107) |

## 05 事件视频重建与增强

E2VID 谱系、HDR、去模糊、扩散先验。收录 6 篇。

| 编号 | 标题 | 年份 | 出处 | PDF | 原文链接 |
| --- | --- | --- | --- | --- | --- |
| 05-01 | From Events to Enhancement: A Survey on Event-Based Imaging Technologies | 2025 | arXiv 2025（预印本/待发表） | [PDF](./EventCamera-Coding/05_Event-Video-Reconstruction-and-Enhancement/01_From_Events_to_Enhancement_Survey_2025.pdf) | [原文](https://arxiv.org/abs/2505.05488) |
| 05-02 | Events-to-Video: Bringing Modern Computer Vision to Event Cameras | 2019 | CVPR 2019（奠基/必读经典） | [PDF](./EventCamera-Coding/05_Event-Video-Reconstruction-and-Enhancement/02_Events_to_Video_E2VID_2019.pdf) | [原文](https://arxiv.org/abs/1904.08298) |
| 05-03 | EventHDR: from Event to High-Speed HDR Videos and Beyond | 2024 | TPAMI 2024 | [PDF](./EventCamera-Coding/05_Event-Video-Reconstruction-and-Enhancement/03_EventHDR_2024.pdf) | [原文](https://arxiv.org/abs/2409.17029) |
| 05-04 | Event-Based Fusion for Motion Deblurring with Cross-modal Attention | 2022 | ECCV 2022（oral，必读经典） | [PDF](./EventCamera-Coding/05_Event-Video-Reconstruction-and-Enhancement/04_Event_Fusion_Motion_Deblur_2022.pdf) | [原文](https://arxiv.org/abs/2112.00167) |
| 05-05 | E2VIDiff: Perceptual Events-to-Video Reconstruction using Diffusion Priors | 2024 | arXiv 2024（预印本/待发表） | [PDF](./EventCamera-Coding/05_Event-Video-Reconstruction-and-Enhancement/05_E2VIDiff_2024.pdf) | [原文](https://arxiv.org/abs/2407.08231) |
| 05-06 | LaSe-E2V: Towards Language-guided Semantic-aware Event-to-Video Reconstruction | 2024 | NeurIPS 2024 | [PDF](./EventCamera-Coding/05_Event-Video-Reconstruction-and-Enhancement/06_LaSe_E2V_2024.pdf) | [原文](https://arxiv.org/abs/2407.05547) |

## 06 事件语义理解

检测、开放世界识别、开放词汇分割。收录 6 篇。

| 编号 | 标题 | 年份 | 出处 | PDF | 原文链接 |
| --- | --- | --- | --- | --- | --- |
| 06-01 | Recurrent Vision Transformers for Object Detection with Event Cameras | 2023 | CVPR 2023（奠基/必读经典） | [PDF](./EventCamera-Coding/06_Event-Semantic-Understanding/01_RVT_Recurrent_Vision_Transformers_2023.pdf) | [原文](https://arxiv.org/abs/2212.05598) |
| 06-02 | EventDance: Unsupervised Source-free Cross-modal Adaptation for Event-based Object Recognition | 2024 | CVPR 2024 | [PDF](./EventCamera-Coding/06_Event-Semantic-Understanding/02_EventDance_2024.pdf) | [原文](https://arxiv.org/abs/2403.14082) |
| 06-03 | EventBind: Learning a Unified Representation to Bind Them All for Event-based Open-world Understanding | 2024 | ECCV 2024 | [PDF](./EventCamera-Coding/06_Event-Semantic-Understanding/03_EventBind_2024.pdf) | [原文](https://arxiv.org/abs/2308.03135) |
| 06-04 | Segment Any Events via Weighted Adaptation of Pivotal Tokens | 2024 | TPAMI 2024 | [PDF](./EventCamera-Coding/06_Event-Semantic-Understanding/04_Segment_Any_Events_2024.pdf) | [原文](https://arxiv.org/abs/2312.16222) |
| 06-05 | OVOSE: Open-Vocabulary Semantic Segmentation in Event-Based Cameras | 2024 | ICPR 2024 | [PDF](./EventCamera-Coding/06_Event-Semantic-Understanding/05_TESPEC_2025.pdf) | [原文](https://arxiv.org/abs/2408.09424) |
| 06-06 | TESPEC: Temporally-Enhanced Self-Supervised Pretraining for Event Cameras | 2025 | ICCV 2025 | [PDF](./EventCamera-Coding/06_Event-Semantic-Understanding/06_OVOSE_2024.pdf) | [原文](https://arxiv.org/abs/2508.00913) |

## 07 事件编码与脉冲神经网络

频率×时间编码、SNN 表示与检测。收录 8 篇。

| 编号 | 标题 | 年份 | 出处 | PDF | 原文链接 |
| --- | --- | --- | --- | --- | --- |
| 07-01 | High-performance deep spiking neural networks with 0.3 spikes per neuron | 2024 | Nature Communications 2024 | [PDF](./EventCamera-Coding/07_Event-Coding-and-Spiking-Neural-Networks/01_TTFS_SNN_03_Spikes_2024.pdf) | [原文](https://www.nature.com/articles/s41467-024-51110-5) |
| 07-02 | Spike-TBR: a Noise Resilient Neuromorphic Event Representation | 2025 | arXiv 2025（预印本/待发表） | [PDF](./EventCamera-Coding/07_Event-Coding-and-Spiking-Neural-Networks/02_Spike_TBR_Event_Representation_2025.pdf) | [原文](https://arxiv.org/abs/2506.04817) |
| 07-03 | EAS-SNN: End-to-End Adaptive Sampling and Representation for Event-based Detection with Recurrent Spiking Neural Networks | 2024 | ECCV 2024 | [PDF](./EventCamera-Coding/07_Event-Coding-and-Spiking-Neural-Networks/03_EAS_SNN_Event_Detection_2024.pdf) | [原文](https://arxiv.org/abs/2403.12574) |
| 07-04 | CREST: An Efficient Conjointly-trained Spike-driven Framework for Event-based Object Detection Exploiting Spatiotemporal Dynamics | 2025 | AAAI 2025 | [PDF](./EventCamera-Coding/07_Event-Coding-and-Spiking-Neural-Networks/04_CREST_Spike_Driven_Detection_2025.pdf) | [原文](https://arxiv.org/abs/2412.12525) |
| 07-05 | SpiLiFormer: Enhancing Spiking Transformers with Lateral Inhibition | 2025 | ICCV 2025 | [PDF](./EventCamera-Coding/07_Event-Coding-and-Spiking-Neural-Networks/05_SpiLiFormer_Lateral_Inhibition_2025.pdf) | [原文](https://arxiv.org/abs/2503.15986) |
| 07-06 | Converting High-Performance and Low-Latency SNNs through Explicit Modelling of Residual Error in ANNs | 2025 | TNNLS 2025 | [PDF](./EventCamera-Coding/07_Event-Coding-and-Spiking-Neural-Networks/06_ANN2SNN_Residual_Error_2025.pdf) | [原文](https://arxiv.org/abs/2404.17456) |
| 07-07 | Adaptive Fission: Post-training Encoding for Low-latency Spike Neural Networks | 2025 | NeurIPS 2025 | 仅链接 | [原文](https://openreview.net/forum?id=2zZzdAMyYi) |
| 07-08 | HetSyn: Versatile Timescale Integration in Spiking Neural Networks via Heterogeneous Synapses | 2025 | arXiv 2025（预印本/待发表） | [PDF](./EventCamera-Coding/07_Event-Coding-and-Spiking-Neural-Networks/08_HetSyn_Heterogeneous_Synapses_2025.pdf) | [原文](https://arxiv.org/abs/2508.11644) |

## 08 典型应用（选学）

驾驶、眼动、四足机器人、乒乓机器人。收录 5 篇。

| 编号 | 标题 | 年份 | 出处 | PDF | 原文链接 |
| --- | --- | --- | --- | --- | --- |
| 08-01 | DSEC: A Stereo Event Camera Dataset for Driving Scenarios | 2021 | RA-L 2021（奠基/必读经典） | [PDF](./EventCamera-Coding/08_Selected-Applications/01_DSEC_Stereo_Driving_2021.pdf) | [原文](https://arxiv.org/abs/2103.06011) |
| 08-02 | Event-Based Eye Tracking. AIS 2024 Challenge Survey | 2024 | arXiv 2024（预印本/AIS 2024 挑战赛综述） | [PDF](./EventCamera-Coding/08_Selected-Applications/02_AIS2024_Eye_Tracking_Survey_2024.pdf) | [原文](https://arxiv.org/abs/2404.11770) |
| 08-03 | Event-based Agile Object Catching with a Quadrupedal Robot | 2023 | ICRA 2023（奠基/必读经典） | [PDF](./EventCamera-Coding/08_Selected-Applications/03_Quadruped_Agile_Catching_2023.pdf) | [原文](https://arxiv.org/abs/2303.17479) |
| 08-04 | FACET: Fast and Accurate Event-Based Eye Tracking Using Ellipse Modeling for Extended Reality | 2024 | arXiv 2024（预印本） | [PDF](./EventCamera-Coding/08_Selected-Applications/04_FACET_XR_Eye_Tracking_2024.pdf) | [原文](https://arxiv.org/abs/2409.15584) |
| 08-05 | An Event-Based Perception Pipeline for a Table Tennis Robot | 2025 | arXiv 2025（预印本/投稿 IEEE 中） | [PDF](./EventCamera-Coding/08_Selected-Applications/05_Table_Tennis_Robot_Pipeline_2025.pdf) | [原文](https://arxiv.org/abs/2502.00749) |

---

仓库根目录的 `event_denoising/` 为原有去噪专题（16 篇），未改动。