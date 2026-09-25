---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

<span class="anchor" id="about-me"></span>

<div class="intro-copy">
  <p>I am a PhD candidate in Computer Science at the University of Warwick, working at the intersection of artificial intelligence, neuroimaging, and computational neuroscience.</p>

  <p>My research develops fine-grained brain foundation models for learning generalizable representations from large-scale fMRI and EEG data. I am particularly interested in functional brain organization, neurodevelopment, and individual variability. I further connect individualized brain representations with personalized brain parcellation and computational neuromodulation, with the long-term goal of linking brain representation, organization, and intervention within a unified framework for personalized neuroscience.</p>
</div>

<span class="anchor" id="news"></span>

# News

<ul class="news-list">
  <li><span>2026.09</span><div><strong>FlatClip</strong> was accepted to NeurIPS 2026.</div></li>
  <li><span>2026.09</span><div><strong>BrainWorld</strong> was selected for an oral presentation at NeurIPS 2026.</div></li>
  <li><span>2026</span><div><strong>Omni-fMRI</strong> and <strong>FlexiBrain</strong> were accepted to ICML and ECCV; <strong>Brain-DiT</strong> was selected for the MICCAI Best Paper Shortlist.</div></li>
</ul>

<span class="anchor" id="publications"></span>

# Selected Publications

<p class="publication-note"><sup>&dagger;</sup> Equal contribution; <sup>*</sup> co-corresponding author.</p>

<div class="paper-box paper-box--new">
  <div class="paper-box-image">
    <div><div class="badge">NeurIPS 2026</div><img src="images/flatclip.png" alt="FlatClip pipeline"></div>
  </div>
  <div class="paper-box-text" markdown="1">

  <p class="paper-title">FlatClip: A Geometry-Aware Surface-Level Baseline for fMRI Representation Learning</p>

  <p class="paper-authors"><strong>Mo Wang</strong>, Wenhao Ye, Zihan Ning, Jiayu Zuo, Junfeng Xia, Hongkai Wen<sup>*</sup>, Quanying Liu<sup>*</sup></p>

  FlatClip reuses a frozen image foundation model over geometry-aware cortical flatmap sequences, providing a practical surface-level baseline between ROI and voxel representations.

  </div>
</div>

