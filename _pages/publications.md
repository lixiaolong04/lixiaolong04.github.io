---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

My work explores dexterous robotic manipulation, multi-finger coordination, and robot learning.
You can also find my publications on
[Google Scholar](https://scholar.google.com/citations?user=PS_CX0AAAAAJ).

## Peer-reviewed Publications

{% include publication-rigidity-card.html %}

## Undergraduate Thesis

<article class="thesis-card">
  <div class="thesis-card__summary">
    <a class="thesis-card__cover" href="/files/thesis/xiaolong-li-undergraduate-thesis-2026.pdf">
      <img
        src="/images/thesis/thesis-cover.png"
        alt="Cover of Xiaolong Li's undergraduate thesis"
        loading="lazy">
    </a>
    <div class="thesis-card__content">
      <p class="publication-card__venue">Undergraduate Thesis · Chongqing University · 2026</p>
      <h3>
        <a href="/files/thesis/xiaolong-li-undergraduate-thesis-2026.pdf">
          Research on In-Hand Rotation Algorithm of Multi-Fingered Dexterous Hand Based on Reinforcement Learning
        </a>
      </h3>
      <p class="thesis-card__subtitle">基于强化学习的多指灵巧手手内旋转算法研究</p>
      <p class="publication-card__authors">
        <strong>Xiaolong Li</strong> · Advisor:
        <a href="https://faculty.cqu.edu.cn/GangshanJing/zh_CN/index.htm">Prof. Gangshan Jing</a>
      </p>
      <p>
        A reinforcement-learning framework for in-hand rotation with a custom 16-DoF
        four-fingered dexterous hand in MuJoCo. The system combines PPO, an asymmetric
        Actor-Critic architecture, curriculum learning, domain randomization, and a homing-key
        initialization mechanism. The thesis reports a rotation success rate above 90% and
        demonstrates both Z-axis rotation and Y-axis flipping.
      </p>
      <div class="publication-card__links">
        <a href="/files/thesis/xiaolong-li-undergraduate-thesis-2026.pdf">Thesis PDF</a>
        <a href="/files/thesis/z-axis-rotation.mp4">Z-axis Demo</a>
        <a href="/files/thesis/y-axis-flip.mp4">Y-axis Demo</a>
      </div>
    </div>
  </div>

  <div class="thesis-demo-grid" aria-label="Undergraduate thesis demonstrations">
    <figure class="thesis-demo">
      <video
        controls
        playsinline
        preload="metadata"
        poster="/images/thesis/z-axis-rotation.jpg">
        <source src="/files/thesis/z-axis-rotation.mp4" type="video/mp4">
        Your browser does not support HTML5 video.
      </video>
      <figcaption>
        <strong>Z-axis rotation</strong>
        <span>Continuous in-hand rotation of a cube while maintaining a stable grasp.</span>
      </figcaption>
    </figure>

    <figure class="thesis-demo">
      <video
        controls
        playsinline
        preload="metadata"
        poster="/images/thesis/y-axis-flip.jpg">
        <source src="/files/thesis/y-axis-flip.mp4" type="video/mp4">
        Your browser does not support HTML5 video.
      </video>
      <figcaption>
        <strong>Y-axis flipping</strong>
        <span>Generalization to a different rotation axis through reward and initial-pose adaptation.</span>
      </figcaption>
    </figure>
  </div>
</article>
