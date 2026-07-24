---
permalink: /
title: "Junshuo Zhang"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

Hi! I am a Master's student in Computer Science at the University of Electronic Science and Technology of China (UESTC), where I am a member of the Spatiotemporal Big Data and Intelligence Team, supervised by Prof. Shen Gao. My research interests include **LLM-based Agents**, **Reinforcement Learning**, and **Information Retrieval**. 

During my undergraduate studies, I participated in research on embodied intelligence technology for humanoid robots, led by Changjiang Scholar Prof. Jiafu Tang, supervised by Prof. Ming Gao.

## 📣 News

- **[2026.05]** 🎮 Reached peak 2000 points and Legendary King tier in Honor of Kings S43.
- **[2026.03]** 🎉 Our paper *DPEPO* was accepted to **ACL 2026**!
- **[2026.02]** 🎮 Achieved C6 Columbia in Genshin Impact — My second C6 character after Furina.

## 📝 Publications

<style>
.paper-box {
  display: flex;
  justify-content: flex-start;
  align-items: flex-start;
  margin: 1.5em 0;
}
.paper-box-image {
  flex: 0 0 25%;
  max-width: 200px;
  padding-right: 20px;
}
.paper-box-image .badge {
  background-color: #4a90d9;
  color: white;
  padding: 3px 8px;
  border-radius: 4px;
  font-size: 0.75rem;
  font-weight: 600;
  display: inline-block;
  margin-bottom: 6px;
}
.paper-box-text {
  flex: 1;
}
@media (max-width: 768px) {
  .paper-box {
    flex-direction: column;
  }
  .paper-box-image {
    max-width: 100%;
    padding-right: 0;
    padding-bottom: 10px;
  }
}
</style>

<div class="paper-box">
  <div class="paper-box-image">
    <div>
      <div class="badge">ACL 2026</div>
      <img src="/images/DPEPO.png" alt="DPEPO" width="100%">
    </div>
  </div>
  <div class="paper-box-text">
    <p><strong>DPEPO: Diverse Parallel Exploration Policy Optimization for LLM-based Agents</strong></p>
    <p><strong>Junshuo Zhang</strong>, Chengrui Huang, Feng Guo, Zihan Li, Ke Shi, Jiguo Yu, Shuo Shang, Shen Gao</p>
    <p>[<a href="https://aclanthology.org/2026.acl-long.2151/">paper</a>]</p>
    <ul>
      <li>Proposes DPEPO, a novel agent exploration paradigm that enables simultaneous exploration of multiple environments for information acquisition and action execution, coupled with a diversity-driven reward mechanism to encourage efficient and diverse exploration during RL training.</li>
      <li>Achieves state-of-the-art (SOTA) results on ALF-World and ScienceWorld, with demonstrated strong robustness and generalization on out-of-domain tasks.</li>
    </ul>
  </div>
</div>

<div class="paper-box">
  <div class="paper-box-image">
    <div>
      <div class="badge">In Progress</div>
      <img src="/images/HTTA.png" alt="HTAA" width="100%">
    </div>
  </div>
  <div class="paper-box-text">
    <p><strong>HTAA: Enhancing LLM Planning via Hybrid Toolset Agentization & Adaptation</strong></p>
    <p>Chengrui Huang, <strong>Junshuo Zhang</strong>, Zhiyuan Ma, Xikun Wang, Ximeng Wang, Menghua Jiang, Gang Zeng, Zhaobin Han, Shen Gao, Shuo Shang</p>
    <p>[<a href="https://arxiv.org/abs/2604.10917">arXiv</a>]</p>
    <ul>
      <li>Proposes HTAA, a hierarchical framework that encapsulates frequently co-used tools into specialized agent tools, thereby reducing the planner's action space and mitigating redundancy.</li>
      <li>Introduces Asymmetric Planner Adaptation, aligning the planner with agent tools via trajectory-based backward reconstruction and forward refinement.</li>
      <li>Achieves SOTA performance on real-world POI validation tasks and standard benchmarks, significantly reducing length of trajectories and context overhead compared to strong baselines.</li>
    </ul>
  </div>
</div>

