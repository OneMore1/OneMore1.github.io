---
permalink: /
title: ""
excerpt: ""
author_profile: false
redirect_from:
  - /about/
  - /about.html
---

<span class="anchor" id="about-me"></span>

<section class="home-hero">
  <p class="intro-kicker">Computational neuroscience · fMRI foundation models · neuromodulation</p>
  <h1 class="intro-title">Mo Wang</h1>
  <p class="hero-role">PhD candidate in Computer Science · University of Warwick / Southern University of Science and Technology</p>
  <p class="intro-lead">
    I study how machine learning can model, decode, and modulate human brain activity. My work connects large-scale fMRI foundation models, neural decoding, personalized brain parcellation, and computational optimization for transcranial electrical stimulation.
  </p>
  <p class="hero-links">
    <a href="mailto:Mo.Wang.1@warwick.ac.uk">Email</a>
  </p>
</section>

<section class="research-overview" aria-label="Research interests">
  <div class="section-heading">
    <p>Research Interests</p>
    <h2>Learning representations of the brain, then using them responsibly.</h2>
  </div>
  <div class="research-grid">
    <article class="research-card">
      <span>01</span>
      <h3>fMRI foundation models</h3>
      <p>Representation learning for heterogeneous, atlas-free, and multi-state fMRI data, with an emphasis on models that transfer across cohorts, tasks, and acquisition settings.</p>
    </article>
    <article class="research-card">
      <span>02</span>
      <h3>Brain decoding and parcellation</h3>
      <p>Neural decoding and personalized brain atlas construction for connecting computational representations with interpretable functional organization.</p>
    </article>
    <article class="research-card">
      <span>03</span>
      <h3>Personalized neuromodulation</h3>
      <p>Computational modeling and optimization for transcranial electrical stimulation, including individualized stimulation policies and target-aware intervention design.</p>
    </article>
  </div>
</section>

<span class="anchor" id="publications"></span>

<section class="publication-header">
  <div class="section-heading">
    <p>Selected Publications</p>
    <h2>Recent work across fMRI representation learning and neuromodulation.</h2>
  </div>
  <p class="publication-note"><sup>†</sup> Equal contribution; <sup>*</sup> co-corresponding author.</p>
</section>

<div class="paper-box paper-box--featured">
  <div class="paper-box-image">
    <div><img src="images/flexibrain.png" alt="FlexiBrain framework figure"></div>
  </div>
  <div class="paper-box-text" markdown="1">

  <p class="paper-venue">European Conference on Computer Vision (ECCV2026)</p>

  <p class="paper-title">FlexiBrain: A Mamba-JEPA Architecture for Voxel-Level Representation Learning from Variable-Resolution Native fMRI</p>

  <p class="paper-authors"><strong>Mo Wang<sup>&dagger;</sup></strong>, Wenhao Ye<sup>&dagger;</sup>, Junfeng Xia<sup>&dagger;</sup>, Minghao Xu, Hongkai Wen, Quanying Liu</p>

  <p class="paper-summary">Voxel-level fMRI representation learning for variable-resolution native fMRI through flexible spatial-temporal patching and Mamba-based predictive learning.</p>
  <p class="paper-links">
    <a class="paper-link paper-link--paper" href="https://arxiv.org/abs/2606.11500">Paper</a>
    <a class="paper-link paper-link--code" href="https://github.com/OneMore1/FlexiBrain">Code</a>
    <a class="paper-link paper-link--hf" href="https://huggingface.co/OneMore1/FlexiBrain">HuggingFace</a>
  </p>

  </div>
</div>

<div class="paper-box paper-box--featured">
  <div class="paper-box-image">
    <div><img src="images/braindit.png" alt="Brain-DiT framework figure"></div>
  </div>
  <div class="paper-box-text" markdown="1">

  <p class="paper-venue">Medical Image Computing and Computer-Assisted Intervention (MICCAI2026)</p>

  <p class="paper-title">Brain-DiT: A Universal Multi-state fMRI Foundation Model with Metadata-Conditioned Pretraining</p>

  <p class="paper-authors">Junfeng Xia, Wenhao Ye, Xuanye Pan, Xinyu Shen, <strong>Mo Wang<sup>&#42;</sup></strong>, Quanying Liu<sup>&#42;</sup></p>

  <p class="paper-summary">A diffusion-transformer foundation model for multi-state fMRI, using metadata-conditioned pretraining and downstream adaptation for demographic and clinical prediction tasks.</p>
  <p class="paper-links">
    <a class="paper-link paper-link--paper" href="https://arxiv.org/abs/2604.12683">Paper</a>
    <a class="paper-link paper-link--code" href="https://github.com/REDMAO4869/Brain-DiT">Code</a>
  </p>

  </div>
