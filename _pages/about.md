---
permalink: /
title: "Zhiyuan Ouyang"
author_profile: false
landing_page: true
excerpt: "Ph.D. student in Computational Mathematics, working on generative modeling and AI systems."
redirect_from:
  - /about/
  - /about.html
---

<div class="homepage">
  <section class="home-intro" aria-labelledby="home-name">
    <header class="home-intro__heading">
      <h1 class="home-name" id="home-name">Zhiyuan Ouyang</h1>
      <p class="home-role">Ph.D. student · Computational Mathematics</p>
    </header>
    <div class="home-intro__text">
      <p>
        I am a second-year Ph.D. student at
        <a href="https://math.ecnu.edu.cn/">East China Normal University</a> and
        <a href="https://www.sii.edu.cn/">Shanghai Innovation Institute</a>,
        co-supervised by
        <a href="https://math.ecnu.edu.cn/~xyzhang/">Xiangyun Zhang</a> and
        <a href="https://thinklab.sjtu.edu.cn/">Junchi Yan</a>.
      </p>
      <p>
        My research focuses on generative models, with an emphasis on theoretical understanding,
        generalization, and efficient, controllable generation. I also work on distributed training
        and AI deployment, and explore on-chain execution infrastructure and prediction markets.
      </p>
      <nav class="home-links" aria-label="Contact and profiles">
        <a href="mailto:zhiyuanouyang@sii.edu.cn">Email</a>
        <a href="https://github.com/AdrainOY" target="_blank" rel="noopener noreferrer">GitHub</a>
        <a href="{{ '/resume_en.pdf' | relative_url }}">CV</a>
        <a href="https://www.xiaohongshu.com/user/profile/63c9827c000000002702bf18" target="_blank" rel="noopener noreferrer">Xiaohongshu</a>
        <a href="https://www.zhihu.com/people/sakamoto-sama" target="_blank" rel="noopener noreferrer">Zhihu</a>
        <a href="https://x.com/Adrain_OY" target="_blank" rel="noopener noreferrer">X</a>
      </nav>
    </div>
    <div class="home-intro__photo">
      <img class="home-photo" src="{{ '/images/photo.jpg' | relative_url }}" alt="Zhiyuan Ouyang" width="564" height="834">
    </div>
  </section>

  <section class="home-section" aria-labelledby="home-news">
    <h2 class="home-section__title" id="home-news">News</h2>
    <ul class="home-news">
      <li>
        <time datetime="2026-06">Jun 2026</time>
        <span>Open-sourced <a href="https://github.com/AdrainOY/MimicPolymarket">MimicPolymarket</a>, an on-chain execution router for Polymarket.</span>
      </li>
      <li>
        <time datetime="2026-05">May 2026</time>
        <span><a href="https://icml.cc/virtual/2026/poster/66180">Primal-Spectral Generative Modeling</a> accepted at ICML 2026.</span>
      </li>
      <li>
        <time datetime="2026-03">Mar 2026</time>
        <span>Received the National Scholarship for PhD Students in China.</span>
      </li>
      <li>
        <time datetime="2025">2025</time>
        <span>Published work on thyroid nodule diagnosis in <em>Computational Biology and Chemistry</em>.</span>
      </li>
    </ul>
  </section>

  <section class="home-section" aria-labelledby="home-publications">
    <h2 class="home-section__title" id="home-publications">Publications</h2>
    <div class="home-section__content">
      <div class="home-entry">
        <div class="home-entry__main">
          <a class="home-entry__title" href="{{ '/publication/2026-05-01-primal-spectral-generative-modeling.html' | relative_url }}">Primal-Spectral Generative Modeling: Fast Analytical Generation via Pseudoinverse Levy Inversion</a>
          <p class="home-entry__meta">Zhiyuan Ouyang et al. · First author<br><em>ICML 2026</em></p>
        </div>
        <div class="home-entry__side">2026</div>
      </div>
      <div class="home-entry">
        <div class="home-entry__main">
          <a class="home-entry__title" href="https://doi.org/10.1016/j.compbiolchem.2025.108572">A Novel Network for Resolving Subjective Masking Differences and Accurate Thyroid Nodule Diagnosis</a>
          <p class="home-entry__meta">Zhiyuan Ouyang et al. · First author<br><em>Computational Biology and Chemistry</em></p>
        </div>
        <div class="home-entry__side">2025</div>
      </div>
      <div class="home-entry">
        <div class="home-entry__main">
          <a class="home-entry__title" href="https://doi.org/10.1080/03610918.2023.2300362">Model Detection for Grey Forecasting Model with Polynomial Term</a>
          <p class="home-entry__meta">Zhiyuan Ouyang et al. · First author<br><em>Communications in Statistics</em></p>
        </div>
        <div class="home-entry__side">2023</div>
      </div>
      <a class="home-more" href="{{ '/publications/' | relative_url }}">All publications <span aria-hidden="true">↗</span></a>
    </div>
  </section>

  <section class="home-section" aria-labelledby="home-experience">
    <h2 class="home-section__title" id="home-experience">Experience</h2>
    <div class="home-section__content">
      <div class="home-entry">
        <div class="home-entry__main">
          <a class="home-entry__title" href="https://github.com/AdrainOY/MimicPolymarket">MimicPolymarket</a>
          <p class="home-entry__meta">Independent open-source project</p>
          <p>Execution router with multi-wallet routing, risk control, order aggregation, and MongoDB-backed state persistence.</p>
        </div>
        <div class="home-entry__side">2026–Present</div>
      </div>
      <div class="home-entry">
        <div class="home-entry__main">
          <h3 class="home-entry__title">Baizhi Xunlian Technology Co., Ltd.</h3>
          <p class="home-entry__meta">Head of AI Department</p>
          <p>Led controllable image generation pipelines, deployment planning, and team-level engineering standards.</p>
        </div>
        <div class="home-entry__side">2023–2024</div>
      </div>
    </div>
  </section>

  <section class="home-section" aria-labelledby="home-skills">
    <h2 class="home-section__title" id="home-skills">Technical skills</h2>
    <dl class="home-skills">
      <div><dt>Programming</dt><dd>Python, TypeScript, Rust, C++</dd></div>
      <div><dt>Deep learning</dt><dd>PyTorch, JAX, Diffusers, TensorBoard</dd></div>
      <div><dt>Distributed training</dt><dd>Slurm, DDP, scheduling and performance tuning</dd></div>
      <div><dt>Web3 infrastructure</dt><dd>Ethers.js, Viem, Polymarket CLOB SDK, Account Abstraction, MongoDB, Docker</dd></div>
    </dl>
  </section>

  <p class="home-updated">Last updated <time datetime="2026-06">June 2026</time></p>
</div>
