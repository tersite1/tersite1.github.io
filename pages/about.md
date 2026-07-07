---
layout: page
title: About
permalink: /about/
weight: 1
---

<style>
/* ─────────────────────────── Personal Project Cards ───────────────── */
.main-personal-projects { margin: 2rem 0; display: block; }
.personal-project-row {
  display: grid; grid-template-columns: 1fr; gap: 3rem; margin-top: 1.5rem;
  max-width: 1200px; margin-left: auto; margin-right: auto; width: 95%;
}
.personal-project-card {
  padding: 3rem; background-color: #f8f9fa; border-radius: 1rem; border: 1px solid #e9ecef;
  text-align: center; transition: transform 0.3s ease, box-shadow 0.3s ease;
  width: 100%; max-width: 1200px; margin: 0 auto 3rem auto; box-sizing: border-box;
}
@media (hover: hover) and (pointer: fine) {
  .personal-project-card:hover { transform: translateY(-3px); box-shadow: 0 6px 25px rgba(0,0,0,0.15); }
}
.project-name { font-size: 1.6rem; font-weight: 600; color: #043361; margin-bottom: 1rem; }
.project-description {
  font-size: 1.2rem; color: #6c757d; margin-bottom: 1.5rem; line-height: 1.6;
  max-width: 800px; margin-left: auto; margin-right: auto;
}
.project-buttons { display: flex; justify-content: center; gap: 1rem; margin-bottom: 1.5rem; flex-wrap: wrap; }
.project-button, .download-button, .instagram-button, .ios-button, .news-button {
  display: inline-block; padding: 0.8rem 1.5rem; border-radius: 0.5rem; font-size: 1rem;
  font-weight: 600; text-decoration: none !important; transition: all 0.3s ease; border: 2px solid transparent;
  min-width: 140px; text-align: center; box-sizing: border-box; height: 48px; line-height: 1.2;
  background-color: #043361; color: white !important; border-color: #043361;
}
@media (hover: hover) and (pointer: fine) {
  .project-button:hover, .download-button:hover, .instagram-button:hover, .ios-button:hover, .news-button:hover {
    background-color: #069; border-color: #069; transform: translateY(-1px); box-shadow: 0 3px 12px rgba(0,0,0,0.25);
  }
}
.project-video-container {
  width: 100%; max-width: 900px; height: 350px; border-radius: 0.8rem; overflow: hidden;
  box-shadow: 0 4px 15px rgba(0,0,0,0.12); margin: 0 auto; position: relative; background-color: #000;
}
.project-video-container iframe { width: 100%; height: 100%; border: none; position: absolute; top: 0; left: 0; object-fit: cover; }
.project-image-container { width: 100%; max-width: 900px; margin: 0 auto; border-radius: 0.8rem; overflow: hidden; box-shadow: 0 4px 15px rgba(0,0,0,0.12); }
.project-image-container img { width: 100%; display: block; }
@media (prefers-color-scheme: dark) {
  .project-name { color: rgb(62, 183, 240); }
  .project-description { color: #b0b3b8; }
  .project-button, .download-button, .instagram-button, .ios-button, .news-button {
    background-color: rgb(62, 183, 240); color: #000 !important; border-color: rgb(62, 183, 240);
  }
}
/* ─────────────────────────── Publications ───────────────── */
.pub-list { margin-top: 1rem; }
.pub-item { display: flex; flex-wrap: wrap; gap: 1rem; align-items: center; margin-bottom: 1.4rem; }
.pub-thumb { position: relative; flex: 0 0 270px; }
.pub-thumb img { width: 270px; height: 123px; object-fit: cover; border-radius: 8px; box-shadow: 3px 3px 6px #888; }
.pub-badge { position: absolute; top: 8px; left: 8px; background: #002D72; color: #fff; font-size: .72rem; font-weight: 700; padding: .1rem .55rem; border-radius: 4px; }
.pub-body { flex: 1; min-width: 260px; }
.pub-title { font-weight: 700; }
.pub-venue { color: #555; }
.pub-links { margin-top: .3rem; }
.pub-links a { display: inline-block; color: #000; border: 1px solid #000; padding: .05rem .5rem; margin-right: .35rem; border-radius: 3px; font-size: .8rem; text-decoration: none !important; }
.pub-links a:hover { color: #002D72; border-color: #002D72; }
@media (max-width: 640px) { .pub-thumb, .pub-thumb img { width: 100%; flex-basis: 100%; } }
@media (prefers-color-scheme: dark) { .pub-links a { color: #fff; border-color: #fff; } .pub-venue { color: #b0b3b8; } }
</style>

## About Me

I am an M.S. student at KAIST, currently in the [Computational Intelligence Laboratory](https://cilabs.kaist.ac.kr/) (Prof. Changick Kim). I earned a B.S. in Civil Engineering from Yonsei University, Seoul, and was a student intern at Seoul National University, working in both the [Vehicle Intelligence Laboratory](https://vi.snu.ac.kr/) (Prof. Seungwoo Seo) and the [Autonomous Robot Intelligence Laboratory](https://vi.snu.ac.kr/) (Prof. Seongwoo Kim). I worked as an AI Engineer at [Stellarvision](https://stellarvision.co.kr/en/), a satellite imagery startup. Also, I am founder of [XYZ Innovation](https://www.linkedin.com/company/xyzinnovation), a company focused on applying 3D Vision and Drone technologies to real-world challenges. These combined experiences have shaped my research interests.

## Education
* **[Present]** : M.S. in Electrical Engineering @KAIST, CILAB
* **[Feb. 2025]** : B.S. in  Civil Engineering, AI Convergence @Yonsei University

## Research Interests

* **AIGC(AI Generated Contents) Detection:** Developing robust detection models for wild datasets (TikTok, YouTube Shorts, etc.) with focus on generalization across diverse AI-generated content types and social media platforms. [[arxiv'25]](https://arxiv.org/abs/2506.17592)
* **Spiking Neural Networks:** Investigating model compression and efficiency optimization using SNN architectures to reduce the performance gap between spiking and artificial neural networks while maintaining computational efficiency.[[IEIE'25(Best Paper)]](https://www.linkedin.com/posts/jadenjang_neuromorphiccomputing-visiontransformer-ai-activity-7348206102817189889-3Umd?utm_source=share&utm_medium=member_desktop&rcm=ACoAAEruz8kBUKyMdf_xZCXG6yIDp-BUSGMewOA)[[arxiv'25]](https://arxiv.org/abs/2508.01646) 
* **3D Digital Twin:** Creating comprehensive digital replicas by integrating UAV technology and remote sensing data for climate research applications, environmental monitoring, and atmospheric data analysis.
[[IEIE'24]](https://www.dbpia.co.kr/journal/articleDetail?nodeId=NODE11890368) 


## Work Experience
* **[Jul. 2024 ~ Current]:** CTO @ [IDOLL Robotics](https://idoll.love/)
* **[Jul. 2024 ~ Feb.2026]:** CTO @ [Dailymeal](https://www.dailymeal.co.kr/)
* **[Jul. 2024 ~ Feb. 2025]:** AI Engineer @ [Stellarvision Inc.](https://stellarvision.co.kr/en/)


## Projects
* **[Apr. 2026 ~ Present]:** ETRI - Multimodal AI-based Digital Twin Model Automatic Generation Technology
* **[Mar. 2026 ~ Present]:** NCSL - Development of Safety Evaluation Technology for Multimodal Generative AI
* **[Apr. 2025 ~ Present]:** IITP - Technologies for On-Device AI Inter-Object Collaborative Behavior
* **[Apr. 2025 ~ Jul.2026]:** LIG Nex1 - Underwater sonar image enhancement
* **[Jun. 2025 ~ Apr. 2026]:** SOOMVI - Precise landing technology for drones
* **[Jul. 2024 ~ Feb. 2025]:** Stellarvision Inc - Sensor Fusion(SAR, LiDAR) UAV based Digital Twin Platform for landslides


## News
* **[Nov. 2025]** I took 9th place on [흑백개발자:the해커톤](https://thehackathon.org/)!
* **[Nov. 2025]** DepthViz is hitting #36 on iOS chart! 
* **[Sep. 2025]** Yonsei Drone awarded Joint 1st prize at [23th AAM Tech Challenge](https://www.knnews.co.kr/m2/mView.php?idxno=1469998)!
* **[Aug. 2025]** I nominated as winner of IPESK next generation engineering researcher award.
* **[Jun. 2025]** XYZ Innovation Won World Robo Fest 2025!
* **[Jun. 2025]** I awarded the Governor's prize of Chungcheongnamdo! 
* **[Jun. 2025]** I awarded Best Paper at IEIE 2025 summer Conference.
* **[May. 2025]**: I have joined [GLG (Gerson Lehrman Group)](https://glginsights.com/ko/) as an advisory board member.

## Publications

<div class="pub-list">
{% for link in site.data.publications.main %}
  <div class="pub-item">
    {% if link.image %}
    <div class="pub-thumb">
      <img src="{{ link.image | replace: './', '/' }}" alt="" />
      {% if link.conference_short %}<span class="pub-badge">{{ link.conference_short }}</span>{% endif %}
    </div>
    {% endif %}
    <div class="pub-body">
      <div class="pub-title">{{ link.title }}</div>
      <div class="pub-authors">{{ link.authors }}</div>
      <div class="pub-venue"><em>{{ link.conference }}</em></div>
      <div class="pub-links">
        {% if link.pdf %}<a href="{{ link.pdf }}" target="_blank">PDF</a>{% endif %}
        {% if link.code %}<a href="{{ link.code }}" target="_blank">Code</a>{% endif %}
        {% if link.page %}<a href="{{ link.page }}" target="_blank">Project Page</a>{% endif %}
        {% if link.bibtex %}<a href="{{ link.bibtex }}" target="_blank">BibTex</a>{% endif %}
        {% if link.notes %}<strong> <i style="color:#e74d3c">{{ link.notes }}</i></strong>{% endif %}
      </div>
    </div>
  </div>
{% endfor %}
</div>


## Patents

* *System and Method for Inspecting Structural Defects of Buildings using Dual Drones Equipped with X-ray*, **Minsuk Jang**, Deo Akash, Gupta Amar Prasad  (KR Patent Application 10-2026-0050382)
* *Apparatus and Method for Interior Simulation Using World Model Generation Based on Point Cloud and Diffusion Model*, **Minsuk Jang** (KR Patent Application 10-2026-0010171)
* *AI-Based Integrated Management System and Method for Subscription Food Service Performing Backward Production Scheduling based on Delivery Time Window and Dynamic Route Optimization*, **Minsuk Jang** (KR Patent Application 10-2026-0010717)
* *Apparatus and Method for AI-Based Commercial Area Prediction Using Structuring of Unstructured External Text and Spatio-temporal Impact Propagation*, **Minsuk Jang** (KR Patent Application 10-2026-0010395)
* *LiDAR Micro Mobile Mapping System*, **Minsuk Jang** (KR Patent Application 10-2024-0130327)
* *Forest Carbon Sequestration Analysis System and Method*, **Minsuk Jang** (KR Patent Application 10-2024-0153987)
* *Vertically Takeoff and Landing Unmanned Aerial Vehicle with Adjustable Center of Gravity*, Minjun Kim, Junkyoo Park, Jungha Wang, **Minsuk Jang** (KR Patent Application 10-2024-0177539)
* *Method for Generating a High-Precision 3D Model from a Digital Elevation Model*, **Minsuk Jang**, Seungchul Lee (KR Patent Application 10-2024-0165631)
* *Machine Learning Clustering-Based Method for Algal Bloom Detection in Satellite Imagery*, **Minsuk Jang**, Seungchul Lee (KR Patent Application 10-2024-0165632)


## Awards & Honors
* **NEXT Generation Engineering Researcher** @ IPESK, **Sep. 2025**
* **Joint 1st Prize – [23th AAM Tech Challenge](https://me.yonsei.ac.kr/me/community/news.do?mode=view&articleNo=456983)** @ KASA, **Sep. 2025**
* **Grand Prize (Governor's Award) – World Robo Festa 2025** @ Chungcheongnam-do Provincial Government, **Jun. 2025**
* **Best Paper Award – IEIE 2025 Summer Conference**, **May 2025**
* **Seoul Mayor’s Award – Seoul Drone Utilization Competition** @ Seoul Metropolitan Government, **Dec. 2024**
* **Excellence Prize – Asan Nanum Foundation Startup Competition** @ Asan Nanum Foundation, **Oct. 2024**
* **Grand Prize (Governor’s Award) – Jeju Satellite Data Challenge** @ Jeju Provincial Government, **Sep. 2024**
* Winner – Physical AI Hackathon @Cheonan, **May. 2025**
* Winner – ICEE Challenge 2024 @ Yonsei University, **Jul. 2024**
* Winner – Yonsei Student Council Idea Competition @ Yonsei University, **Jul. 2024**
* Winner – Convergence Social Problem Solving Competition @ Yonsei University, **Jan. 2024**
* Winner – 2nd Command Center Drone Challenge @ Republic of Korea Army (ROKA)
* Winner – Gyeonggi ESG Hackathon @ Gyeonggi-do Provincial Council
* Winner – KSCE Civil Engineering Model Competition @ Korea Society of Civil Engineers


## Academic Services

ICIP 2026 Conference Reviewer 

IEEE TCSVT Journal Reviewer

AAAI 2026 Conference Reviewer


## Personal Projects

<div class="main-personal-projects">
  <div class="personal-project-row">

    <!-- DepthViz -->
    <div class="personal-project-card">
      <div class="project-name"><strong>DepthViz</strong></div>
      <div class="project-description">A LiDAR scanner working on iPhone</div>
      <div class="project-buttons">
        <a href="https://github.com/tersite1/DepthViz" target="_blank" class="project-button">Project Page</a>
        <a href="https://apps.apple.com/app/depthviz/id6754522044" target="_blank" class="download-button ios-button">Download&nbsp;(iOS)</a>
      </div>
      <div class="project-video-container">
        <iframe src="https://www.youtube.com/embed/jtFA_WKWBDY" title="DepthViz Demo" frameborder="0" allowfullscreen></iframe>
      </div>
    </div>

    <!-- Yonsei Drone -->
    <div class="personal-project-card">
      <div class="project-name"><strong>Yonsei&nbsp;Drone</strong></div>
      <div class="project-description">I'm still in Yonsei Drone, Wow!</div>
      <div class="project-buttons">
        <a href="https://yonseidrone.notion.site/a9c169ae021445d0a5d95a083d69b1ad" target="_blank" class="project-button">Project Page</a>
        <a href="https://www.instagram.com/yonsei_drone/" target="_blank" class="instagram-button">Instagram</a>
      </div>
      <div class="project-video-container">
        <iframe src="https://www.youtube.com/embed/iyjVVylZR5Q" title="Yonsei Drone Demo" frameborder="0" allowfullscreen></iframe>
      </div>
    </div>

    <!-- GreenWave -->
    <div class="personal-project-card">
      <div class="project-name"><strong>GreenWave</strong></div>
      <div class="project-description">I awarded Big Prize in Jeju! I beat Coupang and KAKAO, How?</div>
      <div class="project-buttons">
        <a href="https://github.com/tersite1/GreenWave" target="_blank" class="project-button">Project Page</a>
        <a href="https://search.naver.com/search.naver?where=news&query=Fluxmap+녹조" target="_blank" class="news-button">News</a>
      </div>
      <div class="project-image-container">
        <img src="/assets/img/news.jpg" alt="GreenWave 프로젝트 뉴스 이미지">
      </div>
    </div>

    <!-- World Robo Festa -->
    <div class="personal-project-card">
      <div class="project-name"><strong>World Robo Festa</strong></div>
      <div class="project-description">XYZ Innovation Won World Robo Festa 2025.</div>
      <div class="project-buttons">
        <a href="https://www.linkedin.com/company/xyzinnovation" target="_blank" class="project-button">Project Page</a>
        <a href="https://search.naver.com/search.naver?ssc=tab.news.all&where=news&sm=tab_jum&query=%EC%9B%94%EB%93%9C%EB%A1%9C%EB%B3%B4%ED%8E%98%EC%8A%A4%ED%83%80+%EC%9E%A5%EB%AF%BC%EC%84%9D" target="_blank" class="news-button">News</a>
      </div>
      <div class="project-image-container">
        <img src="/assets/img/xuz.png" alt="World Robo Festa 이미지">
      </div>
    </div>

    <!-- MAST -->
    <div class="personal-project-card">
      <div class="project-name"><strong>MAST</strong></div>
      <div class="project-description">MAST has been featured in the news! (From 0:51)</div>
      <div class="project-buttons">
        <a href="https://arxiv.org/abs/2605.05895" target="_blank" class="project-button">arXiv</a>
        <a href="https://github.com/tersite1" target="_blank" class="project-button">GitHub</a>
        <a href="https://news.kbs.co.kr/news/mobile/view/view.do?ncd=8561338" target="_blank" class="news-button">News</a>
      </div>
      <div class="project-image-container">
        <img src="/assets/img/mast_news.png" alt="MAST 프로젝트 뉴스 보도 이미지">
      </div>
    </div>

  </div>
</div>
