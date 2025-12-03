# Image Harmonization Papers and Resources

A curated collection of research papers, datasets, and resources related to Image Harmonization.

## Table of Contents

- [Introduction](#introduction)
- [Survey Papers](#survey-papers)
- [Deep Learning Methods](#deep-learning-methods)
  - [Early Works](#early-works)
  - [Attention-based Methods](#attention-based-methods)
  - [Transformer-based Methods](#transformer-based-methods)
  - [GAN-based Methods](#gan-based-methods)
  - [Diffusion-based Methods](#diffusion-based-methods)
- [Traditional Methods](#traditional-methods)
- [Datasets](#datasets)
- [Evaluation Metrics](#evaluation-metrics)
- [Applications](#applications)
- [Code Repositories](#code-repositories)

## Introduction

Image harmonization is a fundamental task in computer vision that aims to adjust the appearance of a composite image to make it look visually realistic. Given a composite image consisting of foreground object(s) from one image and background from another, image harmonization adjusts the foreground to make it compatible with the background in terms of color, illumination, and style.

## Survey Papers

### 2023
- **Image Harmonization: A Survey** | [[Paper]](https://arxiv.org/abs/2303.00556)
  - Authors: Jiahui Huang, et al.
  - Comprehensive survey covering methods from traditional to deep learning approaches

## Deep Learning Methods

### Early Works

- **DoveNet: Deep Image Harmonization via Domain Verification** (CVPR 2020) | [[Paper]](https://arxiv.org/abs/1911.13239) | [[Code]](https://github.com/bcmi/Image-Harmonization-Dataset-iHarmony4)
  - Authors: Wenyan Cong, Jianfu Zhang, Li Niu, Liu Liu, Zhixin Ling, Weiyuan Li, Liqing Zhang
  - First large-scale dataset (iHarmony4) and deep learning method for image harmonization

- **Deep Image Harmonization** (CVPR 2017) | [[Paper]](https://arxiv.org/abs/1703.00069)
  - Authors: Yi-Hsuan Tsai, Xiaohui Shen, Zhe Lin, Kalyan Sunkavalli, Xin Lu, Ming-Hsuan Yang
  - Pioneer work introducing deep learning to image harmonization

### Attention-based Methods

- **SSH: A Self-Supervised Framework for Image Harmonization** (ICCV 2021) | [[Paper]](https://arxiv.org/abs/2108.06805) | [[Code]](https://github.com/VITA-Group/SSHarmonization)
  - Authors: Yifan Jiang, He Zhang, Jianming Zhang, Yilin Wang, Zhe Lin, Kalyan Sunkavalli, Simon Chen, Sohrab Amirghodsi, Sarah Kong, Zhangyang Wang
  - Self-supervised learning approach for image harmonization

- **RainNet: A Large-Scale Dataset for Spatial Precipitation Downscaling** (ICCV 2021) | [[Paper]](https://arxiv.org/abs/2012.09700)
  - Region-aware adaptive instance normalization for image harmonization

### Transformer-based Methods

- **SCS-Co: Self-Consistent Style Contrastive Learning for Image Harmonization** (CVPR 2022) | [[Paper]](https://arxiv.org/abs/2204.13962) | [[Code]](https://github.com/YCHang686/SCS-Co-CVPR2022)
  - Authors: Yucheng Hang, Bin Xia, Wenming Yang, Qingmin Liao
  - Contrastive learning approach with style consistency

- **PCT-Net: Full Resolution Image Harmonization** (CVPR 2023) | [[Paper]](https://arxiv.org/abs/2305.10337)
  - Authors: Zhanghan Ke, Chunyi Sun, Lei Zhu, Ke Xu, Rynson W.H. Lau
  - Transformer-based method for full resolution harmonization

- **SycoNet: Image Harmonization with Soft-Clipped Joint Bilateral Upsampler** (CVPR 2023)
  - Synergistic color harmonization network

### GAN-based Methods

- **Harmonizer: Learning to Perform White-Box Image and Video Harmonization** (ECCV 2022) | [[Paper]](https://arxiv.org/abs/2207.01322) | [[Code]](https://github.com/ZHKKKe/Harmonizer)
  - Authors: Zhanghan Ke, Chunyi Sun, Lei Zhu, Ke Xu, Rynson W.H. Lau
  - White-box approach with interpretable harmonization process

- **Deep Image Harmonization with Globally Guided Feature Transformation** (WACV 2022)
  - Global feature transformation for better harmonization

### Diffusion-based Methods

- **Diffusion-based Image Harmonization** (2023) | [[Paper]](https://arxiv.org/abs/2303.01681)
  - Leveraging diffusion models for image harmonization

- **PDH: Probabilistic Diffusion for Image Harmonization** (2023)
  - Probabilistic approach using diffusion models

## Traditional Methods

- **Poisson Image Editing** (SIGGRAPH 2003) | [[Paper]](https://www.cs.jhu.edu/~misha/Fall07/Papers/Perez03.pdf)
  - Authors: Patrick Pérez, Michel Gangnet, Andrew Blake
  - Classic gradient-domain method for seamless cloning

- **Lalonde and Efros: Using Color Compatibility for Assessing Image Realism** (ICCV 2007)
  - Color transfer and compatibility assessment

- **Multi-scale Image Harmonization** (CVPR 2010)
  - Multi-scale approach for traditional harmonization

## Datasets

### iHarmony4 Dataset
- **DoveNet Paper** (CVPR 2020) | [[Dataset]](https://github.com/bcmi/Image-Harmonization-Dataset-iHarmony4)
- Contains 73,146 pairs of composite and real images
- Four sub-datasets:
  - HCOCO: 38,545 pairs
  - HAdobe5k: 19,437 pairs
  - HFlickr: 10,398 pairs
  - Hday2night: 4,766 pairs

### Real-world Datasets
- **RealHM Dataset** | [[Link]](https://github.com/bcmi/Image-Harmonization-Dataset-RealHM)
  - Real-world image harmonization dataset

### Synthetic Datasets
- **ccHarmony Dataset** (ICCV 2021)
  - Large-scale synthetic dataset for self-supervised learning

## Evaluation Metrics

### Standard Metrics
- **MSE (Mean Squared Error)**: Measures pixel-level difference
- **PSNR (Peak Signal-to-Noise Ratio)**: Quality metric in dB
- **SSIM (Structural Similarity Index)**: Perceptual quality metric
- **fMSE (foreground MSE)**: MSE computed only on foreground region

### Perceptual Metrics
- **LPIPS (Learned Perceptual Image Patch Similarity)**: Deep feature-based perceptual metric
- **FID (Fréchet Inception Distance)**: Distribution-based quality metric

## Applications

### Image Editing and Composition
- Object insertion and removal
- Image blending and compositing
- Virtual photography

### Augmented Reality
- AR object placement
- Virtual try-on
- Mixed reality applications

### Content Creation
- Movie production and VFX
- Advertising and marketing
- Game development

### Photo Editing
- Professional photo retouching
- Social media filters
- Real estate photography

## Code Repositories

### Comprehensive Implementations
- **Image-Harmonization-Dataset-iHarmony4** | [[GitHub]](https://github.com/bcmi/Image-Harmonization-Dataset-iHarmony4)
  - Official implementation of DoveNet with iHarmony4 dataset
  - Baseline implementations of multiple methods

- **Awesome-Image-Harmonization** | [[GitHub]](https://github.com/bcmi/Awesome-Image-Harmonization)
  - Curated list of image harmonization papers and resources

### Individual Method Implementations
- **SSH (Self-Supervised Harmonization)** | [[GitHub]](https://github.com/VITA-Group/SSHarmonization)
- **SCS-Co** | [[GitHub]](https://github.com/YCHang686/SCS-Co-CVPR2022)
- **Harmonizer** | [[GitHub]](https://github.com/ZHKKKe/Harmonizer)

### Toolkits and Libraries
- **libcom** | [[GitHub]](https://github.com/bcmi/libcom)
  - Open-source library for image composition and harmonization
  - Includes multiple state-of-the-art methods

## Contributing

Contributions are welcome! Please feel free to submit a pull request to add new papers, datasets, or resources related to image harmonization.

## Citation

If you find this collection useful for your research, please consider citing the relevant papers mentioned above.

## License

This is a collection of publicly available research papers and resources. Please refer to individual papers and repositories for their respective licenses.

---

Last updated: December 2025