<div class="paper-box paper-box--new">
  <div class="paper-box-image">
    <div><div class="badge">NeurIPS 2026 Oral</div><img src="images/brainworld.png" alt="BrainWorld framework"></div>
  </div>
  <div class="paper-box-text" markdown="1">

  [BrainWorld: A Structural-Prior-Conditioned Generative Model for Whole-Brain 4D fMRI Dynamics](https://arxiv.org/abs/2606.17742)

  <p class="paper-authors">Junfeng Xia, Wenhao Ye, Junxiang Zhang, Xuanye Pan, <strong>Mo Wang<sup>*</sup></strong>, Quanying Liu<sup>*</sup></p>

  A structural-prior-conditioned generative model for long-horizon whole-brain 4D fMRI dynamics and transferable multimodal representation learning.

  <p class="paper-links"><a href="https://arxiv.org/abs/2606.17742">Paper</a></p>

  </div>
</div>

<div class="paper-box">
  <div class="paper-box-image">
    <div><div class="badge">ECCV 2026</div><img src="images/flexibrain.png" alt="FlexiBrain framework"></div>
  </div>
  <div class="paper-box-text" markdown="1">

  [FlexiBrain: A Mamba-JEPA Architecture for Voxel-Level Representation Learning from Variable-Resolution Native fMRI](https://link.springer.com/chapter/10.1007/978-3-032-37261-1_25)

  <p class="paper-authors"><strong>Mo Wang<sup>&dagger;</sup></strong>, Wenhao Ye<sup>&dagger;</sup>, Junfeng Xia<sup>&dagger;</sup>, Minghao Xu, Hongkai Wen, Quanying Liu</p>

  Voxel-level representation learning for variable-resolution native fMRI through flexible spatial-temporal patching and Mamba-based predictive learning.

  <p class="paper-links"><a href="https://link.springer.com/chapter/10.1007/978-3-032-37261-1_25">Paper</a><a href="https://github.com/OneMore1/FlexiBrain">Code</a><a href="https://huggingface.co/OneMore1/FlexiBrain">Model</a></p>

  </div>
</div>

<div class="paper-box">
  <div class="paper-box-image">
    <div><div class="badge">MICCAI 2026 Best Paper Shortlist</div><img src="images/braindit.png" alt="Brain-DiT framework"></div>
  </div>
  <div class="paper-box-text" markdown="1">

  [Brain-DiT: A Universal Multi-state fMRI Foundation Model with Metadata-Conditioned Pretraining](https://arxiv.org/abs/2604.12683)

  <p class="paper-authors">Junfeng Xia, Wenhao Ye, Xuanye Pan, Xinyu Shen, <strong>Mo Wang<sup>*</sup></strong>, Quanying Liu<sup>*</sup></p>

  Metadata-conditioned diffusion pretraining for multi-state fMRI and downstream demographic and clinical prediction.

  <p class="paper-links"><a href="https://arxiv.org/abs/2604.12683">Paper</a><a href="https://github.com/REDMAO4869/Brain-DiT">Code</a></p>

  </div>
</div>

<div class="paper-box">
  <div class="paper-box-image">
    <div><div class="badge">ICML 2026</div><img src="images/omnifmri.png" alt="Omni-fMRI framework"></div>
  </div>
  <div class="paper-box-text" markdown="1">

  [Omni-fMRI: A Universal Atlas-Free fMRI Foundation Model](https://openreview.net/forum?id=Rc8th2rXXe)

  <p class="paper-authors"><strong>Mo Wang<sup>&dagger;</sup></strong>, Wenhao Ye<sup>&dagger;</sup>, Junfeng Xia, Junxiang Zhang, Xuanye Pan, Minghao Xu, Haotian Deng, Hongkai Wen, Quanying Liu</p>

  Atlas-free representation learning for broad fMRI analysis across cohorts, brain states, and downstream tasks.

  <p class="paper-links"><a href="https://openreview.net/forum?id=Rc8th2rXXe">Paper</a><a href="https://github.com/OneMore1/Omni-fMRI">Code</a><a href="https://huggingface.co/OneMore1/Omni-fMRI">Model</a><a href="https://hub.docker.com/r/onemore1/onmi-fmri">Docker</a></p>

  </div>
</div>

<div class="paper-box">
  <div class="paper-box-image">
    <div><div class="badge">NeurIPS 2025</div><img src="images/Neurips2025.png" alt="DCA brain atlas framework"></div>
  </div>
  <div class="paper-box-text" markdown="1">

  [DCA: Graph-Guided Deep Embedding Clustering for Brain Atlases](https://arxiv.org/abs/2509.01426)

  <p class="paper-authors"><strong>Mo Wang<sup>&dagger;</sup></strong>, Kaining Peng<sup>&dagger;</sup>, Jingsheng Tang<sup>&dagger;</sup>, Hongkai Wen, Quanying Liu</p>

  Graph-guided deep clustering for data-driven atlas construction and interpretable personalized functional organization.

  <p class="paper-links"><a href="https://arxiv.org/abs/2509.01426">Paper</a><a href="https://github.com/ncclab-sustech/DCA">Code</a></p>

  </div>
</div>

<div class="paper-box">
  <div class="paper-box-image">
    <div><div class="badge">NeuroImage 2023</div><img src="images/Movea.png" alt="MOVEA optimization framework"></div>
  </div>
  <div class="paper-box-text" markdown="1">

  [Multi-objective optimization via evolutionary algorithm (MOVEA) for high-definition transcranial electrical stimulation of the human brain](https://doi.org/10.1016/j.neuroimage.2023.120331)

  <p class="paper-authors"><strong>Mo Wang</strong>, Kexin Lou, Zeming Liu, Pengfei Wei, Quanying Liu</p>

  A multi-objective evolutionary framework for individualized stimulation planning across intensity, focality, and avoidance-region constraints.

  <p class="paper-links"><a href="https://doi.org/10.1016/j.neuroimage.2023.120331">Paper</a><a href="https://github.com/ncclab-sustech/MOVEA">Code</a></p>

  </div>
</div>

## Additional Publications

<ul class="compact-publications">
  <li><strong>Omni-Sleep: A Sleep Foundation Model via Hierarchical Contrastive Learning of CNS-ANS Dynamic.</strong><br>Zhoujie Hou, Song Wang, Kexin Lou, <strong>Mo Wang</strong>, Chen Wei, Quanying Liu. <em>MICCAI 2026.</em> <a href="https://arxiv.org/abs/2607.07720">Paper</a> · <a href="https://github.com/AutoBrain-sleep/OmniSleep">Code</a></li>
  <li><strong>A 5.0 T Ultra-High-Field fMRI Dataset for Naturalistic Visual Scene Processing.</strong><br>Gengchen Ye<sup>&dagger;</sup>, <strong>Mo Wang<sup>&dagger;</sup></strong>, Chiyin Li, Yihao Peng, Yilin Qian, Yutao Wang, Xinyi Si, Shaoxin Xiang, Fanzhi Jiang, Lu Wang, Ming Zhang. <em>Scientific Data, 2026.</em> <a href="https://doi.org/10.1038/s41597-026-07885-x">Paper</a></li>
  <li><strong>OpTI-Mouse: Optimization for Targeted Temporal Interference Stimulation in the Mouse Brain.</strong><br>Jingsheng Tang<sup>&dagger;</sup>, Zhengkang Zhou<sup>&dagger;</sup>, Yingyue Xin, Zihan Ning, Pengfei Wei, <strong>Mo Wang<sup>*</sup></strong>, Quanying Liu<sup>*</sup>. <em>EMBC 2026.</em> <a href="https://arxiv.org/abs/2606.15192">Paper</a></li>
  <li><strong>Personalized transcranial electrical stimulation: A review of computational modeling and optimization.</strong><br><strong>Mo Wang</strong>, Kexin Zheng, Yawen Xin, Xinyi Chen, Yifei Liu, Huichun Luo, Ti-Fei Yuan, Hongkai Wen, Pengfei Wei, Quanying Liu. <em>Journal of Neural Engineering, 2026.</em> <a href="https://doi.org/10.1088/1741-2552/ae4d8d">Paper</a></li>
  <li><strong>Transcranial temporal interference stimulation precisely targets deep brain regions to regulate eye movements.</strong><br><strong>Mo Wang<sup>&dagger;</sup></strong>, Sixian Song<sup>&dagger;</sup>, Dan Li, Guangchao Zhao, Yu Luo, Yi Tian, et al. <em>Neuroscience Bulletin, 2025.</em> <a href="https://doi.org/10.1007/s12264-025-01387-3">Paper</a></li>
  <li><strong>Frequency-specific and state-dependent neural responses to brain stimulation.</strong><br>Huichun Luo<sup>&dagger;</sup>, Xiaolai Ye<sup>&dagger;</sup>, Hui-Ting Cai<sup>&dagger;</sup>, <strong>Mo Wang<sup>&dagger;</sup></strong>, et al. <em>Molecular Psychiatry, 2025.</em> <a href="https://doi.org/10.1038/s41380-025-02892-7">Paper</a></li>
  <li><strong>Stimulation of an entorhinal-hippocampal extinction circuit facilitates fear extinction in a post-traumatic stress disorder model.</strong><br>Ze-Jie Lin, Xue Gu, Wan-Kun Gong, <strong>Mo Wang</strong>, Yan-Jiao Wu, Qi Wang, Xin-Rong Wu, Xin-Yu Zhao, Michael X. Zhu, Lu-Yang Wang, Quanying Liu, Ti-Fei Yuan, Wei-Guang Li, Tian-Le Xu. <em>The Journal of Clinical Investigation, 2024.</em> <a href="https://doi.org/10.1172/JCI181095">Paper</a></li>
  <li><strong>Explainable fMRI-based brain decoding via spatial temporal-pyramid graph convolutional network.</strong><br>Ziyuan Ye, Youzhi Qu, Zhichao Liang, <strong>Mo Wang</strong>, Quanying Liu. <em>Human Brain Mapping, 2023.</em> <a href="https://doi.org/10.1002/hbm.26255">Paper</a></li>
</ul>

<span class="anchor" id="education"></span>

# Education

<ul class="timeline-list">
  <li><span>2022 - 2026</span><div><strong>PhD candidate in Computer Science</strong><br>Department of Computer Science, University of Warwick, UK</div></li>
  <li><span>2019 - 2020</span><div><strong>MSc in Computer Science</strong><br>Department of Computer Science, University of Birmingham, UK</div></li>
  <li><span>2015 - 2019</span><div><strong>BS in the Internet of Things</strong><br>Department of Computer Science, Northwest University, China</div></li>
</ul>

<span class="anchor" id="experience"></span>

# Experience

<ul class="timeline-list">
  <li><span>2025 - 2026</span><div><strong>Visiting Student</strong><br>Department of Biomedical Engineering, Southern University of Science and Technology, China</div></li>
  <li><span>2021 - 2022</span><div><strong>Research Assistant</strong><br>Southern University of Science and Technology, China</div></li>
  <li><span>2020 - 2021</span><div><strong>Research Assistant</strong><br>University of Birmingham, UK</div></li>
</ul>
