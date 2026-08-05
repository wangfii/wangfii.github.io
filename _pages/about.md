---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

<span class="anchor" id="about-me"></span>
# 👋 About Me

I am a **Master's candidate** in Computer Science (Software Engineering) at **Anhui Polytechnic University**, supervised by Prof. Guo-Fu Lu. My research focuses on **multi-view clustering**, where I develop efficient and scalable algorithms that fuse heterogeneous information from multiple views.

My work addresses core challenges in multi-view clustering — computational complexity, complementary information utilization across views, and high-order structural relationship modeling. I build anchor graph-based frameworks enhanced with **tensor low-rank constraints**, **multi-scale fusion**, **anchor-side filtering**, and **adaptive regularization** to improve both clustering accuracy and scalability.

I have published **5 first-author SCI papers** in top-tier journals including *Pattern Recognition*, *Neural Networks*, *Knowledge-Based Systems*, and *Neurocomputing*. I am proficient in the complete research pipeline — from problem analysis and model design to experimental validation and paper writing.

I am always open to discussions and collaborations. Feel free to drop me an email!


<span class="anchor" id="news"></span>
# 📰 News

<div class="timeline-container">
  <div class="timeline-item">
    <div class="timeline-date">2026.05.30</div>
    <div class="timeline-content">One paper accepted by <strong>Pattern Recognition</strong>: "Tensorized Anchor Graphs with Multi-Scale Learning for One-Step Multi-View Clustering" (CCF B, 中科院一区).</div>
  </div>
  <div class="timeline-item">
    <div class="timeline-date">2026.04.27</div>
    <div class="timeline-content">One paper accepted by <strong>Pattern Recognition</strong>: "Tensorized Pure Nonlinear Anchor Graph Learning for Multi-View Clustering" (CCF B, 中科院一区).</div>
  </div>
  <div class="timeline-item">
    <div class="timeline-date">2025.09.12</div>
    <div class="timeline-content">One paper accepted by <strong>Neurocomputing</strong>: "Fused Adaptive Tensor Log-Determinant and Local Smoothness Regularizer for Multi-View Clustering" (CCF C, 中科院二区).</div>
  </div>
  <div class="timeline-item">
    <div class="timeline-date">2025.05.21</div>
    <div class="timeline-content">One paper accepted by <strong>Neural Networks</strong>: "Scalable One-Pass Multi-View Clustering with Tensorized Multiscale Bipartite Graphs Fusion" (CCF B, 中科院二区).</div>
  </div>
  <div class="timeline-item">
    <div class="timeline-date">2025.05.18</div>
    <div class="timeline-content">One paper accepted by <strong>Knowledge-Based Systems</strong>: "Unlocking Deep Structures: Anchor-Side Filtering for Efficient Multiview Clustering" (CCF C, 中科院一区).</div>
  </div>
  <div class="timeline-item">
    <div class="timeline-date">2024.09</div>
    <div class="timeline-content">Started M.S. in Computer Science at Anhui Polytechnic University, advised by Prof. Guo-Fu Lu.</div>
  </div>
</div>

