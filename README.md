# Awesome-TTT-in-Vision [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/Jasloft/Awesome-TTT-in-Vision)

A curated list of papers and resources on **Test-Time Training (TTT) in Computer Vision**.

Test-Time Training has recently attracted increasing attention in vision, including visual backbones, image restoration, image segmentation, video generation, medical imaging, vision-language models, and 3D vision. This repository aims to collect representative papers, code, and related resources in this emerging direction.

Contributions are welcome. Please feel free to open an issue or pull request if you find missing papers or useful resources.

TTT Layers: [![Star](https://img.shields.io/github/stars/test-time-training/ttt-lm-pytorch.svg?style=social\&label=Star)](https://github.com/test-time-training/ttt-lm-pytorch)[![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2407.04620)

ViT³: [![Star](https://img.shields.io/github/stars/LeapLabTHU/ViTTT.svg?style=social\&label=Star)](https://github.com/LeapLabTHU/ViTTT)[![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2512.01643)

Vision-TTT: [![Star](https://img.shields.io/github/stars/imKQv/Vittt.svg?style=social\&label=Star)](https://github.com/imKQv/Vittt)[![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2603.00518)

TTT Ecosystem: https://test-time-training.github.io/

## Table of Contents

* [Foundations](#foundations)
* [Vision Backbone](#vision-backbone)
* [Image Restoration](#image-restoration)
* [Image Segmentation](#image-segmentation)
* [Video Generation](#video-generation)
* [Video Understanding](#video-understanding)
* [Vision-Language Model](#vision-language-model)
* [Medical Vision](#medical-vision)
* [3D Vision and Reconstruction](#3d-vision-and-reconstruction)
* [Survey and Awesome Lists](#survey-and-awesome-lists)

### Foundations

| Title                                                                                 | Code                                                                                                                                                                | Link                                                                                                                                                           |
| :------------------------------------------------------------------------------------ | :------------------------------------------------------------------------------------------------------------------------------------------------------------------ | -------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Test-Time Training with Self-Supervision for Generalization under Distribution Shifts | N/A                                                                                                                                                                 | [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/1909.13231)                                                                    |
| TTT++: When Does Self-Supervised Test-Time Training Fail or Thrive?                   | N/A                                                                                                                                                                 | [![PDF](https://img.shields.io/badge/PDF-NeurIPS-blue)](https://proceedings.neurips.cc/paper_files/paper/2021/file/b618c3210e934362ac261db280128c22-Paper.pdf) |
| Learning to (Learn at Test Time): RNNs with Expressive Hidden States                  | [![Star](https://img.shields.io/github/stars/test-time-training/ttt-lm-pytorch.svg?style=social\&label=Star)](https://github.com/test-time-training/ttt-lm-pytorch) | [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2407.04620)                                                                    |
| Test-Time Training Done Right                                                         | N/A                                                                                                                                                                 | [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2505.23884)                                                                    |

### Vision Backbone

| Title                                                                                       | Code                                                                                                                              | Link                                                                                        |
| :------------------------------------------------------------------------------------------ | :-------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------- |
| ViT³: Unlocking Test-Time Training in Vision                                                | [![Star](https://img.shields.io/github/stars/LeapLabTHU/ViTTT.svg?style=social\&label=Star)](https://github.com/LeapLabTHU/ViTTT) | [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2512.01643) |
| Vision-TTT: Efficient and Expressive Visual Representation Learning with Test-Time Training | [![Star](https://img.shields.io/github/stars/imKQv/Vittt.svg?style=social\&label=Star)](https://github.com/imKQv/Vittt)           | [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2603.00518) |
| AU-TTT: Vision Test-Time Training model for Facial Action Unit Detection                    | N/A                                                                                                                               | [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2503.23450) |

### Image Restoration

| Title                                                                                    | Code                                                                                                                                        | Link                                                                                                                                                                                                  |
| :--------------------------------------------------------------------------------------- | :------------------------------------------------------------------------------------------------------------------------------------------ | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| TTT-MIM: Test-Time Training with Masked Image Modeling for Denoising Distribution Shifts | [![Star](https://img.shields.io/github/stars/MLI-lab/TTT_Denoising.svg?style=social\&label=Star)](https://github.com/MLI-lab/TTT_Denoising) | [![PDF](https://img.shields.io/badge/PDF-ECCV-blue)](https://www.ecva.net/papers/eccv_2024/papers_ECCV/papers/01921.pdf)                                                                              |
| Towards Multi-Domain Single Image Dehazing via Test-Time Training                        | N/A                                                                                                                                         | [![PDF](https://img.shields.io/badge/PDF-CVPR-blue)](https://openaccess.thecvf.com/content/CVPR2022/papers/Liu_Towards_Multi-Domain_Single_Image_Dehazing_via_Test-Time_Training_CVPR_2022_paper.pdf) |

### Image Segmentation

| Title                                                                                                                       | Code                                                                                                                                  | Link                                                                                        |
| :-------------------------------------------------------------------------------------------------------------------------- | :------------------------------------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------- |
| SAM-TTT: Segment Anything Model via Reverse Parameter Configuration and Test-Time Training for Camouflaged Object Detection | [![Star](https://img.shields.io/github/stars/guobaoxiao/SAM-TTT.svg?style=social\&label=Star)](https://github.com/guobaoxiao/SAM-TTT) | [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2509.11884) |
| Depth-aware Test-Time Training for Zero-shot Video Object Segmentation                                                      | [![Star](https://img.shields.io/github/stars/NiFangBaAGe/DATTT.svg?style=social\&label=Star)](https://github.com/NiFangBaAGe/DATTT)   | [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2403.04258) |

### Video Generation

| Title                                                                               | Code                                                                                                                                                              | Link                                                                                        |
| :---------------------------------------------------------------------------------- | :---------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------- |
| One-Minute Video Generation with Test-Time Training                                 | [![Star](https://img.shields.io/github/stars/test-time-training/ttt-video-dit.svg?style=social\&label=Star)](https://github.com/test-time-training/ttt-video-dit) | [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2504.05298) |
| CustomTTT: Motion and Appearance Customized Video Generation via Test-Time Training | [![Star](https://img.shields.io/github/stars/rongpiking/customttt.svg?style=social\&label=Star)](https://github.com/rongpiking/customttt)                         | [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2412.15646) |

### Video Understanding

| Title                                                                            | Code                                                                                                                                | Link                                                                                        |
| :------------------------------------------------------------------------------- | :---------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------- |
| Depth-aware Test-Time Training for Zero-shot Video Object Segmentation           | [![Star](https://img.shields.io/github/stars/NiFangBaAGe/DATTT.svg?style=social\&label=Star)](https://github.com/NiFangBaAGe/DATTT) | [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2403.04258) |
| Spatial-TTT: Streaming Visual-based Spatial Intelligence with Test-Time Training | N/A                                                                                                                                 | [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2603.12255) |

### Vision-Language Model

| Title                                                                                                            | Code                                                                                                                                                                                      | Link                                                                                                                                                                                                                        |
| :--------------------------------------------------------------------------------------------------------------- | :---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| LoRA-TTT: Low-Rank Test-Time Training for Vision-Language Models                                                 | N/A                                                                                                                                                                                       | [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2502.02069)                                                                                                                                 |
| Test-Time Low Rank Adaptation via Confidence Maximization for Zero-Shot Generalization of Vision-Language Models | [![Star](https://img.shields.io/github/stars/Razaimam45/TTL-Test-Time-Low-Rank-Adaptation.svg?style=social\&label=Star)](https://github.com/Razaimam45/TTL-Test-Time-Low-Rank-Adaptation) | [![PDF](https://img.shields.io/badge/PDF-WACV-blue)](https://openaccess.thecvf.com/content/WACV2025/papers/Imam_Test-Time_Low_Rank_Adaptation_via_Confidence_Maximization_for_Zero-Shot_Generalization_WACV_2025_paper.pdf) |

### Medical Vision

| Title                                                                                      | Code                                                                                                                                          | Link                                                                                        |
| :----------------------------------------------------------------------------------------- | :-------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------- |
| Med-TTT: Vision Test-Time Training model for Medical Image Segmentation                    | [![Star](https://img.shields.io/github/stars/Jiashu-Xu/Med-TTT.svg?style=social\&label=Star)](https://github.com/Jiashu-Xu/Med-TTT)           | [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2410.02523) |
| TTT-Unet: Enhancing U-Net with Test-Time Training Layers for Biomedical Image Segmentation | [![Star](https://img.shields.io/github/stars/rongzhou7/TTT-Unet.svg?style=social\&label=Star)](https://github.com/rongzhou7/TTT-Unet)         | [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2409.11299) |
| Test Time Training for 4D Medical Image Interpolation                                      | [![Star](https://img.shields.io/github/stars/ChaosTheProducer/TTT4D.svg?style=social\&label=Star)](https://github.com/ChaosTheProducer/TTT4D) | [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2502.02341) |

### 3D Vision and Reconstruction

| Title                                                                            | Code | Link                                                                                        |
| :------------------------------------------------------------------------------- | :--- | ------------------------------------------------------------------------------------------- |
| Spatial-TTT: Streaming Visual-based Spatial Intelligence with Test-Time Training | N/A  | [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2603.12255) |
| tttLRM: Test-Time Training for Long Context and Autoregressive 3D Reconstruction | N/A  | [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2602.20160) |

### Survey and Awesome Lists

| Title                                       | Code                                                                                                                                                                                                      | Link                                                                            |
| :------------------------------------------ | :-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------- |
| Awesome Test-Time Adaptation                | [![Star](https://img.shields.io/github/stars/tim-learn/awesome-test-time-adaptation.svg?style=social\&label=Star)](https://github.com/tim-learn/awesome-test-time-adaptation)                             | [LINK](https://github.com/tim-learn/awesome-test-time-adaptation)               |
| Beyond Model Adaptation at Test Time Papers | [![Star](https://img.shields.io/github/stars/zzzx1224/Beyond-model-adaptation-at-test-time-Papers.svg?style=social\&label=Star)](https://github.com/zzzx1224/Beyond-model-adaptation-at-test-time-Papers) | [LINK](https://github.com/zzzx1224/Beyond-model-adaptation-at-test-time-Papers) |
| Test-Time Training Project Website          | N/A                                                                                                                                                                                                       | [LINK](https://test-time-training.github.io/)                                   |

## Contributing

If you find any missing papers, code repositories, or useful resources, please feel free to open an issue or submit a pull request.

## Acknowledgement

This repository is inspired by community-maintained awesome lists, especially Awesome-RWKV-in-Vision.
