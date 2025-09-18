<div align="center">
  <img src="Pics/ReasoningV-Logo.jpeg" width="200" alt="ReasoningV Logo"> <div>&nbsp;</div>
  <h1>ReasoningV: Efficient Verilog Code Generation with Adaptive Hybrid Reasoning Model</h1>
  <div>&nbsp;</div>

  English | [简体中文](README-CN.md)

  <div>&nbsp;</div>

  [🤗 Hugging Face Dataset](https://huggingface.co/datasets/GipAI/ReaoningV) | [🤗 Hugging Face Model](https://huggingface.co/GipAI/ReasoningV-7B) | [🌐 ModelScope Dataset](https://modelscope.cn/datasets/GipsyAI/ReasoningV) | [🌐 ModelScope Model](https://modelscope.cn/models/GipsyAI/ReasoningV-7B) | [📄 Paper](https://arxiv.org/pdf/2504.14560v3)

  <div>&nbsp;</div>

  [![Hugging Face Dataset](https://img.shields.io/badge/Dataset-HuggingFace-blue?link=https://huggingface.co/datasets/GipAI/ReaoningV)](https://huggingface.co/datasets/GipAI/ReaoningV)
  [![Hugging Face Model](https://img.shields.io/badge/Model-HuggingFace-blue?link=https://huggingface.co/GipAI/ReasoningV-7B)](https://huggingface.co/GipAI/ReasoningV-7B)
  [![ModelScope Dataset](https://img.shields.io/badge/Dataset-ModelScope-orange?link=https://modelscope.cn/datasets/GipsyAI/ReasoningV)](https://modelscope.cn/datasets/GipsyAI/ReasoningV)
  [![ModelScope Model](https://img.shields.io/badge/Model-ModelScope-orange?link=https://modelscope.cn/models/GipsyAI/ReasoningV-7B)](https://modelscope.cn/models/GipsyAI/ReasoningV-7B)
  [![GitHub Stars](https://img.shields.io/github/stars/BUAA-CLab/ReasoningV?style=social)](https://github.com/BUAA-CLab/ReasoningV)
  [![License](https://img.shields.io/github/license/BUAA-CLab/ReasoningV.svg)](https://github.com/BUAA-CLab/ReasoningV/blob/main/LICENSE) [![Python Version](https://img.shields.io/badge/python-3.x-blue)](https://www.python.org/) <div>&nbsp;</div>

  [📚 GitHub Repo](https://github.com/BUAA-CLab/ReasoningV) |
  [📄 Paper](https://arxiv.org/pdf/2504.14560v3) |
  [🐛 Report Issues](https://github.com/BUAA-CLab/ReasoningV/issues/new/choose)

</div>

-----

## Table of Contents

* [Introduction](#introduction)
* [Open Source Plan](#open-source-plan)
* [Citation](#citation)
* [License](#license)

-----
<div id="introduction"></div>

## Introduction

ReasoningV is a novel model designed to enhance Verilog code generation by addressing key challenges faced by Large Language Models (LLMs), including data quality limitations, insufficient reasoning capabilities for complex hardware tasks, and computational inefficiency. We propose a **hybrid reasoning strategy** that integrates trained intrinsic capabilities with dynamic inference adaptation.

Our work introduces three complementary innovations:

1.  **ReasoningV Dataset:** A high-quality dataset of functionally verified Verilog instances with reasoning paths.
2.  **Two-Stage Training:** A training approach combining parameter-efficient fine-tuning for foundational knowledge with full-parameter optimization for enhanced reasoning.
3.  **Adaptive Reasoning Mechanism:** Dynamically adjusts reasoning depth based on problem complexity to improve efficiency (reducing token consumption) while preserving performance.

Experimental results demonstrate ReasoningV's effectiveness, achieving competitive performance on Verilog benchmarks compared to leading models, particularly standing out among open-source alternatives. This work aims to provide a more reliable and accessible pathway for advancing AI-driven hardware design automation.

-----
<div id="open-source-plan"></div>

## Open Source Plan

We are committed to open-sourcing the key components of the ReasoningV project to facilitate research and development in AI-driven hardware design.

We have released the following resources:

- ✅ **ReasoningV Dataset:** High-quality, functionally verified dataset available on:
  - [Hugging Face](https://huggingface.co/datasets/GipAI/ReaoningV)
  - [ModelScope](https://modelscope.cn/datasets/GipsyAI/ReasoningV)
  
- ✅ **ReasoningV-7B Model Weights:** Pre-trained model weights available on:
  - [Hugging Face](https://huggingface.co/GipAI/ReasoningV-7B)
  - [ModelScope](https://modelscope.cn/models/GipsyAI/ReasoningV-7B)

- [ ] **Two-Stage Training Code:** Code implementation for our proposed training methodology.

**Release Strategy:**

The dataset and model weights are now available on both Hugging Face and ModelScope platforms. We will continue to release the training code and other associated resources sequentially after the paper is formally accepted for publication. Stay tuned for updates!

-----
<div id="citation"></div>


## Citation

If you find ReasoningV useful for your research, please consider citing our paper:

```bibtex
@article{qin2025reasoningv,
  title={ReasoningV: Efficient Verilog Code Generation with Adaptive Hybrid Reasoning Model},
  author={Qin, Haiyan and Xie, Zhiwei and Li, Jingjing and Li, LiangChen and Feng, Xiaotong and Liu, Junzhan and Kang, Wang},
  journal={arXiv preprint arXiv:2504.14560},
  year={2025}
}
```


## License

This project is licensed under the Apache License 2.0 - see the [LICENSE](https://www.google.com/url?sa=E&source=gmail&q=https://github.com/BUAA-CLab/ReasoningV/blob/main/LICENSE) file for details. 
