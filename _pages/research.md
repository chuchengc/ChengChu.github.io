---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---

<style>
:root {
  --research-card-bg: rgba(255, 255, 255, 0.55);
  --research-card-text: #333333;
  --research-card-border: rgba(0, 0, 0, 0.10);
  --research-card-shadow: 0 8px 24px rgba(0, 0, 0, 0.08);
}

html[data-theme="dark"],
body.dark,
body.dark-mode,
.dark {
  --research-card-bg: rgba(31, 37, 41, 0.55);
  --research-card-text: #f2f2f2;
  --research-card-border: rgba(255, 255, 255, 0.14);
  --research-card-shadow: 0 8px 24px rgba(0, 0, 0, 0.35);
}

@media (prefers-color-scheme: dark) {
  :root {
    --research-card-bg: rgba(31, 37, 41, 0.55);
    --research-card-text: #f2f2f2;
    --research-card-border: rgba(255, 255, 255, 0.14);
    --research-card-shadow: 0 8px 24px rgba(0, 0, 0, 0.35);
  }
}

.research-intro {
  margin-bottom: 2rem;
  line-height: 1.6;
}

.research-grid {
  display: flex;
  flex-direction: column;
  gap: 1.6rem;
  margin-top: 2rem;
}

.research-card {
  background: var(--research-card-bg);
  color: var(--research-card-text);

  border: 1px solid var(--research-card-border);
  border-radius: 16px;
  padding: 1.5rem 1.7rem;

  box-shadow: var(--research-card-shadow);
  backdrop-filter: blur(14px);
  -webkit-backdrop-filter: blur(14px);
}

.research-card h2 {
  margin-top: 0;
  margin-bottom: 0.8rem;
  font-size: 1.25rem;
  color: var(--research-card-text);
}

.research-card p {
  margin-bottom: 0;
  line-height: 1.65;
  color: var(--research-card-text);
}
</style>

<div class="research-intro">

My research focuses on quantum computing, with an emphasis on quantum computer architecture, quantum system security, and quantum machine learning. I am interested in building practical and secure quantum computing systems by jointly considering hardware characteristics, noise behavior, circuit design, and system-level optimization.

</div>

<div class="research-grid">

<div class="research-card">
  <h2>Quantum Computer Architecture</h2>
  <p>
    Quantum computer architecture focuses on building reliable, scalable, and efficient quantum computing systems by connecting quantum algorithms with the realities of physical hardware. My research studies how device constraints, gate fidelity, noise variation, qubit mapping, circuit scheduling, and execution time affect quantum program performance. By jointly considering architecture, compilation, and hardware-level error behavior, I aim to develop system-level techniques that improve the practicality of quantum computing on near-term and future devices.
  </p>
</div>

<div class="research-card">
  <h2>Quantum System Security</h2>
  <p>
    Quantum system security aims to uncover vulnerabilities in quantum computing systems and develop targeted defense strategies. Quantum computers have shown the potential to address important problems that are difficult or infeasible for classical computers, making them increasingly important for scientific discovery, optimization, machine learning, and secure computation. As quantum computing systems become more capable and widely accessible through cloud platforms, their security becomes a critical concern. This research direction examines how adversaries may exploit quantum noise, circuit structure, model behavior, compilation processes, and error mitigation workflows, while developing principled defenses to improve the robustness, reliability, and trustworthiness of emerging quantum platforms.
  </p>
</div>

</div>
