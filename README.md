

<div align="center">
  <img src="Pics/ReasoningV-Logo.jpeg" width="200" alt="ReasoningV Logo"> <div>&nbsp;</div>
  <h1>ReasoningV: Efficient Verilog Code Generation with Adaptive Hybrid Reasoning Model</h1>
  <div>&nbsp;</div>

  English | [简体中文](README-CN.md)

  <div>&nbsp;</div>

  [🤗 Hugging Face Dataset](https://huggingface.co/datasets/hyq001/ReasoningV-5K) | [🤗 Hugging Face Model](https://huggingface.co/hyq001/ReasoninV) | [🌐 GitHub Repo](https://github.com/BUAA-CLab/ReasoningV) | [📄 Paper](https://arxiv.org/pdf/2504.14560v3)

  <div>&nbsp;</div>

  [![Hugging Face Dataset](https://img.shields.io/badge/Dataset-ReasoningV--5K-blue?link=https://huggingface.co/datasets/hyq001/ReasoningV-5K)](https://huggingface.co/datasets/hyq001/ReasoningV-5K)
  [![Hugging Face Model](https://img.shields.io/badge/Model-ReasoningV-blue?link=https://huggingface.co/hyq001/ReasoninV)](https://huggingface.co/hyq001/ReasoninV)
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

1.  **ReasoningV-5K Dataset:** A high-quality dataset of over 5,000 functionally verified Verilog instances with reasoning paths.
2.  **Two-Stage Training:** A training approach combining parameter-efficient fine-tuning for foundational knowledge with full-parameter optimization for enhanced reasoning.
3.  **Adaptive Reasoning Mechanism:** Dynamically adjusts reasoning depth based on problem complexity to improve efficiency (reducing token consumption) while preserving performance.

Experimental results demonstrate ReasoningV's effectiveness, achieving competitive performance on Verilog benchmarks compared to leading models, particularly standing out among open-source alternatives. This work aims to provide a more reliable and accessible pathway for advancing AI-driven hardware design automation.

-----
<div id="open-source-plan"></div>

## Open Source Plan

We are committed to open-sourcing the key components of the ReasoningV project to facilitate research and development in AI-driven hardware design.

We plan to release the following:

- [ ] **ReasoningV-5K Dataset:** High-quality, functionally verified dataset ([Hugging Face Link](https://huggingface.co/datasets/hyq001/ReasoningV-5K)).
- [ ] **ReasoningV Model Weights:** Pre-trained model weights ([Hugging Face Link](https://huggingface.co/hyq001/ReasoninV)).
- [ ] **Two-Stage Training Code:** Code implementation for our proposed training methodology.

**Release Strategy:**

The dataset and model weights are already available on Hugging Face. We will continue to release the training code and other associated resources sequentially after the paper is formally accepted for publication. Stay tuned for updates!

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
