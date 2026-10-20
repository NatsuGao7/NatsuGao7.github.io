
---
layout: page
title: Projects
permalink: /projects/
description: "Exploring practical AI solutions that bridge cutting-edge research and real-world applications."
nav: true
nav_order: 3
---

<style>
.featured-project {
  display: grid;
  grid-template-columns: 40% 1fr;
  gap: 30px;
  padding: 26px;
  margin-top: 30px;
  border: 1px solid var(--global-divider-color);
  border-radius: 14px;
  background: var(--global-card-bg-color);
  align-items: start;
}

.featured-project img {
  display: block;
  width: 100%;
  height: auto;
  border-radius: 8px;
  object-fit: contain;
}

.featured-project h2 {
  font-size: 1.65rem;
  font-weight: 700;
  margin: 8px 0 12px;
}

.featured-project h3 {
  font-size: 1rem;
  font-weight: 700;
  margin: 18px 0 7px;
}

.featured-project p {
  font-size: 0.92rem;
  line-height: 1.7;
  margin-bottom: 12px;
}

.project-label {
  font-size: 0.76rem;
  font-weight: 700;
  letter-spacing: 0.8px;
  color: var(--global-theme-color);
}

.project-tags {
  margin-top: 15px;
  font-size: 0.82rem;
  color: var(--global-text-color);
  opacity: 0.75;
}

.project-link {
  display: inline-block;
  padding: 9px 18px;
  margin: 18px 8px 0 0;
  border: 1px solid var(--global-theme-color);
  border-radius: 7px;
  color: var(--global-theme-color);
  font-size: 0.88rem;
  font-weight: 600;
  text-decoration: none;
  transition: all 0.2s ease;
}

.project-link:hover {
  background: var(--global-theme-color);
  color: var(--global-bg-color);
  text-decoration: none;
}

@media (max-width: 768px) {
  .featured-project {
    grid-template-columns: 1fr;
    gap: 20px;
    padding: 18px;
  }
}
</style>

<div class="featured-project">

  <div>
    <img
      src="/assets/img/publication_preview/medbench.png"
      alt="MedBench v5 Framework"
      loading="lazy"
    >
  </div>

  <div>
    <div class="project-label">
      FEATURED PROJECT · SHANGHAI AI LAB · 2026
    </div>

    <h2>MedBench v5</h2>

    <p>
      <strong>
        A Dynamic, Process-Oriented, and Hallucination-Aware
        Benchmark for Clinical Multimodal Models
      </strong>
    </p>

    <h3>Project Overview</h3>

    <p>
      MedBench v5 is a Chinese medical AI benchmarking platform
      designed to systematically evaluate the clinical capabilities
      and safety of large language models. It extends conventional
      answer-based evaluation toward dynamic clinical reasoning,
      process-level assessment, and hallucination awareness.
    </p>

    <h3>My Contributions</h3>

    <p>
      Led the design of the dynamic clinical reasoning evaluation
      module, developing three controllable information-flow
      perturbations (missing information, conflicting evidence,
      and delayed evidence), a five-stage reasoning audit framework,
      and hallucination propagation monitoring for multi-turn
      clinical decision-making.
    </p>

    <div class="project-tags">
      Medical LLMs · Clinical Reasoning · Benchmarking ·
      Hallucination Evaluation
    </div>

    <div>
      <a
        class="project-link"
        href="https://arxiv.org/abs/2606.24155"
        target="_blank"
        rel="noopener noreferrer"
      >
        Paper ↗
      </a>
    </div>
  </div>

</div>
