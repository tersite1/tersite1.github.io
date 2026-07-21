---
layout: default
permalink: /
---

<style>
.hero { text-align: center; max-width: 780px; margin: 2.2rem auto 2.2rem; padding: 0 1rem; }
.hero-avatar { width: 168px; height: 168px; object-fit: cover; border-radius: 50%; box-shadow: 0 6px 22px rgba(0,0,0,.18); margin-bottom: 1.1rem; }
.hero h1 { font-size: 2.1rem; font-weight: 800; margin: .2rem 0 .15rem; }
.hero-sub { color: #5c6066; font-size: 1.05rem; margin-bottom: .2rem; }
.hero-statement { font-size: 1.1rem; color: #2c2c2c; line-height: 1.65; margin: 1.1rem auto 0; max-width: 680px; text-wrap: balance; }
@media (prefers-color-scheme: dark) { .hero-statement { color: #d7dade; } }
.affil { max-width: 730px; margin: 1.4rem auto 0; }
.affil-group { margin-bottom: .55rem; }
.affil-label { font-size: .68rem; font-weight: 800; letter-spacing: .14em; text-transform: uppercase; color: #9aa3b0; margin-bottom: .2rem; }
.affil-items { font-size: .85rem; color: #55606b; line-height: 1.6; }
.affil-items .pi { color: #8a93a0; }
.affil-link { color: inherit; font-weight: 600; text-decoration: none; border-bottom: 1px solid transparent; transition: color .15s ease, border-color .15s ease; }
.affil-link:hover { color: #043361; border-bottom-color: rgba(4,51,97,.45); }
@media (prefers-color-scheme: dark) { .affil-label { color: #6b7480; } .affil-items { color: #b3b9c2; } .affil-items .pi { color: #868e99; } .affil-link:hover { color: #8ec5ff; border-bottom-color: rgba(142,197,255,.5); } }
.xp { display: grid; grid-template-columns: 1fr 1fr; gap: 1.4rem 2.4rem; max-width: 800px; margin: 1.8rem auto .4rem; text-align: left; }
.xp-label { font-size: .68rem; font-weight: 800; letter-spacing: .14em; text-transform: uppercase; color: #9aa3b0; margin: 0 0 .7rem; padding-bottom: .35rem; border-bottom: 1px solid #ececf0; }
.xp-item { margin-bottom: .85rem; }
.xp-head { display: flex; justify-content: space-between; align-items: baseline; gap: .6rem; }
.xp-org { font-size: .88rem; font-weight: 700; color: #1f2937; text-decoration: none; border-bottom: 1px solid transparent; transition: color .15s ease, border-color .15s ease; }
.xp-org:hover { color: #043361; border-bottom-color: rgba(4,51,97,.4); }
.xp-date { font-size: .72rem; font-weight: 600; color: #9aa3b0; white-space: nowrap; flex: 0 0 auto; }
.xp-role { font-size: .78rem; color: #6b7280; margin-top: .12rem; line-height: 1.4; }
@media (max-width: 640px) { .xp { grid-template-columns: 1fr; gap: 1.2rem; } }
@media (prefers-color-scheme: dark) {
  .xp-label { color: #6b7480; border-bottom-color: #2c2f33; }
  .xp-org { color: #e5e7eb; } .xp-org:hover { color: #8ec5ff; border-bottom-color: rgba(142,197,255,.5); }
  .xp-date { color: #6b7480; } .xp-role { color: #9aa0a6; }
}

/* DepthViz editorial card */
.dv2 {
  max-width: 940px; margin: 2rem auto 0; padding: 1.9rem; text-align: left;
  background: #fdfdfc; border: 1px solid #e7e4de; border-radius: 1rem; box-shadow: 0 6px 28px rgba(0,0,0,0.07);
  background-image: linear-gradient(rgba(0,0,0,.035) 1px, transparent 1px), linear-gradient(90deg, rgba(0,0,0,.035) 1px, transparent 1px);
  background-size: 34px 34px;
  display: grid; grid-template-columns: 1.02fr 1fr; gap: 2rem; align-items: center;
}
.dv2-logo { width: 60px; height: 60px; border-radius: 12px; border: 2px solid #111; object-fit: cover; box-shadow: 5px 5px 0 rgba(17,17,17,.08); }
.dv2-eyebrow { font-size: .78rem; font-weight: 800; letter-spacing: .2em; color: #e8552b; margin: 1rem 0 .15rem; }
.dv2-title { font-family: Georgia, 'Times New Roman', serif; font-size: 2.6rem; font-weight: 700; color: #111; margin: 0 0 .7rem; line-height: 1; }
.dv2-desc { font-size: 1rem; color: #3a3a3a; line-height: 1.55; margin: 0 0 1rem; max-width: 400px; }
.dv2-rank { font-family: Georgia, serif; font-size: 3rem; font-weight: 700; color: #e8552b; line-height: 1; margin: .3rem 0 .05rem; }
.dv2-rank-cap { font-size: .8rem; font-weight: 800; letter-spacing: .14em; color: #e8552b; margin: 0 0 1.2rem; }
.dv2-btns { display: flex; flex-wrap: wrap; gap: .6rem; align-items: stretch; }
.dv2-appstore { display: inline-flex; align-items: center; gap: .6rem; background: #111; color: #fff !important; padding: .55rem 1.1rem; border-radius: 9px; text-decoration: none !important; transition: transform .15s ease; }
.dv2-appstore:hover { transform: translateY(-2px); }
.dv2-appstore svg { color: #e8552b; }
.dv2-appstore .t1 { font-size: .6rem; letter-spacing: .16em; color: #b9b9b9; text-transform: uppercase; display: block; }
.dv2-appstore .t2 { font-size: .92rem; font-weight: 700; }
.dv2-gh { display: inline-flex; align-items: center; padding: .55rem 1rem; border: 2px solid #111; border-radius: 9px; color: #111 !important; font-weight: 700; font-size: .88rem; text-decoration: none !important; transition: all .15s ease; }
.dv2-gh:hover { background: #111; color: #fff !important; }
.dv2-right { display: grid; grid-template-columns: 1fr 1fr; gap: 1rem; }
.dv2-shot-cap { font-size: .82rem; font-weight: 800; letter-spacing: .08em; color: #111; text-transform: uppercase; line-height: 1.15; }
.dv2-shot-sub { font-size: .76rem; color: #666; margin: .15rem 0 .5rem; }
.dv2-phone { background: #f3f3f0; border-radius: 18px; padding: 6px; box-shadow: 6px 6px 0 rgba(17,17,17,.05), 0 4px 14px rgba(0,0,0,.12); position: relative; }
.dv2-phone::before { content:''; position:absolute; top:11px; left:50%; transform:translateX(-50%); width:34%; height:12px; background:#111; border-radius:0 0 9px 9px; z-index:2; }
.dv2-phone video { width: 100%; display: block; border-radius: 13px; background:#000; }

/* Social icons */
.dv-social { display: flex; gap: .6rem; justify-content: center; margin-top: 1.6rem; }
.soc-ic { display: inline-flex; align-items: center; justify-content: center; width: 40px; height: 40px; border-radius: 50%; background: #f1f3f5; color: #5c6066 !important; transition: all .2s ease; }
.soc-ic svg { width: 18px; height: 18px; }
.soc-ic:hover { background: #043361; color: #fff !important; transform: translateY(-2px); }

@media (max-width: 820px) { .dv2 { grid-template-columns: 1fr; } .dv2-title { font-size: 2.2rem; } }
@media (prefers-color-scheme: dark) {
  .dv2 { background:#17181b; border-color:#2c2f33; background-image: linear-gradient(rgba(255,255,255,.045) 1px, transparent 1px), linear-gradient(90deg, rgba(255,255,255,.045) 1px, transparent 1px); }
  .dv2-title { color:#f1f1f1; } .dv2-desc { color:#c7cad0; } .dv2-logo { border-color:#f1f1f1; }
  .dv2-shot-cap { color:#f1f1f1; } .dv2-shot-sub { color:#a9adb3; }
  .dv2-gh { border-color:#f1f1f1; color:#f1f1f1 !important; } .dv2-gh:hover { background:#f1f1f1; color:#111 !important; }
  .dv2-phone { background:#23252a; }
  .soc-ic { background:#2a2f36; color:#c7cad0 !important; } .soc-ic:hover { background:#2b6cb0; color:#fff !important; }
}
</style>

<div class="hero">
  <img class="hero-avatar" src="/assets/img/minsuk0.png" alt="Minsuk Jang" />
  <h1>Minsuk Jang</h1>
  <p class="hero-statement">
    I'm an <strong>AI researcher with a civil engineering background</strong>, holding a
    <strong>B.S. in Civil Engineering from Yonsei University</strong> and currently pursuing an
    <strong>M.S. in Electrical Engineering at KAIST</strong>. My work spans
    <strong>3D perception, Agentic AI, and AI safety</strong>, and I care most about research that leaves
    the lab and holds up in the real world. I like to build end to end, from field sensing systems to the
    learning algorithms behind them. Above all, I place my highest priority on contributing to
    <strong>physical AI</strong>.
  </p>
</div>

<div class="dv2">
  <div class="dv2-left">
    <img class="dv2-logo" src="/assets/img/depthviz-logo.png" alt="DepthViz" />
    <div class="dv2-eyebrow">OPEN-SOURCE SLAM · iOS</div>
    <h2 class="dv2-title">DepthViz</h2>
    <p class="dv2-desc">
      The <strong>most accurate, fastest, and most compatible</strong> LiDAR scanner on iOS: a powerful,
      fully open-source SLAM engine that turns any iPhone into a reality-capture device. Free, no ads.<br>
      <strong>Collaboration &amp; research inquiries are always welcome.</strong>
    </p>
    <div class="dv2-rank">#36</div>
    <div class="dv2-rank-cap">HIT CHART #36 · iOS APP STORE</div>
    <div class="dv2-btns">
      <a class="dv2-appstore" href="https://apps.apple.com/app/depthviz/id6754522044" target="_blank" rel="noopener">
        <svg viewBox="0 0 16 16" fill="currentColor" width="24" height="24"><path d="M11.182.008C11.148-.03 9.923.023 8.857 1.18c-1.066 1.156-.902 2.482-.878 2.516.024.034 1.52.087 2.475-1.258.955-1.345.762-2.391.728-2.43Zm3.314 11.733c-.048-.096-2.325-1.234-2.113-3.422.212-2.189 1.675-2.789 1.698-2.854.023-.065-.597-.79-1.254-1.157a3.692 3.692 0 0 0-1.563-.434c-.108-.003-.483-.095-1.254.116-.508.139-1.653.589-1.968.607-.316.018-1.256-.522-2.267-.665-.647-.125-1.333.131-1.824.328-.49.196-1.422.754-2.074 2.237-.652 1.482-.311 3.83-.067 4.56.244.729.625 1.924 1.273 2.796.576.984 1.34 1.667 1.659 1.899.319.232 1.219.386 1.843.067.502-.308 1.408-.485 1.766-.472.357.013 1.061.154 1.782.539.571.197 1.111.115 1.652-.105.541-.221 1.324-1.059 2.238-2.758.347-.79.505-1.217.473-1.282Z"/></svg>
        <span><span class="t1">Download on</span><span class="t2">the App Store</span></span>
      </a>
      <a class="dv2-gh" href="https://github.com/tersite1/DepthViz" target="_blank" rel="noopener">GitHub · open source</a>
    </div>
  </div>

  <div class="dv2-right">
    <div>
      <div class="dv2-shot-cap">Capture Reality</div>
      <div class="dv2-shot-sub">Scan everything around.</div>
      <div class="dv2-phone"><video src="/assets/img/depthviz-capture.mp4" autoplay muted loop playsinline preload="metadata"></video></div>
    </div>
    <div>
      <div class="dv2-shot-cap">Review Instantly</div>
      <div class="dv2-shot-sub">Render results instantly.</div>
      <div class="dv2-phone"><video src="/assets/img/depthviz-review.mp4" autoplay muted loop playsinline preload="metadata"></video></div>
    </div>
  </div>
</div>

<div class="xp">
  <div class="xp-col">
    <div class="xp-label">Research Experience</div>
    <div class="xp-item">
      <div class="xp-head"><a class="xp-org" href="https://cilabs.kaist.ac.kr/" target="_blank" rel="noopener">Computational Intelligence Lab, KAIST</a><span class="xp-date">Feb 2025 - Present</span></div>
      <div class="xp-role">Graduate Research Assistant · Prof. Changick Kim</div>
    </div>
    <div class="xp-item">
      <div class="xp-head"><a class="xp-org" href="https://www.gnss.kr/" target="_blank" rel="noopener">Intelligent Unmanned Systems Lab, Yonsei</a><span class="xp-date">Jul - Sep 2024</span></div>
      <div class="xp-role">Undergraduate Research Assistant · Prof. Jiwon Seo</div>
    </div>
    <div class="xp-item">
      <div class="xp-head"><a class="xp-org" href="https://vi.snu.ac.kr/intro.php" target="_blank" rel="noopener">Vehicle Intelligence Lab, SNU</a><span class="xp-date">Apr - Jul 2024</span></div>
      <div class="xp-role">Undergraduate Research Assistant · Prof. Seoungwoo Seo</div>
    </div>
    <div class="xp-item">
      <div class="xp-head"><a class="xp-org" href="https://arisnu.squarespace.com" target="_blank" rel="noopener">Autonomous Robot Intelligence Lab, SNU</a><span class="xp-date">Jan - Mar 2024</span></div>
      <div class="xp-role">Undergraduate Research Assistant · Prof. Seoung Woo Kim</div>
    </div>
  </div>
  <div class="xp-col">
    <div class="xp-label">Work Experience</div>
    <div class="xp-item">
      <div class="xp-head"><a class="xp-org" href="https://idoll.love/" target="_blank" rel="noopener">IDOLL Robotics</a><span class="xp-date">Apr 2025 - Present</span></div>
      <div class="xp-role">Robotics Engineer · Ontology-based home agent robot</div>
    </div>
    <div class="xp-item">
      <div class="xp-head"><a class="xp-org" href="https://stellarvision.co.kr/english/" target="_blank" rel="noopener">Stellarvision</a><span class="xp-date">Jul 2024 - Feb 2025</span></div>
      <div class="xp-role">AI Engineer · Drone Digital Twin Team</div>
    </div>
    <div class="xp-item">
      <div class="xp-head"><span class="xp-org">XYZ Innovation</span><span class="xp-date">Jul 2024 - Feb 2025</span></div>
      <div class="xp-role">Robotics Engineer · Drone and LiDAR forest carbon</div>
    </div>
    <div class="xp-item">
      <div class="xp-head"><a class="xp-org" href="https://www.hyundai.com/worldwide/en" target="_blank" rel="noopener">Hyundai Motor Company</a><span class="xp-date">Jan - Jul 2024</span></div>
      <div class="xp-role">Undergraduate Research Scholarship · LiDAR perception</div>
    </div>
  </div>
</div>

<script>
(function () {
  function kick(v) { try { v.muted = true; var p = v.play(); if (p && p.catch) p.catch(function () {}); } catch (e) {} }
  function playAll() { document.querySelectorAll('.dv2-phone video').forEach(kick); }
  if (document.readyState !== 'loading') playAll(); else document.addEventListener('DOMContentLoaded', playAll);
  window.addEventListener('load', playAll);
  if ('IntersectionObserver' in window) {
    var io = new IntersectionObserver(function (es) { es.forEach(function (e) { if (e.isIntersecting) kick(e.target); }); }, { threshold: 0.1 });
    document.querySelectorAll('.dv2-phone video').forEach(function (v) { io.observe(v); });
  }
})();
</script>
