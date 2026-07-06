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
.rtheme-body p { margin: 0 0 .5rem; line-height: 1.6; color: #3a3a3a; }
.rtheme-links a { font-size: .85rem; margin-right: .8rem; white-space: nowrap; }
@media (max-width: 640px) { .rtheme { flex-direction: column; } .rtheme-fig, .rtheme-fig img { width: 100%; } .rtheme-fig img { height: 180px; } }
@media (prefers-color-scheme: dark) {
  .rvision { background: #1e2024; border-left-color: #5aa9ff; color: #d7dade; }
  .rtheme-body p { color: #c7cad0; }
}
</style>

# **Research**

<p class="rvision">
My research goal is <strong>autonomous robotic sensing and as-built 3D modeling for construction and
infrastructure</strong>: turning raw LiDAR, camera, and SAR streams into accurate, real-time 3D digital
twins that mobile robots and drones can act on in cluttered, unstructured field environments. I approach
this end-to-end — from field-deployed sensing systems to the learning and reconstruction algorithms behind them.
</p>

## Research Directions

<div class="rtheme">
  <div class="rtheme-fig"><img src="/assets/img/koni.png" alt="3D reconstruction" /></div>
  <div class="rtheme-body">
    <h3>3D Reconstruction &amp; Digital Twins for Infrastructure</h3>
    <p>LiDAR-inertial SLAM, mobile mapping, and neural reconstruction (NeRF / 3D Gaussian Splatting) for
    as-built modeling and scan-to-BIM. I shipped these ideas as <strong>DepthViz</strong>, an on-device iOS
    LiDAR-SLAM scanner, and study lightweight odometry and open-vocabulary 3D scene understanding for robots.</p>
    <div class="rtheme-links">
      <a href="https://github.com/tersite1/DepthViz" target="_blank">DepthViz ↗</a>
      <a href="/publications/">Related papers ↗</a>
    </div>
  </div>
</div>

<div class="rtheme">
  <div class="rtheme-fig"><img src="/assets/img/tgrs.png" alt="UAV remote sensing" /></div>
  <div class="rtheme-body">
    <h3>UAV Remote Sensing &amp; Sensor Fusion</h3>
    <p>Drone-mounted <strong>SAR + LiDAR</strong> fusion for 3D digital twins and disaster-risk mapping
    (landslide prevention), and detection-driven super-resolution for sonar imagery. This line connects
    field UAV systems — exhibited at <strong>CES 2025</strong> — with the perception algorithms that make
    their data usable.</p>
    <div class="rtheme-links">
      <a href="/projects/">Projects ↗</a>
      <a href="/publications/">Related papers ↗</a>
    </div>
  </div>
</div>

<div class="rtheme">
  <div class="rtheme-fig"><img src="/assets/img/gaussianization.png" alt="Efficient and trustworthy AI" /></div>
  <div class="rtheme-body">
    <h3>Efficient &amp; Trustworthy Perception</h3>
    <p>Spiking Neural Networks for efficient on-device inference, and robust detection of AI-generated
    content. These give me the deep-learning and efficiency foundation needed to run perception on
    resource-constrained robots and drones.</p>
    <div class="rtheme-links">
      <a href="/publications/">Related papers ↗</a>
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
