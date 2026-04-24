---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---

<style>
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
  background: #1f2529;
  border-radius: 8px;
  padding: 1.4rem 1.6rem;
  box-shadow: 0 2px 8px rgba(0, 0, 0, 0.25);
  border: 1px solid rgba(255, 255, 255, 0.08);
}

.research-card img {
  width: 220px;
  height: 150px;
  object-fit: cover;
  border-radius: 6px;
  flex-shrink: 0;
}

.research-text {
  flex: 1;
}

.research-text h2 {
  margin-top: 0;
  margin-bottom: 0.7rem;
  font-size: 1.25rem;
  color: #ffffff;
}

.research-text p {
  margin-bottom: 0;
  line-height: 1.6;
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

@media (prefers-color-scheme: light) {
  .research-card {
    background: #f7f7f7;
    border: 1px solid #e0e0e0;
    box-shadow: 0 2px 8px rgba(0, 0, 0, 0.08);
  }

  .research-text h2 {
    color: #222222;
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
