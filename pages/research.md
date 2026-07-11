---
layout: page
title: Research
permalink: /research/
weight: 2
---

<style>
.rvision {
  font-size: 1.05rem; line-height: 1.7; color: #2c2c2c; background: #f8f9fa;
  border-left: 4px solid #043361; border-radius: .6rem; padding: 1rem 1.25rem; margin: 1rem 0 2.2rem;
}
.rtheme { display: flex; gap: 1.4rem; align-items: flex-start; margin: 1.6rem 0 2.2rem; }
.rtheme-fig { flex: 0 0 200px; }
.rtheme-fig img { width: 200px; height: 140px; object-fit: cover; border-radius: .6rem; box-shadow: 0 3px 12px rgba(0,0,0,.12); }
.rtheme-body { flex: 1; }
.rtheme-body h3 { margin: 0 0 .4rem; font-size: 1.2rem; font-weight: 700; color: #043361; }
.rtheme-num { font-family: Georgia, serif; font-weight: 700; color: #9aa3b0; margin-right: .4rem; }
.rtheme-body p { margin: 0 0 .5rem; line-height: 1.6; color: #3a3a3a; }
.rtheme-links a { font-size: .85rem; margin-right: .8rem; white-space: nowrap; }
@media (max-width: 640px) { .rtheme { flex-direction: column; } .rtheme-fig, .rtheme-fig img { width: 100%; } .rtheme-fig img { height: 180px; } }
@media (prefers-color-scheme: dark) {
  .rvision { background: #1e2024; border-left-color: #5aa9ff; color: #d7dade; }
  .rtheme-body p { color: #c7cad0; }
  .rtheme-body h3 { color: #7fb4ff; }
}
.r-divider { border: none; border-top: 2px solid #e5e7eb; margin: 2.6rem 0 1.4rem; }
.r-interest { font-size: 1.02rem; color: #4a4a4a; margin: 0 0 1.4rem; }
@media (prefers-color-scheme: dark) { .r-divider { border-top-color: #2c2f33; } .r-interest { color: #c7cad0; } }
</style>

# **Research**

<p class="rvision">
I'm an AI researcher with a civil engineering background. My work spans <strong>3D perception, agentic AI,
and AI safety</strong>, and I care most about research that leaves the lab and holds up in the real world.
I like to build end to end, from field sensing systems to the learning algorithms behind them.
</p>

## Research Directions

<div class="rtheme">
  <div class="rtheme-fig"><img src="/assets/img/koni.png" alt="3D reconstruction" /></div>
  <div class="rtheme-body">
    <h3><span class="rtheme-num">01</span>3D (Gaussian Splatting, LiDAR)</h3>
    <p>Real-time 3D reconstruction from LiDAR and cameras: LiDAR-inertial odometry, mobile mapping, and
    neural representations such as NeRF and <strong>3D Gaussian Splatting</strong>. I shipped these ideas as
    <strong>DepthViz</strong>, an on-device iOS LiDAR-SLAM scanner, and study lightweight odometry and
    open-vocabulary 3D scene understanding for robots.</p>
    <div class="rtheme-links">
      <a href="https://github.com/tersite1/DepthViz" target="_blank">DepthViz ↗</a>
      <a href="/publications/">Related papers ↗</a>
    </div>
  </div>
</div>

<div class="rtheme">
  <div class="rtheme-fig"><img src="/assets/img/mate.png" alt="Agentic AI" /></div>
  <div class="rtheme-body">
    <h3><span class="rtheme-num">02</span>Agentic AI</h3>
    <p>Agents that act reliably in the real world: mobile GUI agents, multi-agent orchestration, and
    on-device collaborative behavior. My work on <strong>MATE (Mobile Agent Trustworthy Execution)</strong>
    makes agent actions safe and efficient, and I bring the same ideas to ontology-based home robots and
    multi-user memory control.</p>
    <div class="rtheme-links">
      <a href="/publications/">Related papers ↗</a>
    </div>
  </div>
</div>

<div class="rtheme">
  <div class="rtheme-fig"><img src="/assets/img/aigv.png" alt="AI safety" /></div>
  <div class="rtheme-body">
    <h3><span class="rtheme-num">03</span>AI Safety</h3>
    <p>Making AI systems trustworthy: safety evaluation for multimodal generative AI, robust detection of
    AI-generated images and video, and efficient, verifiable inference. This line runs from agent-level
    safety to content-level trust, connecting my work on generative-content detection and reliable
    execution.</p>
    <div class="rtheme-links">
      <a href="/publications/">Related papers ↗</a>
    </div>
  </div>
</div>

<hr class="r-divider" />

## Real-World Problems

<p class="r-interest">More than any single method, this is the area I care about most: research that leaves the lab and solves an actual problem in the field.</p>

<div class="rtheme">
  <div class="rtheme-fig"><img src="/assets/img/tgrs.png" alt="Real-world remote sensing" /></div>
  <div class="rtheme-body">
    <p>Detection-driven <strong>super-resolution for sonar imagery (IEEE TGRS)</strong> for mine-like
    object detection, UAV SAR and LiDAR digital twins for landslide and disaster mapping, and remote
    sensing for environmental monitoring. I want work where the benchmark is the real world, not just a dataset.</p>
    <div class="rtheme-links">
      <a href="/publications/">Related papers ↗</a>
      <a href="/projects/">Projects ↗</a>
    </div>
  </div>
</div>

## Funded Research Projects

* **ETRI** — Multimodal AI-based Digital Twin Model Automatic Generation *(Apr. 2026 – Present)*
* **NCSL** — Safety Evaluation Technology for Multimodal Generative AI *(Mar. 2026 – Present)*
* **IITP** — On-Device AI Inter-Object Collaborative Behavior *(Apr. 2025 – Present)*
* **LIG Nex1** — Underwater Sonar Image Enhancement *(Apr. 2025 – Jul. 2026)*
* **SOOMVI** — Precise Landing Technology for Drones *(Jun. 2025 – Apr. 2026)*
* **Stellarvision** — Sensor-Fusion (SAR, LiDAR) UAV Digital Twin Platform for Landslides *(Jul. 2024 – Feb. 2025)*

See the full [Publications](/publications/) list for papers.
