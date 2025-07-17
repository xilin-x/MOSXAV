# MOSXAV: A Benchmark Dataset for Multi-Object Segmentation in X-ray Angiography Videos

**[[Homepage]]()**  **[[arXiv]]()**

## 1. Overview

**MOSXAV** is a benchmark dataset designed for **multi-object segmentation** in X-ray angiography videos. It provides **high-quality, manually annotated segmentation ground truth**, supporting the analysis of vascular structures in dynamic medical imaging. Each video contains **33$\sim$70** frames at a resolution of **512$\times$512 pixels**. Vascular regions are annotated by experienced radiologists, with annotations focused on **one or two key frames** where the contrast agent is most prominent.

- The **training and validation sets** include **50 sequences** (2,335 frames), with **annotations every 5 frames**.
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
@inproceedings{MOSE,
  title={{MOSE}: A New Dataset for Video Object Segmentation in Complex Scenes},
  author={Ding, Henghui and Liu, Chang and He, Shuting and Jiang, Xudong and Torr, Philip HS and Bai, Song},
  booktitle={ICCV},
  year={2023}
}
```