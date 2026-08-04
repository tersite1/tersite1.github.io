---
layout: default
title: CV
permalink: /cv/
weight: 8
---

<style>
.cv-actions { display: flex; gap: .6rem; flex-wrap: wrap; margin: .2rem 0 1rem; }
.cv-btn {
  font-size: .9rem; font-weight: 700; color: #043361; text-decoration: none !important;
  border: 1.5px solid #043361; border-radius: 7px; padding: .45rem .9rem; display: inline-block;
}
.cv-btn.solid { background: #043361; color: #fff !important; }
.cv-frame { width: 100%; height: 90vh; min-height: 900px; border: 1px solid #e5e7eb; border-radius: .5rem; }
.cv-mobile-note { display: none; }
@media (max-width: 680px) {
  .cv-frame { display: none; }
  .cv-mobile-note { display: block; color: #6c757d; font-size: .88rem; margin: 0 0 1rem; }
}
@media (prefers-color-scheme: dark) {
  .cv-btn { color: #8ec5ff; border-color: #8ec5ff; }
  .cv-btn.solid { background: #8ec5ff; color: #0b1220 !important; }
  .cv-mobile-note { color: #9aa0a6; }
}
</style>

<div class="cv-actions">
  <a class="cv-btn solid" href="/assets/files/CV_minsuk.pdf" target="_blank" rel="noopener">Open PDF in new tab ↗</a>
  <a class="cv-btn" href="/assets/files/CV_minsuk.pdf" download>Download PDF</a>
</div>

<p class="cv-mobile-note">PDF preview is best viewed on desktop. On mobile, use the buttons above to open or download.</p>

<iframe class="cv-frame" src="/assets/files/CV_minsuk.pdf#view=FitH">
    This browser does not support PDFs. Please download the PDF to view it:
    <a href="/assets/files/CV_minsuk.pdf">Download PDF</a>.
</iframe>
