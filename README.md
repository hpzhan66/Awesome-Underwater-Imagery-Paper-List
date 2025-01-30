# Awesome-Underwater-Imagery-Paper-List [![Awesome](https://awesome.re/badge-flat.svg)](https://awesome.re)
A list of papers related to underwater imagery, inspired by [Awesome-3D-AIGC](https://github.com/mdyao/Awesome-3D-AIGC/).

If you want to contribute to this repo, please send a pull request.

Let's explore the mysterious marine world!

## Contents
- [Dataset](#dataset)
- [Survey](#survey)
- [Underwater Optical Image](#underwater-optical-image)
  - [Underwater Optical Image Enhancement](#underwater-optical-image-enhancement)
  - [Underwater Optical Image Super-resolution](#underwater-optical-image-super-resolution)
  - [Underwater Optical Image Object Detection](#underwater-optical-image-object-detection)
  - [Underwater Optical Depth Estimation](#underwater-optical-depth-estimation)
- [Underwater Acoustic Image](#underwater-acoustic-image)
- [Underwater Opti-Acoustic Image](#underwater-opti-acoustic-image)

## Dataset

| Name  | Task | Source |
|:------------------------|:---------------------|:---------------------|
| Underwater Image Enhancement Benchmark  | Underwater Optical Image Enhancement | [UIEB](https://li-chongyi.github.io/proj_benchmark.html) |
| Large-Scale Underwater Image Dataset  | Underwater Optical Image Enhancement | [LSUI](https://lintaopeng.github.io/code/) |
| Enhancing Underwater Visual Perception Dataset  | Underwater Optical Image Enhancement | [EUVP](https://irvlab.cs.umn.edu/resources/euvp-dataset) |
| Realworld Underwater Image Enhancement Benchmark | Underwater Optical Image Enhancement | [RUIE](https://github.com/dlut-dimt/Realworld-Underwater-Image-Enhancement-RUIE-Benchmark) |
| Underwater Video Enhancement Benchmark  | Underwater Video Enhancement | [UVEB](https://github.com/yzbouc/UVEB) |
| The USR-248 Dataset | Underwater Optical Image Super-Resolution | [USR-248](https://irvlab.cs.umn.edu/resources/usr-248-dataset) |
| The UFO-120 Dataset | Simultaneous Enhancement and Super-Resolution | [UFO-120](https://irvlab.cs.umn.edu/resources/ufo-120-dataset) |
| Atlantis Dataset  | Underwater Depth Estimation | [Atlantis](https://www.kaggle.com/datasets/zkawfanx/atlantis/data) |
| URPC2020 Dataset  | Underwater Optical Object Detection | [URPC2020](https://github.com/xiaoDetection/Learning-Heavily-Degraed-Prior) |
| Real-world Underwater Object Detection Dataset | Underwater Optical Object Detection  | [RUOD](https://github.com/dlut-dimt/RUOD) |
| Underwater Object Detection Dataset | Underwater Optical Object Detection | [UODD](https://github.com/LehiChiang/Underwater-object-detection-dataset) |
| Detecting Underwater Objects Dataset | Underwater Object Detection | [DUO](https://github.com/chongweiliu/DUO) |



## Survey
- [Signal Processing: Image Communication 20] Diving deeper into underwater image enhancement: A survey
  
  [📄 Paper](https://www.sciencedirect.com/science/article/abs/pii/S0923596520301478)
  
  TL;DR: A survey on underwater optical image enhancement
  
- [ArXiv 24] A Comprehensive Survey on Underwater Image Enhancement Based on Deep Learning

  [📄 Paper](https://arxiv.org/abs/2405.19684) | [🌐 Project Page](https://github.com/YuZhao1999/UIE)
  
  TL;DR: A survey on deep-learning based underwater optical image enhancement

- [Neurocomputing 23] A systematic review and analysis of deep learning-based underwater object detection

  [📄 Paper](https://www.sciencedirect.com/science/article/abs/pii/S0925231223000656)
  
  TL;DR: An in-depth analysis of underwater object detection, emphasizing its correlation with underwater image enhancement. 
  
- [ArXiv 24] Underwater Object Detection in the Era of Artificial Intelligence: Current, Challenge, and Future

  [📄 Paper](https://arxiv.org/pdf/2410.05577) | [🌐 Project Page](https://github.com/LongChenCV/UODReview)
  
  TL;DR: A comprehensive survey on underwater optical object detection
## Underwater Optical Image

### Underwater Optical Image Enhancement
- [IJCV 24] HCLR-Net: Hybrid Contrastive Learning Regularization with Locally Randomized Perturbation for Underwater Image Enhancement
  
  [📄 Paper](https://link.springer.com/article/10.1007/s11263-024-01987-y) | [💻 Code](https://github.com/zhoujingchun03/HCLR-Net)
  
  TL;DR: HCLR-Net uses hybrid contrastive learning and unpaired data to enhance underwater images, outperforming state-of-the-art methods in quality and generalization.
  
- [CVPR 24] Wavelet-based Fourier Information Interaction with Frequency Diffusion Adjustment for Underwater Image Restoration 
  
  [📄 Paper](https://openaccess.thecvf.com/content/CVPR2024/papers/Zhao_Wavelet-based_Fourier_Information_Interaction_with_Frequency_Diffusion_Adjustment_for_Underwater_CVPR_2024_paper.pdf) | [💻 Code](https://github.com/ChenzhaoNju/WF-Diff)
  
  TL;DR: WF-Diff leverages frequency domain information with a Wavelet-based Fourier information interaction network and Frequency Residual Diffusion Adjustment Module to enhance underwater images, achieving state-of-the-art performance and superior visual quality.

- [ACMMM 23] Underwater Image Enhancement by Transformer-based Diffusion Model with Non-uniform Sampling for Skip Strategy

  [📄 Paper](https://dl.acm.org/doi/10.1145/3581783.3612378) | [💻 Code](https://github.com/piggy2009/DM_underwater) 

  TL;DR: An efficient underwater image enhancement method using a lightweight transformer-based diffusion model with skip and non-uniform sampling strategies, achieving competitive performance and high efficiency.

- [CVPR 23] Contrastive Semi-supervised Learning for Underwater Image Restoration via Reliable Bank
  
  [📄 Paper](https://arxiv.org/pdf/2303.09101.pdf) | [💻 Code](https://github.com/Huang-ShiRui/Semi-UIR) 

  TL;DR: This work presents a semi-supervised underwater image restoration framework using a mean-teacher approach with a reliable output bank and contrastive regularization to address label scarcity, improving performance over state-of-the-art methods.
  
- [TIP 23] U-Shape Transformer for Underwater Image Enhancement
  
  [📄 Paper](https://ieeexplore.ieee.org/document/10129222) | [💻 Code](https://github.com/LintaoPeng/U-shape_Transformer_for_Underwater_Image_Enhancement) 

  TL;DR: This work introduces a large-scale underwater image dataset and a U-shape Transformer network with novel feature fusion and loss functions, achieving state-of-the-art performance in underwater image enhancement.
  
- [AAAI 23] Underwater Ranker: Learn Which Is Better and How to Be Better
  
  [📄 Paper](https://ieeexplore.ieee.org/document/10129222) | [🌐 Project Page](https://li-chongyi.github.io/URanker_files/) | [💻 Code](https://github.com/RQ-Wu/UnderwaterRanker) 

  TL;DR: This paper presents URanker, a ranking-based underwater image quality assessment method using a conv-attentional Transformer, which accurately ranks image quality and improves UIE networks when combined with a pre-trained model.
  
- [ECCV 22] Uncertainty Inspired Underwater Image Enhancement
  
  [📄 Paper](https://arxiv.org/pdf/2207.09689.pdf) | [💻 Code](https://github.com/zhenqifu/PUIE-Net) 

  TL;DR: This paper introduces a probabilistic network for underwater image enhancement that learns enhancement distributions and uses a consensus process to handle reference map ambiguity, achieving competitive performance with state-of-the-art methods.
  
- [RAL 20] Fast Underwater Image Enhancement for Improved Visual Perception
  
  [📄 Paper](https://ieeexplore.ieee.org/document/9001231) | [💻 Code](https://github.com/xahidbuffon/FUnIE-GAN) 

  TL;DR: This paper presents a real-time underwater image enhancement model using a conditional GAN, trained on the EUVP dataset, improving image quality for object detection, human pose estimation, and saliency prediction in underwater robotics.
  
- [TIP 19] An Underwater Image Enhancement Benchmark Dataset and Beyond
  
  [📄 Paper](https://ieeexplore.ieee.org/document/8917818) | [🌐 Project Page](https://li-chongyi.github.io/proj_benchmark.html) | [💻 Code](https://github.com/BIGWangYuDong/UWEnhancement) 

  TL;DR: This paper introduces the Underwater Image Enhancement Benchmark (UIEB) with 950 real-world images and presents Water-Net, a baseline network, to evaluate and highlight the strengths and limitations of current underwater image enhancement algorithms.
  
 
### Underwater Optical Image Super-resolution
- [ICRA 20] Underwater Image Super-Resolution using Deep Residual Multipliers
  
  [📄 Paper](https://ieeexplore.ieee.org/document/9197213) | [💻 Code](https://github.com/xahidbuffon/SRDRM) 

  TL;DR: This paper introduces a deep residual network-based model for underwater single image super-resolution using the USR-248 dataset and adversarial training, achieving competitive performance and practical feasibility for autonomous underwater robots.

- [RSS 20] Underwater Image Super-Resolution using Deep Residual Multipliers
  
  [📄 Paper](http://www.roboticsproceedings.org/rss16/p018.pdf) | [💻 Code](https://github.com/xahidbuffon/Deep_SESR) 

  TL;DR: This paper presents Deep SESR, a residual network-based model for simultaneous enhancement and super-resolution of underwater images, trained on the UFO-120 dataset, achieving superior performance in real-time applications for underwater robots.

### Underwater Optical Image Object Detection

- [AAAI 24] AMSP-UOD: When vortex convolution and stochastic perturbation meet underwater object detection
  
  [📄 Paper](https://ojs.aaai.org/index.php/AAAI/article/view/28599) | [💻 Code](https://github.com/zhoujingchun03/AMSP-UOD) 

  TL;DR: This paper proposes AMSP-UOD, a novel underwater object detection framework employing amplitude-modulated perturbations to disrupt noise, a feature association module for enhanced multi-range feature fusion, and aspect-ratio-optimized NMS post-processing, achieving state-of-the-art accuracy and noise immunity on URPC/RUOD benchmarks.


### Underwater Optical Depth Estimation

- [CVPR 24] Atlantis: Enabling Underwater Depth Estimation with Stable Diffusion
  
  [📄 Paper](https://openaccess.thecvf.com/content/CVPR2024/papers/Zhang_Atlantis_Enabling_Underwater_Depth_Estimation_with_Stable_Diffusion_CVPR_2024_paper.pdf) | [💻 Code](https://github.com/zkawfanx/Atlantis/tree/main) 

  TL;DR: Proposes Depth2Underwater ControlNet + Atlantis dataset using Stable Diffusion to generate photorealistic underwater scenes from terrestrial depth data, enabling supervised training that reduces domain gaps and improves depth estimation performance on underwater images, with applications in image enhancement.
## Underwater Acoustic Image
- [ICRA 23] Neural Implicit Surface Reconstruction using Imaging Sonar
  
  [📄 Paper](https://arxiv.org/abs/2209.08221) | [💻 Code](https://github.com/rpl-cmu/neusis) 

  TL;DR: Proposes a neural implicit surface representation with differentiable acoustic renderer for imaging sonar (FLS) 3D reconstruction, enabling high-fidelity geometry recovery from multi-view sonar data while reducing memory overhead compared to point-cloud/grid methods.

## Underwater Opti-Acoustic Image
- [SIGGRAPH 24] AONeuS: A Neural Rendering Framework for Acoustic-Optical Sensor Fusion
  
  [📄 Paper](https://dl.acm.org/doi/10.1145/3641519.3657446) | [🌐 Project Page](https://aoneus.github.io/) | [💻 Code](https://github.com/kzhang2/aoneus)

  TL;DR: Introduces AONeuS, a physics-based multimodal neural framework merging high-res RGB and low-res sonar data for accurate underwater 3D surface reconstruction under restricted baselines, outperforming RGB/sonar-only methods in simulations and experiments.

- [PAMI 24] Z-Splat: Z-Axis Gaussian Splatting for Camera-Sonar Fusion
  
  [📄 Paper](https://ieeexplore.ieee.org/document/10685550)

  TL;DR: Enhances 3D-Gaussian Splatting by integrating sonar-derived transient data to resolve depth-axis "missing cone" issues in restricted-baseline scenarios (e.g., underwater), achieving +5 dB PSNR in view synthesis and 60% lower geometry errors via RGB-sonar fusion.
  

## More Resources
[Awesome_Underwater_Datasets] (https://github.com/xahidbuffon/Awesome_Underwater_Datasets)

[Awesome-Underwater-Image-Enhancement] (https://github.com/sevenzero70/Awesome-Underwater-Image-Enhancement)

