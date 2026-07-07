---
layout: default
permalink: /
---

<style>
.hero { text-align: center; max-width: 780px; margin: 2.2rem auto 3rem; padding: 0 1rem; }
.hero-avatar { width: 168px; height: 168px; object-fit: cover; border-radius: 50%; box-shadow: 0 6px 22px rgba(0,0,0,.18); margin-bottom: 1.1rem; }
.hero h1 { font-size: 2.1rem; font-weight: 800; margin: .2rem 0 .15rem; }
.hero-sub { color: #5c6066; font-size: 1.05rem; margin-bottom: .2rem; }
.hero-statement { font-size: 1.1rem; color: #2c2c2c; line-height: 1.65; margin: 1.1rem auto 1.4rem; max-width: 650px; }
.hero-stats { display: flex; gap: 1rem; justify-content: center; flex-wrap: wrap; margin: 1.4rem 0 0.4rem; }
.hero-stat { background: #f8f9fa; border: 1px solid #e9ecef; border-radius: .85rem; padding: 1rem 1.2rem; min-width: 165px; max-width: 220px; }
.hero-stat .num { font-size: 1.35rem; font-weight: 800; color: #043361; }
.hero-stat .lbl { font-size: .82rem; color: #5c6066; margin-top: .25rem; line-height: 1.4; }
.hero-links { display: flex; gap: .6rem; justify-content: center; flex-wrap: wrap; margin-top: 1.6rem; }
.hero-btn { display: inline-flex; align-items: center; gap: .4rem; padding: .55rem 1.15rem; border-radius: .6rem; font-weight: 600; font-size: .95rem; text-decoration: none !important; border: 2px solid #043361; color: #043361 !important; transition: all .2s ease; }
.hero-btn:hover { background: #043361; color: #fff !important; }
.hero-btn.primary { background: #043361; color: #fff !important; }
.hero-btn.primary:hover { background: #06529c; border-color: #06529c; }
@media (prefers-color-scheme: dark) {
  .hero-stat { background: #1e2024; border-color: #2c2f33; }
  .hero-statement { color: #d7dade; }
  .hero-btn { border-color: #5aa9ff; color: #5aa9ff !important; }
  .hero-btn.primary { background: #2b6cb0; color: #fff !important; border-color: #2b6cb0; }
}
.uc-banner { max-width: 820px; margin: 1.6rem auto 0; padding: 1.5rem 1.2rem; text-align: center;
  background: repeating-linear-gradient(45deg, #fff8e1, #fff8e1 16px, #fdecc8 16px, #fdecc8 32px);
  border: 3px dashed #e0a800; border-radius: 1rem; }
.uc-banner .uc-title { font-size: 2rem; font-weight: 900; color: #8a5a00; letter-spacing: .03em; margin: 0; line-height: 1.2; }
.uc-banner .uc-sub { font-size: 1rem; color: #7a5a00; margin: .5rem 0 0; }
@media (prefers-color-scheme: dark) {
  .uc-banner { background: repeating-linear-gradient(45deg, #2a2410, #2a2410 16px, #35301a 16px, #35301a 32px); border-color: #b8860b; }
  .uc-banner .uc-title { color: #ffd466; }
  .uc-banner .uc-sub { color: #d9c48a; }
}
/* DepthViz highlight */
.depthviz-card {
  max-width: 640px; margin: 2rem auto 0; padding: 1.6rem 1.5rem; text-align: center;
  background: linear-gradient(135deg, #eef4ff, #f8f9fa); border: 1px solid #d9e2f0;
  border-radius: 1.1rem; box-shadow: 0 6px 24px rgba(4,51,97,0.08);
}
.dv-top { display: flex; gap: .45rem; justify-content: center; flex-wrap: wrap; margin-bottom: .6rem; }
.dv-tag { font-size: .72rem; font-weight: 700; color: #043361; background: #fff; border: 1px solid #d9e2f0; border-radius: 999px; padding: .14rem .6rem; }
.dv-title { font-size: 1.7rem; font-weight: 800; color: #043361; margin: .1rem 0 .5rem; }
.dv-desc { font-size: .98rem; color: #3a4654; line-height: 1.6; margin: 0 auto 1.1rem; max-width: 520px; }
.dv-btns { display: flex; gap: .6rem; justify-content: center; flex-wrap: wrap; }
.dv-btn { display: inline-flex; align-items: center; gap: .35rem; padding: .55rem 1.3rem; border-radius: .6rem; font-weight: 700; font-size: .95rem; text-decoration: none !important; border: 2px solid #043361; color: #043361 !important; transition: all .2s ease; }
.dv-btn:hover { background: #043361; color: #fff !important; }
.dv-btn.primary { background: #043361; color: #fff !important; }
.dv-btn.primary:hover { background: #06529c; border-color: #06529c; }
.dv-os { font-weight: 600; font-size: .78rem; opacity: .72; }
.dv-social { display: flex; gap: .6rem; justify-content: center; margin-top: 1.3rem; }
.soc-ic { display: inline-flex; align-items: center; justify-content: center; width: 40px; height: 40px; border-radius: 50%; background: #f1f3f5; color: #5c6066 !important; transition: all .2s ease; }
.soc-ic svg { width: 18px; height: 18px; }
.soc-ic:hover { background: #043361; color: #fff !important; transform: translateY(-2px); }
@media (prefers-color-scheme: dark) {
  .depthviz-card { background: linear-gradient(135deg, #1a2436, #1e2024); border-color: #2c3f5a; }
  .dv-tag { background: #161a20; border-color: #2c3f5a; color: #8ec5ff; }
  .dv-title { color: #8ec5ff; }
  .dv-desc { color: #c7cad0; }
  .dv-btn { border-color: #5aa9ff; color: #5aa9ff !important; }
  .dv-btn.primary { background: #2b6cb0; color: #fff !important; border-color: #2b6cb0; }
  .soc-ic { background: #2a2f36; color: #c7cad0 !important; }
  .soc-ic:hover { background: #2b6cb0; color: #fff !important; }
}
</style>

<div class="uc-banner">
  <p class="uc-title">🚧 UNDER CONSTRUCTION · TBD 🚧</p>
  <p class="uc-sub">This site is being updated — projects &amp; content are being added.</p>
</div>

<div class="hero">
  <img class="hero-avatar" src="/assets/img/minsuk0.png" alt="Minsuk Jang" />
  <h1>Minsuk Jang</h1>
  <div class="hero-sub">AI Researcher &nbsp;·&nbsp; Civil Engineering Background</div>
  <p class="hero-statement">
    I am an <strong>AI researcher with a civil engineering background</strong> — B.S. in Civil Engineering
    at Yonsei University, and currently an M.S. in Electrical Engineering at KAIST. I'm interested in
    <strong>physical AI, agentic AI, and remote sensing</strong>, and I love working on
    <strong>real-world problems and applications</strong>.
  </p>
  <div class="depthviz-card">
    <div class="dv-top">
      <span class="dv-tag">📱 iOS · App Store</span>
      <span class="dv-tag">🏆 Peaked #36</span>
      <span class="dv-tag">◆ Open Source</span>
    </div>
    <h2 class="dv-title">DepthViz</h2>
    <p class="dv-desc">
      The most accurate and robust <strong>LiDAR-SLAM scanner on iPhone</strong> — infrastructure-free,
      on-device 3D mapping. Released on the App Store, where it peaked at <strong>#36</strong>.
    </p>
    <div class="dv-btns">
      <a class="dv-btn primary" href="https://apps.apple.com/app/depthviz/id6754522044" target="_blank" rel="noopener">Try Demo</a>
      <a class="dv-btn" href="https://github.com/tersite1/DepthViz" target="_blank" rel="noopener">GitHub <span class="dv-os">(open source)</span></a>
    </div>
  </div>

  <div class="dv-social">
    <a href="mailto:minsukjang@kaist.ac.kr" class="soc-ic" aria-label="Email">
      <svg viewBox="0 0 16 16" fill="currentColor"><path d="M0 4a2 2 0 0 1 2-2h12a2 2 0 0 1 2 2v8a2 2 0 0 1-2 2H2a2 2 0 0 1-2-2V4Zm2-1a1 1 0 0 0-1 1v.217l7 4.2 7-4.2V4a1 1 0 0 0-1-1H2Zm13 2.383-4.708 2.825L15 11.105V5.383Zm-.034 6.876-5.64-3.471L8 9.583l-1.326-.795-5.64 3.47A1 1 0 0 0 2 13h12a1 1 0 0 0 .966-.741ZM1 11.105l4.708-2.897L1 5.383v5.722Z"/></svg>
    </a>
    <a href="https://github.com/tersite1" class="soc-ic" target="_blank" rel="noopener" aria-label="GitHub">
      <svg viewBox="0 0 16 16" fill="currentColor"><path d="M8 0C3.58 0 0 3.58 0 8c0 3.54 2.29 6.53 5.47 7.59.4.07.55-.17.55-.38 0-.19-.01-.82-.01-1.49-2.01.37-2.53-.49-2.69-.94-.09-.23-.48-.94-.82-1.13-.28-.15-.68-.52-.01-.53.63-.01 1.08.58 1.23.82.72 1.21 1.87.87 2.33.66.07-.52.28-.87.51-1.07-1.78-.2-3.64-.89-3.64-3.95 0-.87.31-1.59.82-2.15-.08-.2-.36-1.02.08-2.12 0 0 .67-.21 2.2.82a7.65 7.65 0 0 1 2-.27c.68 0 1.36.09 2 .27 1.53-1.04 2.2-.82 2.2-.82.44 1.1.16 1.92.08 2.12.51.56.82 1.27.82 2.15 0 3.07-1.87 3.75-3.65 3.95.29.25.54.73.54 1.48 0 1.07-.01 1.93-.01 2.2 0 .21.15.46.55.38A8.01 8.01 0 0 0 16 8c0-4.42-3.58-8-8-8Z"/></svg>
    </a>
    <a href="https://www.linkedin.com/in/jadenjang/" class="soc-ic" target="_blank" rel="noopener" aria-label="LinkedIn">
      <svg viewBox="0 0 16 16" fill="currentColor"><path d="M0 1.146C0 .513.526 0 1.175 0h13.65C15.474 0 16 .513 16 1.146v13.708c0 .633-.526 1.146-1.175 1.146H1.175C.526 16 0 15.487 0 14.854V1.146Zm4.943 12.248V6.169H2.542v7.225h2.401Zm-1.2-8.212c.837 0 1.358-.554 1.358-1.248-.015-.709-.52-1.248-1.342-1.248-.822 0-1.359.54-1.359 1.248 0 .694.521 1.248 1.327 1.248h.016Zm4.908 8.212V9.359c0-.216.016-.432.08-.586.174-.431.568-.878 1.232-.878.869 0 1.216.662 1.216 1.634v3.865h2.401V9.25c0-2.22-1.184-3.252-2.764-3.252-1.274 0-1.845.7-2.165 1.193v.025h-.016l.016-.025V6.169h-2.4c.03.678 0 7.225 0 7.225h2.4Z"/></svg>
    </a>
  </div>
</div>