<div class="paper-box">
  <div class="paper-box-image">
    <div>
      <div class="badge">In Progress</div>
      <img src="/images/HTTA.png" alt="LADT" width="100%">
    </div>
  </div>
  <div class="paper-box-text">
    <p><strong>LADT: Hierarchical Tree-Guided Grounding for GUI Localization via Ancestor-Descendant Traversal</strong></p>
    <p><strong>Junshuo Zhang</strong>, Ke Shi, Jinyuan Zhang, Chengrui Huang, Zhaobing Han, Gang Zeng, Menghua Jiang, Ximeng Wang, Meng Wang, Shuo Shang, Shen Gao</p>
    <ul>
      <li>Proposes LADT, a novel paradigm that localizes GUI elements via iterative ancestor-to-descendant traversal of the DOM tree to enable coarse-to-fine grounding, and designs a Subsumption-Aware Hierarchical Reward that combines sparse inbox rewards with dense structural penalties to enforce coherent localization paths and correct containment relationships.</li>
      <li>Achieves SOTA performance on three Web/GUI benchmarks with strong cross-platform generalization.</li>
    </ul>
  </div>
</div>

<div class="paper-box">
  <div class="paper-box-image">
    <div>
      <div class="badge">AAAI 2026</div>
      <img src="/images/Unlearn.png" alt="Beyond Superficial Forgetting" width="100%">
    </div>
  </div>
  <div class="paper-box-text">
    <p><strong>Beyond Superficial Forgetting: Thorough Unlearning Through Knowledge Density Estimation and Block Re-Insertion</strong></p>
    <p>Feng Guo, Yuntao Wen, Shen Gao, <strong>Junshuo Zhang</strong>, Shuo Shang</p>
    <ul>
      <li>Proposes KUnBR, a novel machine unlearning framework designed to thoroughly remove harmful knowledge from LLMs.</li>
      <li>Leverages Knowledge Density Estimation to pinpoint the layers richest in harmful knowledge, and a Block Re-insertion strategy for thorough unlearning.</li>
      <li>Achieves state-of-the-art performance on unlearning benchmarks, robustly resisting knowledge recovery while preserving model general utility.</li>
    </ul>
  </div>
</div>

<div class="paper-box">
  <div class="paper-box-image">
    <div>
      <div class="badge">SIGIR 2026</div>
      <img src="/images/FAVE.png" alt="FAVE" width="100%">
    </div>
  </div>
  <div class="paper-box-text">
    <p><strong>FAVE: Flow-based Average Velocity Establishment for Sequential Recommendation</strong></p>
    <p>Ke Shi, Yao Zhang, Feng Guo, Jinyuan Zhang, <strong>Junshuo Zhang</strong>, Shen Gao, Shuo Shang</p>
    <p>[<a href="https://arxiv.org/abs/2604.04427">arXiv</a>]</p>
    <ul>
      <li>Proposes FAVE, a flow-based average velocity establishment approach aimed at improving sequential recommendation systems.</li>
    </ul>
  </div>
</div>

<div class="paper-box">
  <div class="paper-box-image">
    <div>
      <div class="badge">arXiv 2024</div>
      <img src="/images/LLM_Embed.png" alt="LLMs are also effective embedding models" width="100%">
    </div>
  </div>
  <div class="paper-box-text">
    <p><strong>LLMs are also effective embedding models: An in-depth overview</strong></p>
    <p>Chongyang Tao, Tao Shen, Shen Gao, <strong>Junshuo Zhang</strong>, Zhen Li, Kai Hua, Wenpeng Hu, Zhengwei Tao, Shuai Ma</p>
    <p>[<a href="https://arxiv.org/abs/2412.12591">arXiv</a>]</p>
    <ul>
      <li>Conducted a comprehensive survey spanning from established text embedding methods to advanced embedding techniques in multilingual, long-context, and cross-modal domains.</li>
      <li>Systematizes the paradigm shift from specialized encoders like BERT to general-purpose LLMs for generating high-quality text embeddings.</li>
      <li>Systematically summarizes and categorizes two core methodologies: direct prompting for tuning-free embeddings and data-centric fine-tuning to optimize model with diverse objectives and datasets.</li>
    </ul>
  </div>
</div>

## 🏆 Honors & Awards

- **Academic Scholarship**, 2025
- **Model Student Scholarship**, 2024
- **The First Prize Scholarship**, 2023