<style>
/* News Timeline Styling */
.timeline-container {
  position: relative;
  padding-left: 20px;
  border-left: 2px solid #e1e4e8;
  margin-bottom: 30px;
  margin-left: 8px;
}
.timeline-item { position: relative; margin-bottom: 16px; }
.timeline-item::before {
  content: ''; position: absolute; left: -27px; top: 5px;
  width: 12px; height: 12px; background-color: #0366d6;
  border-radius: 50%; border: 2px solid #fff;
}
.timeline-date { font-weight: 600; color: #0366d6; font-size: 0.95em; margin-bottom: 2px; }
.timeline-content { font-size: 0.95em; color: #24292e; }

/* Global Paper Box Hover Effect */
.paper-box {
  display: flex;
  margin-bottom: 24px;
  border-radius: 8px;
  padding: 14px;
  border: 1px solid #ececec;
  background-color: #ffffff;
  transition: transform 0.25s cubic-bezier(0.2, 0.8, 0.2, 1), box-shadow 0.25s cubic-bezier(0.2, 0.8, 0.2, 1);
}
.paper-box:hover {
  transform: translateY(-3px);
  box-shadow: 0 10px 24px rgba(0, 0, 0, 0.08);
  border-color: #e2e8f0;
}
.paper-box-image {
  flex: 0 0 32%;
  margin-right: 18px;
  border-radius: 8px;
  overflow: hidden;
  position: relative;
  transform: translateZ(0);
}
.paper-box-image video, .paper-box-image img {
  width: 100%;
  height: 100%;
  object-fit: cover;
  display: block;
}
.paper-box-text { flex: 1; }
.paper-box-text .title {
  font-weight: 600;
  font-size: 1.06em;
  color: #1f2d3d;
  text-decoration: none;
  transition: color 0.2s ease;
}
.paper-box-text .title:hover { color: #0366d6; }
.paper-box-text .authors { margin: 4px 0 3px 0; color: #333; font-size: 0.95em; }
.paper-box-text .venue { margin-bottom: 4px; color: #555; font-size: 0.95em; }
.paper-box-text .desc { font-size: 0.9em; margin: 6px 0 8px 0; color: #444; }
.paper-box-text .links a {
  margin-right: 10px;
  font-size: 0.9em;
  font-weight: 500;
  color: #0366d6;
  text-decoration: none;
}
.paper-box-text .links a:hover { text-decoration: underline; color: #005cc5; }
.badge {
  position: absolute; top: 6px; left: 6px;
  background: rgba(0, 0, 0, 0.72); color: #fff;
  padding: 2px 6px; border-radius: 4px; font-size: 0.75em;
  backdrop-filter: blur(4px);
}

/* Education & Experience Cards */
.exp-card {
  display: flex; align-items: flex-start;
  background: #fdfdfd; border: 1px solid #eaeaea;
  border-radius: 8px; padding: 16px; margin-bottom: 16px;
  transition: background-color 0.2s;
}
.exp-card:hover { background: #f8f9fa; }
.exp-logo {
  width: 72px;
  height: 72px;
  flex-shrink: 0;
  margin-right: 18px;
  border-radius: 4px;
  object-fit: contain;
}
.exp-content { flex-grow: 1; display: flex; flex-direction: column; justify-content: center; min-height: 72px; }
.exp-header { display: flex; justify-content: space-between; align-items: center; margin-bottom: 4px; }
.exp-role { font-weight: 600; font-size: 1.05em; color: #24292e; margin: 0; }
.exp-time { font-size: 0.9em; color: #586069; white-space: nowrap; }
.exp-org { font-weight: 500; color: #0366d6; font-size: 0.95em; margin-bottom: 6px; }
.exp-desc { font-size: 0.9em; color: #444; margin: 0; line-height: 1.5; }

/* Highlights & Collapsible */
.highlight-award { font-weight: 600; color: #b31b1b; background: #fff0f0; padding: 2px 6px; border-radius: 4px; }
.highlight-honor { font-weight: 600; color: #005cc5; background: #f0f8ff; padding: 2px 6px; border-radius: 4px; }

.zh-translation { font-size: 0.85em; color: #666; font-weight: normal; }
</style>


<span class="anchor" id="education"></span>
# 🎓 Education

<div class="exp-card">
  <img src="{{ '/images/building-icon.svg' | relative_url }}" class="exp-logo" alt="University">
  <div class="exp-content">
    <div class="exp-header">
      <h3 class="exp-role">M.S. in Computer Science (Software Engineering)</h3>
      <span class="exp-time">2024.09 - Present</span>
    </div>
    <div class="exp-org">Anhui Polytechnic University</div>
    <p class="exp-desc">Academic Master's degree. Research on multi-view clustering advised by Prof. Guo-Fu Lu.</p>
  </div>
</div>

<div class="exp-card">
  <img src="{{ '/images/building-icon.svg' | relative_url }}" class="exp-logo" alt="University">
  <div class="exp-content">
    <div class="exp-header">
      <h3 class="exp-role">B.E. in Computer Science (Software Engineering)</h3>
      <span class="exp-time">2020.09 - 2024.07</span>
    </div>
    <div class="exp-org">Anhui Polytechnic University</div>
    <p class="exp-desc">Graduated in the <strong>top 10%</strong> of the program. Passed CET-6. Solid foundation in computer science and software engineering.</p>
  </div>
</div>


<span class="anchor" id="publications"></span>
# 📝 Publications

<p style="font-size: 0.9em; color: #666; margin-top: -10px; margin-bottom: 20px;">
  5 first-author SCI papers
</p>

<div class='paper-box'>
  <div class='paper-box-image'>
    <div class='badge'>CCF B · 中科院一区</div>
    <img src="{{ '/images/project-placeholder.svg' | relative_url }}" alt="Publication">
  </div>
  <div class='paper-box-text'>
    <a href="https://doi.org/10.1016/j.patcog.2026.114144" class="title">Tensorized Anchor Graphs with Multi-Scale Learning for One-Step Multi-View Clustering</a>
    <div class="authors"><strong>Fei Wang</strong>, Guo-Fu Lu</div>
    <div class="venue"><em><strong>Pattern Recognition</strong>, vol. 180, 2026, 114144</em></div>
    <p class="desc"><strong>TL;DR:</strong> Proposes a one-step multi-view clustering method using tensorized anchor graphs with multi-scale learning.</p>
    <div class="links">
      <a href="https://doi.org/10.1016/j.patcog.2026.114144">[Paper]</a>
    </div>
  </div>
</div>

<div class='paper-box'>
  <div class='paper-box-image'>
    <div class='badge'>CCF B · 中科院一区</div>
    <img src="{{ '/images/project-placeholder.svg' | relative_url }}" alt="Publication">
  </div>
  <div class='paper-box-text'>
    <a href="https://doi.org/10.1016/j.patcog.2026.113876" class="title">Tensorized Pure Nonlinear Anchor Graph Learning for Multi-View Clustering</a>
    <div class="authors"><strong>Fei Wang</strong>, Guo-Fu Lu</div>
    <div class="venue"><em><strong>Pattern Recognition</strong>, vol. 179, 2026, 113876</em></div>
    <p class="desc"><strong>TL;DR:</strong> Introduces tensorized pure nonlinear anchor graph learning for enhanced multi-view clustering performance.</p>
    <div class="links">
      <a href="https://doi.org/10.1016/j.patcog.2026.113876">[Paper]</a>
    </div>
  </div>
</div>

<div class='paper-box'>
  <div class='paper-box-image'>
    <div class='badge'>CCF C · 中科院一区</div>
    <img src="{{ '/images/project-placeholder.svg' | relative_url }}" alt="Publication">
  </div>
  <div class='paper-box-text'>
    <a href="https://doi.org/10.1016/j.knosys.2025.113810" class="title">Unlocking Deep Structures: Anchor-Side Filtering for Efficient Multiview Clustering on High-Order Bipartite Graphs</a>
    <div class="authors"><strong>Fei Wang</strong>, Guo-Fu Lu</div>
    <div class="venue"><em><strong>Knowledge-Based Systems</strong>, vol. 324, 2025, 113810</em></div>
    <p class="desc"><strong>TL;DR:</strong> Proposes anchor-side filtering for efficient multi-view clustering on high-order bipartite graphs.</p>
    <div class="links">
      <a href="https://doi.org/10.1016/j.knosys.2025.113810">[Paper]</a>
    </div>
  </div>
</div>

<div class='paper-box'>
  <div class='paper-box-image'>
    <div class='badge'>CCF B · 中科院二区</div>
    <img src="{{ '/images/project-placeholder.svg' | relative_url }}" alt="Publication">
  </div>
  <div class='paper-box-text'>
    <a href="https://doi.org/10.1016/j.neunet.2025.107669" class="title">Scalable One-Pass Multi-View Clustering with Tensorized Multiscale Bipartite Graphs Fusion</a>
    <div class="authors"><strong>Fei Wang</strong>, Guo-Fu Lu</div>
    <div class="venue"><em><strong>Neural Networks</strong>, vol. 190, 2025, 107669</em></div>
    <p class="desc"><strong>TL;DR:</strong> Develops a scalable one-pass multi-view clustering method with tensorized multiscale bipartite graph fusion.</p>
    <div class="links">
      <a href="https://doi.org/10.1016/j.neunet.2025.107669">[Paper]</a>
    </div>
  </div>
</div>

<div class='paper-box'>
  <div class='paper-box-image'>
    <div class='badge'>CCF C · 中科院二区</div>
    <img src="{{ '/images/project-placeholder.svg' | relative_url }}" alt="Publication">
  </div>
  <div class='paper-box-text'>
    <a href="https://doi.org/10.1016/j.neucom.2025.131564" class="title">Fused Adaptive Tensor Log-Determinant and Local Smoothness Regularizer for Multi-View Clustering</a>
    <div class="authors"><strong>Fei Wang</strong>, Guo-Fu Lu</div>
    <div class="venue"><em><strong>Neurocomputing</strong>, 2025, 131564</em></div>
    <p class="desc"><strong>TL;DR:</strong> Proposes fused adaptive tensor log-determinant and local smoothness regularization for multi-view clustering.</p>
    <div class="links">
      <a href="https://doi.org/10.1016/j.neucom.2025.131564">[Paper]</a>
    </div>
  </div>
</div>


<span class="anchor" id="honors-awards"></span>
# 🏆 Honors and Awards

- *2024-2025*, <span class="highlight-honor">National Scholarship</span> <span class="zh-translation">（国家奖学金）</span> & First-Class University Scholarship <span class="zh-translation">（校一等奖学金）</span>.
- *2020-2024*, <span class="highlight-honor">Anhui Heli Scholarship</span> <span class="zh-translation">（安徽合力奖学金）</span>, University Special Scholarship <span class="zh-translation">（校特等奖学金）</span>, and Outstanding Student Award <span class="zh-translation">（校三好学生）</span>.
- *2024.11*, 3rd Prize (East China Region), <span class="highlight-award">6th National University Computer Ability Challenge</span> <span class="zh-translation">（第六届全国高校计算机能力挑战赛华东赛区三等奖）</span>.
- *2023.04*, 2nd Prize, <span class="highlight-award">Anhui Province University Student Network and Distributed System Innovation Design Competition</span> <span class="zh-translation">（安徽省大学生网络与分布式系统创新设计大赛二等奖）</span>.
- *2022.07*, 3rd Prize (National Level), <span class="highlight-award">National University Student Computer Ability Challenge — AI Guide Dog</span> <span class="zh-translation">（全国大学生计算机能力挑战赛人工智能导盲犬全国三等奖）</span>.
- *2021.07*, 2nd Prize (National Level), <span class="highlight-award">16th National University Student Intelligent Car Competition — Intelligent Vision Group</span> <span class="zh-translation">（第十六届全国大学生智能汽车竞赛智能视觉组全国二等奖）</span>.

---

<div style="text-align: center; margin-top: 40px; padding-top: 20px; border-top: 1px solid #eaeaea; color: #888; font-size: 0.85em;">
  <p>Skills: Matlab · Python · PyTorch · LaTeX · VS Code · Origin</p>
  <p>Language: English CET-6</p>
</div>
