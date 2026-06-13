# Awesome-TTT-in-Vision [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/Jasloft/Awesome-TTT-in-Vision)

A curated list of papers and resources on **Test-Time Training (TTT) in Computer Vision**.

This repository focuses on visual Test-Time Training, especially papers related to **ViT³: Unlocking Test-Time Training in Vision**, visual TTT backbones, and TTT-based applications in image, video, medical vision, and 3D vision.

Contributions are welcome. Please feel free to open an issue or pull request if you find missing papers or useful resources.

ViT³: [![Star](https://img.shields.io/github/stars/LeapLabTHU/ViTTT.svg?style=social\&label=Star)](https://github.com/LeapLabTHU/ViTTT) [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2512.01643)

TTT Layers: [![Star](https://img.shields.io/github/stars/test-time-training/ttt-lm-pytorch.svg?style=social\&label=Star)](https://github.com/test-time-training/ttt-lm-pytorch) [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2407.04620)

## Table of Contents

* [Core Paper](#core-paper)
* [Papers Citing ViT³](#papers-citing-vit³)
* [Related TTT in Vision](#related-ttt-in-vision)

  * [Vision Backbone](#vision-backbone)
  * [Image Restoration](#image-restoration)
  * [Image Segmentation](#image-segmentation)
  * [Video Generation and Understanding](#video-generation-and-understanding)
  * [Medical Vision](#medical-vision)
  * [3D Vision and Reconstruction](#3d-vision-and-reconstruction)
  * [Vision-Language and Spatial Intelligence](#vision-language-and-spatial-intelligence)
* [Foundations](#foundations)
* [Related Awesome Lists](#related-awesome-lists)

## Core Paper

| Title                                        | Venue / Year   | Code                                                                                                                              | Link                                                                                        |
| :------------------------------------------- | :------------- | :-------------------------------------------------------------------------------------------------------------------------------- | :------------------------------------------------------------------------------------------ |
| ViT³: Unlocking Test-Time Training in Vision | CVPR 2026 Oral | [![Star](https://img.shields.io/github/stars/LeapLabTHU/ViTTT.svg?style=social\&label=Star)](https://github.com/LeapLabTHU/ViTTT) | [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2512.01643) |

## Papers Citing ViT³

> This section collects papers that cite or closely follow **ViT³: Unlocking Test-Time Training in Vision**. The list is based on Google Scholar citation results and will be updated regularly.

| Title                                                                                       | Area                          | Venue / Year | Code                                                              | Link                                                                                        |
| :------------------------------------------------------------------------------------------ | :---------------------------- | :----------- | :---------------------------------------------------------------- | :------------------------------------------------------------------------------------------ |
| VGG-T³: Offline Feed-Forward 3D Reconstruction at Scale                                     | 3D Reconstruction             | CVPR 2026    | [Project](https://research.nvidia.com/labs/dvl/projects/vgg-ttt/) | [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2602.23361) |
| Test-Time Training with KV Binding Is Secretly Linear Attention                             | TTT Theory / Linear Attention | arXiv 2026   | [Project](https://research.nvidia.com/labs/sil/projects/tttla/)   | [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2602.21204) |
| Vision-TTT: Efficient and Expressive Visual Representation Learning with Test-Time Training | Vision Backbone               | arXiv 2026   | N/A                                                               | [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2603.00518) |
| MiTA Attention: Efficient Fast-Weight Scaling via a Mixture of Top-k Activations            | Efficient Attention / Vision  | arXiv 2026   | N/A                                                               | [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2602.01219) |
| U-TTT: Towards Generalizable PET Image Denoising via Test-Time Training                     | Medical Image Restoration     | arXiv 2026   | [Code](https://github.com/Yaziwel/U-TTT)                          | [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2606.11032) |

## Related TTT in Vision

### Vision Backbone

| Title                                                                                       | Venue / Year   | Code                                                                                                                              | Link                                                                                        |
| :------------------------------------------------------------------------------------------ | :------------- | :-------------------------------------------------------------------------------------------------------------------------------- | :------------------------------------------------------------------------------------------ |
| ViT³: Unlocking Test-Time Training in Vision                                                | CVPR 2026 Oral | [![Star](https://img.shields.io/github/stars/LeapLabTHU/ViTTT.svg?style=social\&label=Star)](https://github.com/LeapLabTHU/ViTTT) | [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2512.01643) |
| Vision-TTT: Efficient and Expressive Visual Representation Learning with Test-Time Training | arXiv 2026     | N/A                                                                                                                               | [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2603.00518) |
| AU-TTT: Vision Test-Time Training model for Facial Action Unit Detection                    | ICME 2025      | N/A                                                                                                                               | [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2503.23450) |

### Image Restoration

| Title                                                                                    | Venue / Year | Code                                                                                                                                        | Link                                                                                                                                                                                                  |
| :--------------------------------------------------------------------------------------- | :----------- | :------------------------------------------------------------------------------------------------------------------------------------------ | :---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| TTT-MIM: Test-Time Training with Masked Image Modeling for Denoising Distribution Shifts | ECCV 2024    | [![Star](https://img.shields.io/github/stars/MLI-lab/TTT_Denoising.svg?style=social\&label=Star)](https://github.com/MLI-lab/TTT_Denoising) | [![PDF](https://img.shields.io/badge/PDF-ECCV-blue)](https://www.ecva.net/papers/eccv_2024/papers_ECCV/papers/01921.pdf)                                                                              |
| Towards Multi-Domain Single Image Dehazing via Test-Time Training                        | CVPR 2022    | N/A                                                                                                                                         | [![PDF](https://img.shields.io/badge/PDF-CVPR-blue)](https://openaccess.thecvf.com/content/CVPR2022/papers/Liu_Towards_Multi-Domain_Single_Image_Dehazing_via_Test-Time_Training_CVPR_2022_paper.pdf) |

### Image Segmentation

| Title                                                                                                                       | Venue / Year | Code                                                                                                                                  | Link                                                                                        |
| :-------------------------------------------------------------------------------------------------------------------------- | :----------- | :------------------------------------------------------------------------------------------------------------------------------------ | :------------------------------------------------------------------------------------------ |
| SAM-TTT: Segment Anything Model via Reverse Parameter Configuration and Test-Time Training for Camouflaged Object Detection | arXiv 2025   | [![Star](https://img.shields.io/github/stars/guobaoxiao/SAM-TTT.svg?style=social\&label=Star)](https://github.com/guobaoxiao/SAM-TTT) | [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2509.11884) |
| Depth-aware Test-Time Training for Zero-shot Video Object Segmentation                                                      | CVPR 2024    | [![Star](https://img.shields.io/github/stars/NiFangBaAGe/DATTT.svg?style=social\&label=Star)](https://github.com/NiFangBaAGe/DATTT)   | [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2403.04258) |

### Video Generation and Understanding

| Title                                                                               | Venue / Year | Code                                                                                                                                                              | Link                                                                                        |
| :---------------------------------------------------------------------------------- | :----------- | :---------------------------------------------------------------------------------------------------------------------------------------------------------------- | :------------------------------------------------------------------------------------------ |
| One-Minute Video Generation with Test-Time Training                                 | CVPR 2025    | [![Star](https://img.shields.io/github/stars/test-time-training/ttt-video-dit.svg?style=social\&label=Star)](https://github.com/test-time-training/ttt-video-dit) | [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2504.05298) |
| CustomTTT: Motion and Appearance Customized Video Generation via Test-Time Training | AAAI 2025    | [![Star](https://img.shields.io/github/stars/rongpiking/customttt.svg?style=social\&label=Star)](https://github.com/rongpiking/customttt)                         | [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2412.15646) |

### Medical Vision

| Title                                                                                      | Venue / Year | Code                                                                                                                                  | Link                                                                                        |
| :----------------------------------------------------------------------------------------- | :----------- | :------------------------------------------------------------------------------------------------------------------------------------ | :------------------------------------------------------------------------------------------ |
| Med-TTT: Vision Test-Time Training model for Medical Image Segmentation                    | arXiv 2024   | [![Star](https://img.shields.io/github/stars/Jiashu-Xu/Med-TTT.svg?style=social\&label=Star)](https://github.com/Jiashu-Xu/Med-TTT)   | [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2410.02523) |
| TTT-UNet: Enhancing U-Net with Test-Time Training Layers for Biomedical Image Segmentation | arXiv 2024   | [![Star](https://img.shields.io/github/stars/rongzhou7/TTT-Unet.svg?style=social\&label=Star)](https://github.com/rongzhou7/TTT-Unet) | [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2409.11299) |
| U-TTT: Towards Generalizable PET Image Denoising via Test-Time Training                    | arXiv 2026   | [Code](https://github.com/Yaziwel/U-TTT)                                                                                              | [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2606.11032) |

### 3D Vision and Reconstruction

| Title                                                                            | Venue / Year        | Code                                                                                                                                | Link                                                                                        |
| :------------------------------------------------------------------------------- | :------------------ | :---------------------------------------------------------------------------------------------------------------------------------- | :------------------------------------------------------------------------------------------ |
| VGG-T³: Offline Feed-Forward 3D Reconstruction at Scale                          | CVPR 2026           | [Project](https://research.nvidia.com/labs/dvl/projects/vgg-ttt/)                                                                   | [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2602.23361) |
| tttLRM: Test-Time Training for Long Context and Autoregressive 3D Reconstruction | CVPR 2026 Highlight | [![Star](https://img.shields.io/github/stars/cwchenwang/tttLRM.svg?style=social\&label=Star)](https://github.com/cwchenwang/tttLRM) | [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2602.20160) |

### Vision-Language and Spatial Intelligence

| Title                                                                            | Venue / Year | Code                                                                                                                                  | Link                                                                                        |
| :------------------------------------------------------------------------------- | :----------- | :------------------------------------------------------------------------------------------------------------------------------------ | :------------------------------------------------------------------------------------------ |
| Spatial-TTT: Streaming Visual-based Spatial Intelligence with Test-Time Training | arXiv 2026   | [![Star](https://img.shields.io/github/stars/THU-SI/Spatial-TTT.svg?style=social\&label=Star)](https://github.com/THU-SI/Spatial-TTT) | [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2603.12255) |
| LoRA-TTT: Low-Rank Test-Time Training for Vision-Language Models                 | arXiv 2025   | N/A                                                                                                                                   | [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2502.02069) |

## Foundations

| Title                                                                                 | Venue / Year | Code                                                                                                                                                                | Link                                                                                                                                                           |
| :------------------------------------------------------------------------------------ | :----------- | :------------------------------------------------------------------------------------------------------------------------------------------------------------------ | :------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Test-Time Training with Self-Supervision for Generalization under Distribution Shifts | ICML 2020    | N/A                                                                                                                                                                 | [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/1909.13231)                                                                    |
| TTT++: When Does Self-Supervised Test-Time Training Fail or Thrive?                   | NeurIPS 2021 | [![Star](https://img.shields.io/github/stars/vita-epfl/ttt-plus-plus.svg?style=social\&label=Star)](https://github.com/vita-epfl/ttt-plus-plus)                     | [![PDF](https://img.shields.io/badge/PDF-NeurIPS-blue)](https://proceedings.neurips.cc/paper_files/paper/2021/file/b618c3210e934362ac261db280128c22-Paper.pdf) |
| Learning to (Learn at Test Time): RNNs with Expressive Hidden States                  | ICML 2024    | [![Star](https://img.shields.io/github/stars/test-time-training/ttt-lm-pytorch.svg?style=social\&label=Star)](https://github.com/test-time-training/ttt-lm-pytorch) | [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2407.04620)                                                                    |
| Test-Time Training with KV Binding Is Secretly Linear Attention                       | arXiv 2026   | [Project](https://research.nvidia.com/labs/sil/projects/tttla/)                                                                                                     | [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2602.21204)                                                                    |

## Related Awesome Lists

| Title                                       | Link                                                                            |
| :------------------------------------------ | :------------------------------------------------------------------------------ |
| Awesome Test-Time Adaptation                | [LINK](https://github.com/tim-learn/awesome-test-time-adaptation)               |
| Beyond Model Adaptation at Test Time Papers | [LINK](https://github.com/zzzx1224/Beyond-model-adaptation-at-test-time-Papers) |

## Notes

This list is a work in progress.

For the **Papers Citing ViT³** section, papers should be added only when they are verified to cite or closely follow **ViT³: Unlocking Test-Time Training in Vision**.

For the **Related TTT in Vision** section, papers should satisfy at least one of the following conditions:

* The paper explicitly uses Test-Time Training in a visual task.
* The paper uses TTT layers or TTT-style sequence modeling in vision, video, medical imaging, 3D vision, or vision-language tasks.
* The paper provides theoretical or architectural insights that are directly relevant to visual TTT.

## Contributing

If you find missing papers, code repositories, or useful resources, please feel free to open an issue or submit a pull request.

## Acknowledgement

This repository is inspired by community-maintained awesome lists, especially [Awesome-RWKV-in-Vision](https://github.com/Yaziwel/Awesome-RWKV-in-Vision).