</div>

<div class="paper-box paper-box--featured">
  <div class="paper-box-image">
    <div><img src="images/omnifmri.png" alt="Omni-fMRI framework figure"></div>
  </div>
  <div class="paper-box-text" markdown="1">

  <p class="paper-venue">International Conference on Machine Learning (ICML2026)</p>

  [Omni-fMRI: A Universal Atlas-Free fMRI Foundation Model](https://doi.org/10.48550/arXiv.2601.23090)

  <p class="paper-authors"><strong>Mo Wang<sup>&dagger;</sup></strong>, Wenhao Ye<sup>&dagger;</sup>, Junfeng Xia, Junxiang Zhang, Xuanye Pan, Minghao Xu, Haotian Deng, Hongkai Wen, Quanying Liu</p>

  <p class="paper-summary">Atlas-free representation learning for broad fMRI analysis, designed to reduce dependence on predefined ROI parcellations.</p>
  <p class="paper-links">
    <a class="paper-link paper-link--paper" href="https://doi.org/10.48550/arXiv.2601.23090">Paper</a>
    <a class="paper-link paper-link--code" href="https://github.com/OneMore1/Omni-fMRI">Code</a>
    <a class="paper-link paper-link--hf" href="https://huggingface.co/OneMore1/Omni-fMRI">HuggingFace</a>
    <a class="paper-link paper-link--docker" href="https://hub.docker.com/r/onemore1/onmi-fmri">Docker</a>
  </p>

  </div>
</div>

<div class="paper-box">
  <div class="paper-box-image">
    <div><img src="images/JNE2025.png" alt="Personalized tES review figure"></div>
  </div>
  <div class="paper-box-text" markdown="1">

  <p class="paper-venue">Journal of Neural Engineering</p>

  [Personalized transcranial electrical stimulation: a review of computational modeling and optimization](https://iopscience.iop.org/article/10.1088/1741-2552/ae4d8d)

  <p class="paper-authors"><strong>Mo Wang</strong>, Kexin Zheng, Yawen Xin, Xinyi Chen, Yifei Liu, Huichun Luo, Ti-Fei Yuan, Hongkai Wen, Pengfei Wei, Quanying Liu</p>

  <p class="paper-summary">A review of computational modeling, individualized optimization, and practical design choices for personalized tES.</p>
  <p class="paper-links"><a class="paper-link paper-link--paper" href="https://iopscience.iop.org/article/10.1088/1741-2552/ae4d8d">Paper</a></p>

  </div>
</div>

<div class="paper-box">
  <div class="paper-box-image">
    <div><img src="images/Neurips2025.png" alt="DCA brain atlas figure"></div>
  </div>
  <div class="paper-box-text" markdown="1">

  <p class="paper-venue">Advances in Neural Information Processing Systems (NeurIPS2025)</p>

  [DCA: Graph-Guided Deep Embedding Clustering for Brain Atlases](https://arxiv.org/abs/2509.01426)

  <p class="paper-authors"><strong>Mo Wang<sup>&dagger;</sup></strong>, Kaining Peng<sup>&dagger;</sup>, Jingsheng Tang<sup>&dagger;</sup>, Hongkai Wen, Quanying Liu</p>

  <p class="paper-summary">Graph-guided deep clustering for data-driven atlas construction and interpretable regional organization.</p>
  <p class="paper-links">
    <a class="paper-link paper-link--paper" href="https://arxiv.org/abs/2509.01426">Paper</a>
    <a class="paper-link paper-link--code" href="https://github.com/ncclab-sustech/DCA">Code</a>
  </p>

  </div>
</div>

<div class="paper-box">
  <div class="paper-box-image">
    <div><img src="images/NB2025.png" alt="Temporal interference stimulation figure"></div>
  </div>
  <div class="paper-box-text" markdown="1">

  <p class="paper-venue">Neuroscience Bulletin</p>

  [Transcranial temporal interference stimulation precisely targets deep brain regions to regulate eye movements](https://doi.org/10.1007/s12264-025-01387-3)

  <p class="paper-authors"><strong>Mo Wang<sup>&dagger;</sup></strong>, Sixian Song<sup>&dagger;</sup>, Dan Li, Guangchao Zhao, Yu Luo, Yi Tian, Jiajia Zhang, Quanying Liu, Pengfei Wei</p>

  <p class="paper-summary">Experimental and modeling evidence for precise deep-brain targeting with temporal interference stimulation.</p>
  <p class="paper-links"><a class="paper-link paper-link--paper" href="https://doi.org/10.1007/s12264-025-01387-3">Paper</a></p>

  </div>
</div>

<div class="paper-box">
  <div class="paper-box-image">
    <div><img src="images/Frequency-specific and state-dependent neural responses to brain stimulation.png" alt="State-dependent brain stimulation figure"></div>
  </div>
  <div class="paper-box-text" markdown="1">

  <p class="paper-venue">Molecular Psychiatry</p>

  [Frequency-specific and state-dependent neural responses to brain stimulation](https://doi.org/10.1038/s41380-025-02892-7)

  <p class="paper-authors">Huichun Luo<sup>&dagger;</sup>, Xiaolai Ye<sup>&dagger;</sup>, Hui-Ting Cai<sup>&dagger;</sup>, <strong>Mo Wang<sup>&dagger;</sup></strong>, Yue Wang, Qiangqiang Liu, Ying Xu, Ziyu Mao, Yanqing Cai, Jing Hong, Chencheng Zhang, Pengfei Wei, Yong Lu, Quanying Liu, Jiwen Xu, Ti-Fei Yuan</p>

  <p class="paper-summary">A study of how neural responses to stimulation depend on frequency and brain state.</p>
  <p class="paper-links"><a class="paper-link paper-link--paper" href="https://doi.org/10.1038/s41380-025-02892-7">Paper</a></p>

  </div>
</div>

<div class="paper-box">
  <div class="paper-box-image">
    <div><img src="images/Movea.png" alt="MOVEA tES optimization figure"></div>
  </div>
  <div class="paper-box-text" markdown="1">

  <p class="paper-venue">NeuroImage</p>

  [Multi-objective optimization via evolutionary algorithm (MOVEA) for high-definition transcranial electrical stimulation of the human brain](https://doi.org/10.1016/j.neuroimage.2023.120331)

  <p class="paper-authors"><strong>Mo Wang</strong>, Kexin Lou, Zeming Liu, Pengfei Wei, Quanying Liu</p>

  <p class="paper-summary">A multi-objective optimization framework for high-definition transcranial electrical stimulation planning.</p>
  <p class="paper-links">
    <a class="paper-link paper-link--paper" href="https://doi.org/10.1016/j.neuroimage.2023.120331">Paper</a>
    <a class="paper-link paper-link--code" href="https://github.com/ncclab-sustech/MOVEA">Code</a>
  </p>

  </div>
</div>

<section class="career-grid">
  <div class="career-block" id="education">
    <p class="section-eyebrow">Education</p>
    <ul>
      <li><strong>2022 - now</strong><span>PhD candidate in Computer Science, Department of Computer Science, University of Warwick, U.K.</span></li>
      <li><strong>2019 - 2020</strong><span>MSc in Advanced Computer Science, Department of Computer Science, University of Birmingham, U.K.</span></li>
      <li><strong>2015 - 2019</strong><span>BS in The Internet of Things, Department of Computer Science, Northwest University, China.</span></li>
    </ul>
  </div>
  <div class="career-block" id="experience">
    <p class="section-eyebrow">Experience</p>
    <ul>
      <li><strong>2021 - 2022</strong><span>Research assistant, Southern University of Science and Technology, China.</span></li>
      <li><strong>2020 - 2021</strong><span>Research assistant, University of Birmingham, U.K.</span></li>
    </ul>
  </div>
</section>
