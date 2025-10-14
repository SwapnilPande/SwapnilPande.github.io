---
layout: post
title: Every Flavor demoed Etchbot at OpenSauce 2024!
date: 2024-06-25 07:59:00-0400
inline: false
related_posts: false
---

We demoed our viral EtchBot at OpenSauce 2024! We went through some serious design revisions to improve the robustness and serviceability of the hardware. Each Etchbot ran over 800 demos, with only routine servicing. We quickly discovered that the Etch-a-sketches were the weak link in the system, with a service life of about 400 demos :).

We also redesigned almost all of the software stack to better support live demos. This included building a GUI to capture a picture and show the users the pipeline proessing steps, retuning the piepline to better capture facial features, and reducing the processing time from ~8 minutes to under 50 seconds.

It was incredibly inspiring to meet creators equally as passionate as us in all of their various niches. We met new collaborators, shared insights on the content creation industry, and made lifelong friends. I can't wait to be back next year. We have more in store for the Etchbot, subscribe to our channel to see what's next!

## Press coverage

<style>
/* Scoped to avoid theme collisions */
.efr-press{display:grid;grid-template-columns:1fr;gap:16px;margin:16px 0}
@media(min-width:880px){.efr-press{grid-template-columns:3fr 2fr}}
.efr-card{background:#fff;border:1px solid #e6e6e6;border-radius:12px;overflow:hidden}
.efr-embed{position:relative;padding-bottom:56.25%;height:0}
.efr-embed iframe{position:absolute;inset:0;width:100%;height:100%;border:0}
.efr-body{padding:14px}
.efr-meta{display:flex;align-items:center;gap:.5rem;color:#666;font-size:.95rem;margin-bottom:.25rem}
.efr-meta img{width:18px;height:18px;border-radius:4px}
.efr-title{font-weight:600;color:#111;margin:.15rem 0 .35rem 0}
.efr-desc{color:#444;font-size:.98rem;line-height:1.45;margin:0}
.efr-cta{margin-top:.75rem;font-size:.95rem}
</style>

<div class="efr-press">

  <!-- Primary OpenSauce short -->
  <div class="efr-card">
    <div class="efr-embed">
      <iframe src="https://www.youtube.com/embed/BSJjZlGh7po"
              title="Every Flavor demoed Etchbot at OpenSauce 2024!"
              allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture"
              allowfullscreen></iframe>
    </div>
    <div class="efr-body">
      <div class="efr-title">Etch-a-Sketch Portrait Robot at Open Sauce ’24</div>
      <p class="efr-desc">A quick look at the live demo and drawing pipeline.</p>
    </div>
  </div>

  <!-- Article card -->
  <a class="efr-card" href="https://hackaday.com/2024/05/20/etch-a-sketch-camera-is-open-source/" target="_blank" rel="noopener">
    <div class="efr-body">
      <div class="efr-meta">
        <img src="https://hackaday.com/favicon.ico" alt="Hackaday">
        <span>hackaday.com</span>
      </div>
      <div class="efr-title">Etch-A-Sketch Camera is Open Source</div>
      <p class="efr-desc">Coverage of our EtchBot build and open-source stack.</p>
      <div class="efr-cta">Read article →</div>
    </div>
  </a>

  <!-- Original long video (full width below) -->
  <div class="efr-card" style="grid-column:1/-1;">
    <div class="efr-embed">
      <iframe src="https://www.youtube.com/embed/iQhhutAanu0"
              title="Original EtchBot video"
              allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture"
              allowfullscreen></iframe>
    </div>
    <div class="efr-body">
      <div class="efr-title">Original build video</div>
      <p class="efr-desc">Deep dive on the story of the build.</p>
    </div>
  </div>

</div>


