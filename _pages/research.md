---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---

<style>
:root {
  --research-card-bg: #ffffff;
  --research-card-text: #333333;
  --research-card-border: #e5e5e5;
  --research-card-shadow: 0 4px 14px rgba(0, 0, 0, 0.08);
  --research-image-bg: #f2f2f2;
}

/* 如果网站切到 dark mode，就自动改变量 */
html[data-theme="dark"],
body.dark,
body.dark-mode,
.dark {
  --research-card-bg: #1f2529;
  --research-card-text: #f2f2f2;
  --research-card-border: rgba(255, 255, 255, 0.10);
  --research-card-shadow: 0 4px 14px rgba(0, 0, 0, 0.30);
  --research-image-bg: #2b3136;
}

/* 如果站点没有显式主题标记，就跟随系统主题 */
@media (prefers-color-scheme: dark) {
  :root {
    --research-card-bg: #1f2529;
    --research-card-text: #f2f2f2;
    --research-card-border: rgba(255, 255, 255, 0.10);
    --research-card-shadow: 0 4px 14px rgba(0, 0, 0, 0.30);
    --research-image-bg: #2b3136;
  }
}

.research-intro {
  margin-bottom: 2rem;
  line-height: 1.6;
}

.research-grid {
  display: flex;
  flex-direction: column;
  gap: 1.8rem;
  margin-top: 2rem;
}

.research-card {
  display: flex;
  align-items: center;
  gap: 1.5rem;

  background: var(--research-card-bg);
  color: var(--research-card-text);

  border-radius: 12px;
  padding: 1.4rem 1.6rem;
  border: 1px solid var(--research-card-border);
  box-shadow: var(--research-card-shadow);
}

.research-card img {
  width: 240px;
  height: 165px;
  object-fit: cover;
  border-radius: 10px;
  flex-shrink: 0;
  background: var(--research-image-bg);
}

.research-text {
  flex: 1;
}

.research-text h2 {
  margin-top: 0;
  margin-bottom: 0.7rem;
  font-size: 1.25rem;
  color: var(--research-card-text);
}

.research-text p {
  margin-bottom: 0;
  line-height: 1.6;
  color: var(--research-card-text);
}

@media (max-width: 768px) {
  .research-card {
    flex-direction: column;
    align-items: flex-start;
  }

  .research-card img {
    width: 100%;
    height: auto;
  }
}
</style>


<div class="research-intro">

My research focuses on quantum computing, with an emphasis on quantum computer architecture, quantum system security, and quantum machine learning. I am interested in building practical and secure quantum computing systems by jointly considering hardware characteristics, noise behavior, circuit design, and system-level optimization.

</div>

<div class="research-grid">


<div class="research-card">
  <img src="/images/quantum_architecture.jpg" alt="Quantum Computer Architecture">

  <div class="research-text">
    <h2>Quantum Computer Architecture</h2>
    <p>
      Quantum computer architecture focuses on building reliable, scalable and efficient quantum computing systems by connecting quantum algorithms with the realities of physical hardware. My research studies how device constraints, gate fidelity, noise variation, qubit mapping, circuit scheduling, and execution time affect quantum program performance. By jointly considering architecture, compilation, and hardware-level error behavior, I aim to develop system-level techniques that improve the practicality of quantum computing on near-term and future devices.
    </p>
  </div>
</div>


<div class="research-card">
  <img src="/images/quantum_security.jpg" alt="Quantum System Security">

  <div class="research-text">
    <h2>Quantum System Security</h2>
    <p>
      Quantum system security aims to uncover vulnerabilities in quantum computing systems and develop targeted defense strategies. Quantum computers have shown the potential to address important problems that are difficult or infeasible for classical computers, making them increasingly important for scientific discovery, optimization, machine learning, and secure computation. As quantum computing systems become more capable and widely accessible through cloud platforms, their security becomes a critical concern. This research direction examines how adversaries may exploit quantum noise, circuit structure, model behavior, compilation processes, and error mitigation workflows, while developing principled defenses to improve the robustness, reliability, and trustworthiness of emerging quantum platforms.
    </p>
  </div>
</div>





</div>
