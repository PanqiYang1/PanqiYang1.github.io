---
permalink: /
title: "About Me"
excerpt: "About Me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

<style>
  /* 全局基础样式 —— 更现代的学术风格 */
  body {
    font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, "Helvetica Neue", Arial, sans-serif;
    line-height: 1.55;
    color: #1e2a3e;
    background: #fff;
    margin: 0;
    padding: 0;
  }

  /* 主要内容容器（模拟传统学术页面宽度）*/
  .page__content, .main-content {
    max-width: 1000px;
    margin: 0 auto;
  }

  /* 引用块美化 */
  blockquote {
    border-left: 4px solid #2c7da0;
    background: #f8fafc;
    padding: 0.8rem 1.5rem;
    margin: 1.2rem 0;
    font-style: normal;
    border-radius: 0 12px 12px 0;
    color: #2c3e50;
  }

  /* 标题样式 */
  h2 {
    font-size: 1.8rem;
    font-weight: 600;
    border-bottom: 2px solid #e2e8f0;
    padding-bottom: 0.3rem;
    margin-top: 2rem;
    margin-bottom: 1.2rem;
    letter-spacing: -0.3px;
  }

  h3 {
    font-size: 1.3rem;
    font-weight: 500;
    margin-top: 1.5rem;
    margin-bottom: 0.75rem;
    color: #1e466e;
  }

  /* 新闻列表 */
  .news-list {
    list-style: none;
    padding-left: 0;
  }
  .news-list li {
    margin-bottom: 0.65rem;
    padding-left: 0.5rem;
    border-left: 3px solid #cbd5e1;
    transition: border-color 0.2s;
  }
  .news-list li:hover {
    border-left-color: #2c7da0;
  }

  /* 论文条目卡片效果（原有 div 结构不动，仅增强视觉） */
  .paper-entry {
    transition: background 0.2s ease, box-shadow 0.2s ease;
    padding: 0.25rem 0;
  }
  .paper-entry:hover {
    background: #fafcff;
  }

  /* 图片圆角与阴影 */
  img[alt*="paper preview"] {
    border-radius: 8px;
    box-shadow: 0 2px 8px rgba(0,0,0,0.05);
    transition: transform 0.2s, box-shadow 0.2s;
  }
  img[alt*="paper preview"]:hover {
    transform: scale(1.01);
    box-shadow: 0 4px 12px rgba(0,0,0,0.1);
  }

  /* 按钮/链接 */
  a {
    color: #2c7da0;
    text-decoration: none;
    border-bottom: 1px dotted #cbd5e1;
  }
  a:hover {
    color: #1f5068;
    border-bottom-color: #2c7da0;
  }

  /* Experience 中的右浮动日期 */
  .float-date {
    float: right;
    color: #5a6e85;
    font-size: 0.85rem;
    font-weight: normal;
  }

  /* 联系部分 */
  .contact-links {
    background: #f1f5f9;
    padding: 0.8rem 1.2rem;
    border-radius: 18px;
    display: inline-block;
    margin-top: 0.5rem;
  }

  /* 调整内联图片样式 */
  img {
    max-width: 100%;
    height: auto;
  }

  /* 响应式小屏优化 */
  @media (max-width: 700px) {
    .float-date {
      float: none;
      display: block;
      margin-top: 0.2rem;
    }
    .paper-entry > div {
      flex-direction: column;
    }
  }
</style>

> *"The success of machine learning generally depends on data representation."* <br>
> — **Yoshua Bengio**

I am currently a Master's student at **Xi'an Jiaotong University (XJTU)**, and I am fortunate to continue my research journey as an **incoming Ph.D. student** at XJTU in Fall 2026. Previously, I spent a wonderful time as a Research Intern at the Transaction Algorithm Team, **Xiaohongshu**.

💡 Research Philosophy

<p align="center">
  <strong>Representation Learning · Top‑down ↔ Bottom‑up Closed Loop</strong>
</p>

<br/>

| 🧠 **Top‑down** | ↺ | ⚙️ **Bottom‑up** |
| :--- | :---: | ---: |
| Cognitive inspiration — how the human brain decouples concepts, aligns modalities, and generalizes. |  | Computational grounding — translating insights into algebraic & geometric designs for unified representations. |

<p align="center">
  <em>Bidirectional dialogue: biological intelligence guides the math, and computation refines our understanding of cognition.</em>
</p>

🔥 News
======
<ul class="news-list" style="margin-top: -0.2rem;">
  <li><strong>[2026.04]</strong> 🎉🎉 One paper <strong>MUSE</strong> addressing manifold misalignment in Visual Tokenization is accepted to <strong>ICML 2026</strong>!</li>
  <li><strong>[2026.03]</strong> 🎉🎉 One paper <strong>DAMind</strong> is accepted to <strong>TIP 2026</strong>!</li>
  <li><strong>[2026.02]</strong> 🎉🎉 One paper <strong>InstrucRobo</strong> is accepted to <strong>EAAI 2026</strong>!</li>
  <li><strong>[2025.12]</strong> 🎉🎉 Two papers <strong>UniHOI</strong> and <strong>EVOKE</strong> are accepted to <strong>AAAI 2026</strong>!</li>
  <li><strong>[2025.08]</strong> 🎉🎉 Our paper <strong>Pinpointing Visual Content</strong> is accepted to <strong>KBS 2025</strong>!</li>
  <li><strong>[2025.03]</strong> 🎉🎉 Our paper on 3D scene understanding (<strong>UniBVR</strong>) is accepted to <strong>Neurocomputing 2025</strong>.</li>
