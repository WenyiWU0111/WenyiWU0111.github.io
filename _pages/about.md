---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

<span class='anchor' id='about-me'></span>

I am an incoming Ph.D. student at the [Halıcıoğlu Data Science Institute (HDSI)](https://datascience.ucsd.edu/), UC San Diego (Fall 2026), where I am fortunate to be advised by Prof. [Biwei Huang](https://biweihuang.com/) and mentored by [Kun Zhou](https://lancelot39.github.io/). Before that, I received my M.S. in Data Science from UC San Diego in March 2026, and my B.Sc. in Statistics (First Class Honors) from The Chinese University of Hong Kong in 2024.

My research aims to make **long-horizon agentic tasks controllable and reliable through a causal lens**, spanning **GUI agents**, **long-horizon planning**, and **multi-agent reinforcement learning**. My work follows one thread:

- **Memory** — equipping agents with scalable *continuous memory*, so that past experience is compactly reusable across unfamiliar interfaces and long horizons ([CoMEM](https://arxiv.org/abs/2505.17670), NeurIPS 2025; [CoMEM-Agent](https://arxiv.org/abs/2510.09038); [HyMEM](https://arxiv.org/abs/2603.10291), ACL 2026 Findings).
- **Planning** — identifying planning as the dominant factor behind long-horizon performance, and efficiently improving it by training only the planner with reinforcement learning in an unbalanced multi-agent framework ([Planner Matters!](https://arxiv.org/abs/2605.02168)).
- **Causal structure** — harnessing agents with a unified causal structure that maintains compact, verifiable task progress, enabling evidence-based completion, failure attribution, and recovery ([StructAgent](https://arxiv.org/abs/2607.11388)).

Going forward, I aim to tackle the central challenge of **long-horizon planning** for agents: through **verifiable state management** and **self-evolving memory and tools**, I want agents to truly cross the **sim-to-real** gap — moving beyond benchmarks to deliver real productivity in the wild.

I am always open to collaborations and happy to chat about agents, causality, and everything in between — feel free to reach out!


# 🔥 News
- *2026.07*: &nbsp;📄 New preprint: [StructAgent](https://arxiv.org/abs/2607.11388) — harnessing long-horizon digital agents with unified causal structure. [[Project page]](https://wenyiwu0111.github.io/structagent-page/)
- *2026.07*: &nbsp;🎉🎉 I will join [UC San Diego HDSI](https://datascience.ucsd.edu/) as a Ph.D. student in Fall 2026, advised by Prof. [Biwei Huang](https://biweihuang.com/)!
- *2026.05*: &nbsp;🎉🎉 [HyMEM](https://arxiv.org/abs/2603.10291) is accepted to **ACL 2026 Findings**!
- *2026.05*: &nbsp;📄 New preprint: [Planner Matters!](https://arxiv.org/abs/2605.02168) — planning is the dominant factor in long-horizon tasks; RL-training only the planner is enough.
- *2026.03*: &nbsp;🎓 I graduated with an M.S. in Data Science from UC San Diego.
- *2025.10*: &nbsp;📄 New preprint: [CoMEM-Agent](https://arxiv.org/abs/2510.09038) — continuous memory + an auto-scaling data flywheel (100k+ trajectories) for GUI agents.
- *2025.09*: &nbsp;🎉🎉 [CoMEM](https://arxiv.org/abs/2505.17670) is accepted at **NeurIPS 2025**!

# 📝 Publications 

(⭐️ denotes first author)

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Preprint</div><img src='images/papers/structagent.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[StructAgent: Harness Long-horizon Digital Agents with Unified Causal Structure](https://arxiv.org/abs/2607.11388)

**Wenyi Wu**⭐️, Sibo Zhu, Kun Zhou, Aayush Salvi, Zixuan Song, Biwei Huang

*arXiv preprint arXiv:2607.11388, 2026*

[**Paper**](https://arxiv.org/abs/2607.11388) / [**Project Page**](https://wenyiwu0111.github.io/structagent-page/) / [**Code**](https://github.com/WenyiWU0111/StructAgent)
- A unified causal structure for long-horizon digital agents: a compact, verifiable task-progress state coupled with structured workflows, enabling checkpointing, evidence-based completion, and failure recovery. Improves multiple backbones on computer-use benchmarks and generalizes to Minecraft.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Under Review</div><img src='images/papers/planner.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Planner Matters! An Efficient and Unbalanced Multi-agent Collaboration Framework for Long-horizon Planning](https://arxiv.org/abs/2605.02168)

**Wenyi Wu**⭐️, Sibo Zhu, Kun Zhou, Biwei Huang

*arXiv preprint arXiv:2605.02168, 2026 (under review)*

[**Paper**](https://arxiv.org/abs/2605.02168) / [**Code**](https://github.com/WenyiWU0111/Planner-Matters-GUI-Agent)
- Decomposes long-horizon automation into planner / actor / memory-manager roles and shows planning is the dominant factor in task performance — so we RL-train *only* the planner, yielding efficient gains across web navigation, OS control, and tool use.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ACL 2026 Findings</div><img src='images/papers/hymem.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Hybrid Self-evolving Structured Memory for GUI Agents](https://arxiv.org/abs/2603.10291)

Sibo Zhu, **Wenyi Wu**, Kun Zhou, Stephen Wang, Biwei Huang

*Findings of the Association for Computational Linguistics: ACL 2026*

[**Paper**](https://arxiv.org/abs/2603.10291)
- HyMEM: a graph-based, self-evolving memory that couples symbolic nodes with continuous trajectory embeddings and supports multi-hop retrieval, letting small open-source backbones match or exceed closed-source models (e.g., Gemini 2.5 Pro, GPT-4o) on computer-use tasks.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Under Review</div><img src='images/papers/comem_agent.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Auto-scaling Continuous Memory for GUI Agent](https://arxiv.org/abs/2510.09038)

**Wenyi Wu**⭐️, Kun Zhou, Ruoxin Yuan, Vivian Yu, Stephen Wang, Zhiting Hu, Biwei Huang

*arXiv preprint arXiv:2510.09038, 2025 (under review)*

[**Paper**](https://arxiv.org/abs/2510.09038) / [**Code**](https://github.com/WenyiWU0111/CoMEM-Agent) / [**Dataset**](https://huggingface.co/datasets/WenyiWU0111/CoMEM-agent-memory-trajectories)
- Encodes each GUI trajectory into fixed-length continuous embeddings (the VLM as its own encoder), sharply cutting context cost while preserving fine-grained visual cues; an auto-scaling data flywheel collects 100k+ trajectories, bringing Qwen2.5-VL-7B to the level of closed-source SOTA agents.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">NeurIPS 2025</div><img src='images/papers/comem.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Towards General Continuous Memory for Vision-Language Models](https://arxiv.org/abs/2505.17670)

**Wenyi Wu**⭐️, Zixuan Song, Kun Zhou, Yifei Shao, Zhiting Hu, Biwei Huang

*Advances in Neural Information Processing Systems (NeurIPS), 2025*

[**Paper**](https://arxiv.org/abs/2505.17670) / [**Code**](https://github.com/WenyiWU0111/CoMEM)
- CoMEM represents multimodal and multilingual knowledge as a compact set of dense embeddings instead of long token sequences — the key insight being that a VLM can serve as its own continuous memory encoder — with data- and parameter-efficient fine-tuning improving complex multimodal reasoning.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Preprint</div><img src='images/papers/causalcopilot.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Causal-Copilot: An Autonomous Causal Analysis Agent](https://arxiv.org/abs/2504.13263)

Xinyue Wang, Kun Zhou, **Wenyi Wu**, Har Simrat Singh, Fang Nan, Songyao Jin, Aryan Philip, Saloni Patnaik, Hou Zhu, Shivam Singh, Parjanya Prashant, Qian Shen, Biwei Huang

*arXiv preprint arXiv:2504.13263, 2025*

[**Paper**](https://arxiv.org/abs/2504.13263) / [**Code**](https://github.com/Lancelot39/Causal-Copilot) / [**Demo**](https://causalcopilot.com)
- An autonomous LLM agent that operationalizes expert-level causal analysis end-to-end — causal discovery, inference, algorithm selection, hyperparameter tuning, and interpretation — integrating 20+ state-of-the-art causal methods behind a natural-language interface.
</div>
</div>

# 📖 Educations
- *2026.09 – (expected 2030)*, Ph.D., Halıcıoğlu Data Science Institute, UC San Diego. Advisor: Prof. [Biwei Huang](https://biweihuang.com/).
- *2024.09 – 2026.03*, M.S. in Data Science, UC San Diego.
- *2020.09 – 2024.07*, B.Sc. in Statistics (First Class Honors), The Chinese University of Hong Kong.

# 🐱 Life

Beyond research, I am a devoted cat lover 🐈, and **baking** 🍰 and **crocheting** 🧶 are my favorite *me time*.

I am deeply grateful for my happy family, my beloved husband, and my dear friends — their love, support, and companionship have filled my life in California with beautiful memories ☀️.

<div class="photo-strip">
  <div class="photo-track">
    {% for img in site.static_files %}{% if img.path contains '/images/life/' %}<img src="{{ img.path | relative_url }}" alt="life" loading="lazy">{% endif %}{% endfor %}
    {% for img in site.static_files %}{% if img.path contains '/images/life/' %}<img src="{{ img.path | relative_url }}" alt="life" loading="lazy">{% endif %}{% endfor %}
  </div>
</div>

<style>
.photo-strip {
  overflow: hidden;
  padding: 6px 0 10px;
  position: relative;
}
.photo-track {
  display: flex;
  width: max-content;
  animation: strip-scroll 45s linear infinite;
}
.photo-track img {
  height: 220px;
  width: auto;
  flex: 0 0 auto;
  border-radius: 10px;
  margin-right: 12px;
  box-shadow: 0 1px 4px rgba(0,0,0,0.15);
}
.photo-strip:hover .photo-track { animation-play-state: paused; }
@keyframes strip-scroll {
  from { transform: translateX(0); }
  to { transform: translateX(-50%); }
}
</style>
