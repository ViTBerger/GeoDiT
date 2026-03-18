# GeoDiT

[![paper](https://img.shields.io/badge/arXiv-Paper-<COLOR>.svg)](https://arxiv.org/abs/2512.02505)
[![hf_model](https://img.shields.io/badge/🤗-Model-blue.svg)](https://huggingface.co/ViTBerger/GeoDiT)

---

## 📢 Latest Updates
- `2025/03/18`: We released **GeoDiT** checkpoint [huggingface](https://huggingface.co/ViTBerger/GeoDiT). 
- `2026/02/21`:  **GeoDiT** has been accepted by CVPR 2026. 🔥🔥🔥

## TODO
- GeoDiT's training code and test code.

---

## GeoDiT: Overview
Autoregressive models are structurally misaligned with the inherently parallel nature of geospatial understanding, forcing a rigid sequential narrative onto scenes and fundamentally hindering the generation of structured and coherent outputs. We challenge this paradigm by reframing geospatial generation as a parallel refinement process, enabling a holistic, coarse-to-fine synthesis that resolves all semantic elements simultaneously. To operationalize this, we introduce GeoDiT, the first diffusion-based vision-language model tailored for the geospatial domain. Extensive experiments demonstrate that GeoDiT establishes a new state-of-the-art on benchmarks requiring structured, object-centric outputs. It achieves significant gains in image captioning, visual grounding, and multi-object detection, precisely the tasks where autoregressive models falter. Our work validates that aligning the generative process with the data's intrinsic structure is key to unlocking superior performance in complex geospatial analysis.
![Description](figs/abs.png)

## Citation

```bibtex
@misc{liu2025geoditdiffusionbasedvisionlanguagemodel,
      title={GeoDiT: A Diffusion-based Vision-Language Model for Geospatial Understanding}, 
      author={Jiaqi Liu and Ronghao Fu and Haoran Liu and Lang Sun and Bo Yang},
      year={2025},
      eprint={2512.02505},
      archivePrefix={arXiv},
      primaryClass={cs.CV},
      url={https://arxiv.org/abs/2512.02505}, 
}
```

## Acknowledgement

The initial weights of **RSThinker** are initialized from [LLaDA-V](https://github.com/ML-GSAI/LLaDA-V), we sincerely thank their effort for open-sourcing.
