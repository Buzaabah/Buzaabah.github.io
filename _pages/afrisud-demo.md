---
permalink: /afrisud-demo/
title: "AfriSUD Interactive Demo"
author_profile: true
classes: wide
---

<link rel="stylesheet" href="{{ base_path }}/assets/css/afrisud-demo.css">

<section class="afrisud-demo-header">
  <p class="afrisud-demo-kicker">EMNLP 2026 · Interactive research demo</p>
  <h2>Explore dependency parsing across nine African languages</h2>
  <p>
    Enter a sentence, select a language and model, then compare the model's
    dependency parse against a verified AfriSUD gold annotation.
  </p>
  <p class="afrisud-demo-links">
    <a href="https://arxiv.org/abs/2606.12708">Read the paper</a>
    <span aria-hidden="true">·</span>
    <a href="https://github.com/Buzaabah">View my GitHub</a>
  </p>
</section>

<div class="afrisud-frame-shell">
  <iframe
    class="afrisud-frame"
    src="https://afrisud-explainer.hbuzaaba.chatgpt.site"
    title="AfriSUD interactive dependency parsing demo"
    loading="eager"
    allow="clipboard-write"
    referrerpolicy="strict-origin-when-cross-origin">
  </iframe>
</div>

<noscript>
  This interactive demo requires JavaScript. You can open it directly at
  <a href="https://afrisud-explainer.hbuzaaba.chatgpt.site">the AfriSUD demo site</a>.
</noscript>