</ul>

📝 Selected Publications
======

<!-- update 论文+预览图 -->

<div class="paper-entry" style="display: flex; align-items: flex-start; gap: 18px; margin-bottom: 1.8rem;">
  <div style="flex: 0 0 170px;">
    <img src="/images/MUSE.png" alt="MUSE paper preview" style="width: 100%; border-radius: 8px; box-shadow: 0 2px 6px rgba(0,0,0,0.08);">
  </div>
  <div style="flex: 1;">
    <strong>MUSE: Resolving Manifold Misalignment in Visual Tokenization via Topological Orthogonality</strong><br>
    <em><strong>Panqi Yang</strong></em><br>
    <em>International Conference on Machine Learning (<strong>ICML</strong>), 2026</em><br>
    <span style="color: #4a627a; font-size: 0.9em;">We attribute the conflict between generation quality and semantic understanding in visual tokenizers to <em>manifold misalignment</em>, proposing a unified tokenizer decoupled in topological and semantic spaces.</span><br>
    <a href="https://arxiv.org/abs/2605.05646" style="font-weight: bold;">[Paper]</a> | <a href="https://github.com/panqiyang1/MUSE">[Code]</a>
  </div>
</div>

<div class="paper-entry" style="display: flex; align-items: flex-start; gap: 18px; margin-bottom: 1.8rem;">
  <div style="flex: 0 0 170px;">
    <img src="/images/UniHOI_preview.png" alt="UniHOI paper preview" style="width: 100%; border-radius: 8px; box-shadow: 0 2px 6px rgba(0,0,0,0.08);">
  </div>
  <div style="flex: 1;">
    <strong>UniHOI: Unified Human-Object Interaction Understanding via Unified Token Space</strong><br>
    <em><strong>Panqi Yang</strong>*, Haodong Jing*, Nanning Zheng, Yongqiang Ma</em><br>
    <em>AAAI Conference on Artificial Intelligence (<strong>AAAI</strong>), 2026</em><br>
    <span style="color: #4a627a; font-size: 0.9em;">A unified perspective treating HOI detection and generation as inverse problem modeling on a shared representation space, boosting rare HOI detection by 4.9%.</span><br>
    <a href="https://arxiv.org/abs/2511.15046" style="font-weight: bold;">[Paper]</a> | <a href="https://github.com/PanqiYang1/UniHOI_AAAI2026">[Code]</a>
  </div>
</div>

<div class="paper-entry" style="display: flex; align-items: flex-start; gap: 18px; margin-bottom: 1.8rem;">
  <div style="flex: 0 0 170px;">
    <img src="/images/UniBVR.png" alt="UniBVR paper preview" style="width: 100%; border-radius: 8px; box-shadow: 0 2px 6px rgba(0,0,0,0.08);">
  </div>
  <div style="flex: 1;">
    <strong>UniBVR: Balancing Visual and Reasoning Abilities in Unified 3D Scene Understanding</strong><br>
    <em><strong>Panqi Yang</strong></em><br>
    <em><strong>Neurocomputing</strong>, 2025</em><br>
    <span style="color: #4a627a; font-size: 0.9em;">Achieving SOTA on 7 benchmarks by learning a balanced 3D multimodal representation that serves both geometric perception and semantic reasoning.</span><br>
    <a href="https://www.sciencedirect.com/science/article/pii/S0925231225032710" style="font-weight: bold;">[Paper]</a> 
  </div>
</div>

*(For a full list of publications, please refer to my [Google Scholar](https://scholar.google.com/citations?user=2jocSAUAAAAJ&hl=zh-CN)).*

💼 Experience
======
*   **Xiaohongshu (RED)** | *Algorithm Research Intern* <span class="float-date">Apr. 2025 - Apr. 2026</span>

🤝 Collaboration & Contact
======
I am always open to profound discussions, academic collaborations, and exploring the true nature of intelligence. If you resonate with my research philosophy or have any questions about my work, please feel free to drop me an email!

<div class="contact-links">
  📧 <strong>Email:</strong> <a href="mailto:yangpq@stu.xjtu.edu.cn">yangpq@stu.xjtu.edu.cn</a> | <a href="mailto:1390849861@qq.com">1390849861@qq.com</a><br>
  📍 <strong>Location:</strong> Xi'an, China
</div>

<!-- 不蒜子计数器 JS -->
<script async src="//busuanzi.ibruce.info/busuanzi/2.3/busuanzi.pure.mini.js"></script>

<div style="text-align: center; margin-top: 3rem; padding-top: 1rem; border-top: 1px solid #eef2f6; font-size: 0.85rem; color: #6c7a8e;">
  <span id="busuanzi_container_site_pv" style="display: inline-block;">
    👀 总访问量 <span id="busuanzi_value_site_pv"></span> 次
  </span>
  &nbsp;|&nbsp;
  <span id="busuanzi_container_site_uv" style="display: inline-block;">
    🧑‍💻 访客数 <span id="busuanzi_value_site_uv"></span> 人
  </span>
</div>
