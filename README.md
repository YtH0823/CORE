<h1 align="center">Global Cross-Modal Geo-Localization: A Million-Scale Dataset and a Physical Consistency Learning Framework</h1>

<p align="center">
  Yutong Hu, Jinhui Chen, Chaoqiang Xu, Yuan Kou, Sili Zhou, Shaocheng Yan, Pengcheng Shi, Qingwu Hu, Jiayuan Li
</p>

<p align="center">
  <a href="#-update">Update</a> | 
  <a href="#-abstract">Abstract</a> | 
  <a href="#-datasets">Datasets</a> | 
  <a href="#-model">Model</a> | 
  <a href="#-usage">Usage</a>
</p>

## 🔥 Update
- **2026.3.9** The paper is post on arXiv!([CORE](https://arxiv.org/abs/2603.08491))


## Abstract
Cross-modal Geo-localization (CMGL) matches ground-level text descriptions with geo-tagged aerial imagery, which is crucial for pedestrian navigation and emergency response. However, existing researches are constrained by narrow geographic coverage and simplistic scene diversity, failing to reflect the immense spatial heterogeneity of global architectural styles and topographic features. To bridge this gap and facilitate universal positioning, we introduce CORE, the first million-scale dataset dedicated to global CMGL. CORE comprises 1,034,786 cross-view images sampled from 225 distinct geographic regions across all continents, offering an unprecedented variety of perspectives in varying environmental conditions and urban layouts. We leverage the zero-shot reasoning of Large Vision-Language Models (LVLMs) to synthesize high-quality scene descriptions rich in discriminative cues. Furthermore, we propose a physical-law-aware network (PLANET) for cross-modal geo-localization. PLANET introduces a novel contrastive learning paradigm to guide textual representations in capturing the intrinsic physical signatures of satellite imagery. Extensive experiments across varied geographic regions demonstrate that PLANET significantly outperforms state-of-the-art methods, establishing a new benchmark for robust, global-scale geo-localization.

<p align="center">
  <img width="100%" alt="Distribution_01" src="https://github.com/user-attachments/assets/67374a12-7849-4e4c-9086-7732c753501d" />
  <br>
  <em>Figure 1. Geographical distribution map of sampled images and corresponding text annotations from the CORE dataset.</em>
</p>


<p align="center">
  <img width="100%"  alt="Pipeline_01" src="https://github.com/user-attachments/assets/94db6fb1-8ac6-46e4-87ce-b0a89ebe09db" />
  <br>
  <em>Figure 2. Pipeline of proposed PLANET.</em>
</p>




## Datasets
The complete CORE dataset and source code will be made publicly available upon acceptance.

## Model
Model weights for PLANET (on CORE and other datasets) will be released upon acceptance.
