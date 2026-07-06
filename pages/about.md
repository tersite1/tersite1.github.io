---
layout: page
title: About
permalink: /about/
weight: 1
---

<style>
.about-avatar {
  display: block; width: 180px; height: 180px; object-fit: cover; border-radius: 50%;
  margin: 0.5rem auto 1.5rem auto; box-shadow: 0 4px 18px rgba(0,0,0,0.18);
}
.about-links { display: flex; gap: .55rem; flex-wrap: wrap; margin: 0.4rem 0 1.6rem; }
.about-links a {
  display: inline-block; padding: .4rem .9rem; border-radius: .5rem; font-weight: 600; font-size: .9rem;
  text-decoration: none !important; border: 2px solid #043361; color: #043361 !important; transition: all .2s;
}
.about-links a:hover { background: #043361; color: #fff !important; }
.highlights { list-style: none; padding: 0; margin: 1rem 0 2rem; }
.highlights li {
  padding: .7rem 1rem; margin-bottom: .6rem; border: 1px solid #e9ecef; border-left: 4px solid #043361;
  border-radius: .5rem; background: #f8f9fa; line-height: 1.5;
}
.exp-list { display: flex; flex-direction: column; gap: 0.9rem; margin: 1.2rem 0 2rem; }
.exp-item {
  display: flex; justify-content: space-between; align-items: baseline; gap: 1rem;
  padding: 0.9rem 1.25rem; border: 1px solid #e9ecef; border-left: 4px solid #043361;
  border-radius: 0.6rem; background: #f8f9fa; transition: transform .2s ease, box-shadow .2s ease;
}
.exp-item:hover { transform: translateY(-2px); box-shadow: 0 4px 16px rgba(0,0,0,0.1); }
.exp-role { font-weight: 700; color: #043361; }
.exp-org  { color: #333; text-decoration: none; border-bottom: 1px dotted #999; }
.exp-period { color: #6c757d; font-size: .92rem; white-space: nowrap; }
@media (max-width: 600px) { .exp-item { flex-direction: column; gap: .25rem; } .exp-period { white-space: normal; } }
@media (prefers-color-scheme: dark) {
  .highlights li, .exp-item { background: #1e2024; border-color: #2c2f33; border-left-color: #5aa9ff; }
}
</style>

<img class="about-avatar" src="/assets/img/minsuk0.png" alt="Minsuk Jang" />

## About Me

I am an M.S. student at KAIST in the [Computational Intelligence Laboratory](https://cilabs.kaist.ac.kr/) (Prof. Changick Kim), with a B.S. in Civil Engineering (AI Convergence) from Yonsei University. I am driven by **real-world applications and solving real problems**. I founded and exited [DepthViz](https://github.com/tersite1/DepthViz), an on-device iOS LiDAR-SLAM app acquired by a construction firm, and as an AI Engineer at [Stellarvision](https://stellarvision.co.kr/en/) I generated 3D digital twins from **drone-mounted SAR imagery** for landslide prevention — exhibited at **CES 2025**.

My work centers on **LiDAR-inertial SLAM, mobile mapping, UAV remote sensing, and as-built 3D modeling** for construction and infrastructure. I hold **nine patents** and an ultralight-aircraft pilot license, and I am currently CTO of [IDOLL Robotics](https://idoll.love/). My long-term goal is to become a professor who advances autonomous robotic sensing and trains the next generation of scholars.

<div class="about-links">
  <a href="/assets/files/CV_minsuk.pdf" target="_blank">CV</a>
  <a href="https://scholar.google.com/citations?user=2ARVuOcAAAAJ&hl=ko" target="_blank">Google Scholar</a>
  <a href="https://github.com/tersite1" target="_blank">GitHub</a>
  <a href="https://www.linkedin.com/in/jadenjang/" target="_blank">LinkedIn</a>
  <a href="mailto:minsukjang@kaist.ac.kr">Email</a>
</div>

## Highlights

<ul class="highlights">
  <li><strong>Shipped &amp; exited a field system</strong> — DepthViz, an on-device iOS LiDAR-SLAM scanner (#36 on the App Store), acquired by a construction firm.</li>
  <li><strong>9 patents</strong> in LiDAR mobile mapping, 3D reconstruction, and UAV systems (2 transferred). See <a href="/patents/">Patents</a>.</li>
  <li><strong>Drone-SAR 3D digital twin</strong> for landslide prevention, built with Neural Radiance Fields and exhibited at <strong>CES 2025</strong>.</li>
  <li><strong>Joint 1st Place, KASA AAM Tech Challenge</strong> and Governor's / Mayor's grand prizes in drone &amp; robotics competitions. See <a href="/awards/">Awards</a>.</li>
</ul>

## Education
* **M.S. in Electrical Engineering**, KAIST (Computational Intelligence Lab) — *Present*
* **B.S. in Civil Engineering (AI Convergence)**, Yonsei University — *Feb. 2025*

## Work Experience

<div class="exp-list">
  <div class="exp-item">
    <span><span class="exp-role">CTO</span> &middot; <a class="exp-org" href="https://idoll.love/" target="_blank">IDOLL Robotics</a></span>
    <span class="exp-period">Jul. 2024 – Present</span>
  </div>
  <div class="exp-item">
    <span><span class="exp-role">CTO</span> &middot; <a class="exp-org" href="https://www.dailymeal.co.kr/" target="_blank">Dailymeal</a></span>
    <span class="exp-period">Jul. 2024 – Feb. 2026</span>
  </div>
  <div class="exp-item">
    <span><span class="exp-role">AI Engineer</span> &middot; <a class="exp-org" href="https://stellarvision.co.kr/en/" target="_blank">Stellarvision Inc.</a></span>
    <span class="exp-period">Jul. 2024 – Feb. 2025</span>
  </div>
</div>

## Academic Services

Reviewer — IEEE TCSVT (Journal) · ICIP 2026 · AAAI 2026
