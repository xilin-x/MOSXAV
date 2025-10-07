# MOSXAV: A Benchmark Dataset for Multi-Object Segmentation in X-ray Angiography Videos

<a href="https://xilin-x.github.io/MOSXAV/" target="_blank"><img alt="Static Badge" src="https://img.shields.io/badge/Homepage-MOSXAV-yellow?logo=databricks&logoColor=%23FF3621"></a> <a href="https://link.springer.com/chapter/10.1007/978-3-032-05472-2_2" target="_blank"><img alt="Static Badge" src="https://img.shields.io/badge/SN-DGM4MICCAI 2025-f8f8f8?style=flat&labelColor=01324b"></a> <a href="https://arxiv.org/abs/2507.16429" target="_blank"><img src="https://img.shields.io/badge/arXiv-2507.16429-b31b1b?style=flat&logo=arXiv&logoColor=%23B31B1B"></a>

## 1. Overview

**MOSXAV** is a benchmark dataset designed for **multi-object segmentation** in X-ray angiography videos. It provides **high-quality, manually annotated segmentation ground truth**, supporting the analysis of vascular structures in dynamic medical imaging. Each video contains **33$\sim$70** frames at a resolution of **512$\times$512 pixels**. Vascular regions are annotated by experienced radiologists, with annotations focused on **one or two key frames** where the contrast agent is most prominent.

- The **training and validation sets** include **30 sequences** (2,335 frames), with **annotations every 5 frames**.
- The **test set** consists of **12 sequences** (488 frames), with **frame-level annotations** throughout.

MOSXAV provides a valuable resource for the development and benchmarking of methods in X-ray angiography video segmentation.

File Structure

## 2. Download

[[GoogleDrive]]() [[OneDrive]]() [[BaiduPan]]()

## 3. License

The dataset is licensed under a [Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License](https://creativecommons.org/licenses/by-nc-sa/4.0/). See [LICENSE](./LICENSE) for details.

<a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-nc-sa/4.0/88x31.png" /></a>

## Citation

Please consider to cite MOSXAV if it helps your research.

```text
@InProceedings{10.1007/978-3-032-05472-2_2,
    author={Xi, Lin and Ma, Yingliang and Wang, Cheng and Howell, Sandra and Rinaldi, Aldo and Rhode, Kawal S.},
    title={Robust Noisy Pseudo-Label Learning for Semi-supervised Medical Image Segmentation Using Diffusion Model},
    booktitle={Deep Generative Models Workshop, International Conference on Medical Image Computing and Computer-Assisted Intervention (DGM4MICCAI)},
    year={2026},
    pages={12--23}
}
```