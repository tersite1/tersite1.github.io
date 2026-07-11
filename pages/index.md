---
layout: default
permalink: /
---

<style>
.hero { text-align: center; max-width: 780px; margin: 2.2rem auto 2.2rem; padding: 0 1rem; }
.hero-avatar { width: 168px; height: 168px; object-fit: cover; border-radius: 50%; box-shadow: 0 6px 22px rgba(0,0,0,.18); margin-bottom: 1.1rem; }
.hero h1 { font-size: 2.1rem; font-weight: 800; margin: .2rem 0 .15rem; }
.hero-sub { color: #5c6066; font-size: 1.05rem; margin-bottom: .2rem; }
.hero-statement { font-size: 1.1rem; color: #2c2c2c; line-height: 1.65; margin: 1.1rem auto 0; max-width: 650px; }
@media (prefers-color-scheme: dark) { .hero-statement { color: #d7dade; } }
.affil { max-width: 730px; margin: 1.4rem auto 0; }
.affil-group { margin-bottom: .55rem; }
.affil-label { font-size: .68rem; font-weight: 800; letter-spacing: .14em; text-transform: uppercase; color: #9aa3b0; margin-bottom: .2rem; }
.affil-items { font-size: .85rem; color: #55606b; line-height: 1.6; }
.affil-items .pi { color: #8a93a0; }
@media (prefers-color-scheme: dark) { .affil-label { color: #6b7480; } .affil-items { color: #b3b9c2; } .affil-items .pi { color: #868e99; } }

/* Under construction banner */
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

<div class="uc-banner">
  <p class="uc-title">🚧 UNDER CONSTRUCTION · TBD 🚧</p>
  <p class="uc-sub">This site is being updated. Projects &amp; content are being added.</p>
</div>

<div class="hero">
  <img class="hero-avatar" src="/assets/img/minsuk0.png" alt="Minsuk Jang" />
  <h1>Minsuk Jang</h1>
  <div class="hero-sub">AI Researcher &nbsp;·&nbsp; Civil Engineering Background</div>
  <p class="hero-statement">
    I'm an <strong>AI researcher with a background in civil engineering</strong>. After a B.S. in Civil
    Engineering at Yonsei University, I'm now pursuing my M.S. in Electrical Engineering at KAIST, in the
    Computational Intelligence Laboratory (Prof. Changick Kim). Having worked across research labs and
    companies, I focus on <strong>3D, agentic AI, and physical AI</strong>, with one goal throughout:
    building systems that solve real problems in the real world.
  </p>
  <div class="affil">
    <div class="affil-group">
      <div class="affil-label">Research Labs</div>
      <div class="affil-items">
        Computational Intelligence Lab, KAIST <span class="pi">(Prof. Changick Kim)</span> ·
        Intelligent Unmanned Systems Lab, Yonsei <span class="pi">(Prof. Jiwon Seo)</span> ·
        Vehicle Intelligence Lab, SNU <span class="pi">(Prof. Seoungwoo Seo)</span> ·
        Autonomous Robot Intelligence Lab, SNU <span class="pi">(Prof. Seoung Woo Kim)</span>
      </div>
    </div>
    <div class="affil-group">
      <div class="affil-label">Industry</div>
      <div class="affil-items">IDOLL Robotics · Stellarvision · XYZ Innovation · Hyundai Motor Company</div>
    </div>
  </div>
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
