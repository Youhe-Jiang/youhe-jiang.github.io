---
permalink: /
title: "About"
excerpt: "Research on efficient systems for large-scale AI."
author_profile: true
show_title: false
redirect_from:
  - /about/
  - /about.html
---

<section class="home-hero">
  <p class="home-hero__eyebrow">Distributed systems • LLM serving • large-scale training</p>
  <h1 class="home-hero__title">I build systems that make modern AI workloads more efficient at scale.</h1>
  <p class="home-hero__lead">
    I am Youhe Jiang, a PhD student in Computer Science at the University of Cambridge advised by
    <a href="https://www.cl.cam.ac.uk/~ey204/">Dr. Eiko Yoneki</a>.
    My work focuses on efficient LLM serving, heterogeneous GPU systems, distributed training, and the systems infrastructure needed to run large models under real deployment constraints.
  </p>
  <div class="home-hero__actions">
    <a class="home-pill" href="/publications/">Browse publications</a>
    <a class="home-pill home-pill--ghost" href="/cv/">View CV</a>
  </div>
</section>

<section class="home-grid">
  <div class="home-card home-card--accent">
    <p class="home-card__label">Current position</p>
    <h2>PhD student at Cambridge</h2>
    <p>
      I am currently pursuing a PhD in Computer Science at the University of Cambridge. My research examines how to improve the performance,
      cost-efficiency, and scalability of AI systems across both training and inference.
    </p>
  </div>
  <div class="home-card">
    <p class="home-card__label">Research interests</p>
    <ul class="home-list">
      <li>LLM serving and heterogeneous inference</li>
      <li>Distributed training systems for large foundation models</li>
      <li>Topology-aware and communication-efficient optimisation</li>
      <li>Systems support for decentralized and agentic AI workloads</li>
    </ul>
  </div>
  <div class="home-card">
    <p class="home-card__label">Previous experience</p>
    <p>
      Before Cambridge, I worked as a Research Assistant at HKUST and Peking University, and held R&amp;D internships at Tsinghua University,
      Kuaishou Technology, and Baidu. That path shaped a research style grounded in both systems theory and production constraints.
    </p>
  </div>
</section>

<section class="home-section">
  <div class="home-section__header">
    <p class="home-card__label">Selected papers</p>
    <h2>Recent work on large-scale AI systems</h2>
  </div>
  <div class="pub-list">
    <article class="pub-item">
      <p class="pub-item__meta">OSDI 2026</p>
      <h3>LLMFabric: Unifying Decentralized HPC Clusters for Heterogeneous LLM Serving</h3>
      <p>Joint work on unifying decentralized HPC clusters for practical heterogeneous LLM serving.</p>
    </article>
    <article class="pub-item">
      <p class="pub-item__meta">MLSys 2026</p>
      <h3>BOute: Cost-Efficient LLM Serving with Heterogeneous LLMs and GPUs via Multi-Objective Bayesian Optimization</h3>
      <p>Research on improving cost-efficiency in LLM serving by jointly reasoning about model and hardware heterogeneity.</p>
    </article>
    <article class="pub-item">
      <p class="pub-item__meta">NeurIPS 2025</p>
      <h3>Efficient Pre-Training of LLMs via Topology-Aware Communication Alignment on 9600+ GPUs</h3>
      <p>Work on scaling pre-training efficiently under large-cluster communication constraints.</p>
    </article>
    <article class="pub-item">
      <p class="pub-item__meta">MLSys 2025</p>
      <h3>ThunderServe: High-performance and Cost-efficient LLM Serving in Cloud Environments</h3>
      <p>A serving system designed to improve performance and deployment efficiency in cloud settings.</p>
    </article>
  </div>
</section>

<section class="home-section home-section--split">
  <div>
    <p class="home-card__label">Open-source work</p>
    <h2>I contribute to systems that move from papers into usable infrastructure.</h2>
    <p>
      My research is closely tied to real systems. I have led or contributed to open-source frameworks across both serving and training,
      including Parallax, FSA, Galvatron, Hetu, Bagua, PaddlePaddle, LMDeploy, and AReaL.
    </p>
    <p>
      That work sits at the boundary between systems research and deployable engineering: better runtimes, better scaling behaviour,
      and cleaner abstractions for difficult workloads.
    </p>
  </div>
  <div class="quote-panel">
    <p>"Efficient AI systems are built by understanding both the algorithm and the machine."</p>
  </div>
</section>

<section class="contact-strip">
  <div>
    <p class="home-card__label">Contact</p>
    <h2>I am interested in scalable AI systems, LLM infrastructure, and collaboration across research and engineering.</h2>
  </div>
  <a class="home-pill" href="mailto:yj367@cam.ac.uk">yj367@cam.ac.uk</a>
</section>
