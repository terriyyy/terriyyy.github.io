---
permalink: /
title: ""
excerpt: "Yihang Lin — Undergraduate researcher in AI for Software Engineering at Nankai University."
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

<span class="anchor" id="about-me"></span>

<header class="home-intro">
  <p class="home-intro__eyebrow">AI for Software Engineering</p>
  <h1>Building dependable AI agents for real software systems.</h1>
  <p>I am an undergraduate student at <strong>Nankai University</strong>, interested in developing AI methods that make software engineering more reliable and autonomous.</p>
  <p>My research focuses on <strong>large language model (LLM) agents</strong>, <strong>automated software repair</strong>, and <strong>intelligent systems for software building and evaluation</strong>.</p>
</header>

<section class="portfolio-section" aria-labelledby="publications-heading">
  <span class="anchor" id="publications"></span>
  <div class="section-heading">
    <div>
      <p class="section-heading__eyebrow">Research</p>
      <h2 id="publications-heading">Selected Publication</h2>
    </div>
    <span class="section-heading__count">01</span>
  </div>

  <article class="work-card work-card--publication">
    <div class="work-card__visual">
      <img src="/images/publications/probe-ase26.jpg" alt="PROBE architecture: telemetry, diagnosis, and guidance layers form a recovery loop for failed agent runs" loading="lazy">
      <span class="work-card__venue">ASE 2026 · CCF A</span>
    </div>
    <div class="work-card__content">
      <p class="work-card__type">Core Contributor</p>
      <h3>Debugging the Debuggers: Failure-Anchored Structured Recovery for Software Engineering Agents</h3>
      <p class="work-card__authors">Chenyu Zhao, Shenglin Zhang<sup>*</sup>, <strong>Yihang Lin</strong>, Wenwei Gu, Zhimin Chen, Yongqian Sun, Dan Pei, Chetan Bansal, Saravan Rajmohan, Minghua Ma</p>
      <p class="work-card__summary">PROBE turns failed agent runs into recoverable evidence: it fuses telemetry to localize and diagnose failures, then injects grounded, actionable guidance through a gated recovery loop. Across 257 initially unresolved cases in three software-engineering settings, it improves both diagnosis and recovery over baseline approaches.</p>
      <div class="work-card__links">
        <a href="https://arxiv.org/abs/2605.08717" target="_blank" rel="noopener">Paper <span aria-hidden="true">↗</span></a>
      </div>
    </div>
  </article>
</section>

<section class="portfolio-section" aria-labelledby="projects-heading">
  <span class="anchor" id="projects"></span>
  <div class="section-heading">
    <div>
      <p class="section-heading__eyebrow">Selected Work</p>
      <h2 id="projects-heading">Projects</h2>
    </div>
    <span class="section-heading__count">04</span>
  </div>

  <div class="project-list">
    <article class="work-card">
      <div class="work-card__visual">
        <img src="/images/projects/agentops-rca.png" alt="Workflow for reflection-guided root-cause analysis of agent failures" loading="lazy">
        <span class="work-card__venue">Innovation Program</span>
      </div>
      <div class="work-card__content">
        <p class="work-card__type">Core Leader</p>
        <h3>Multimodal Monitoring and Automated RCA for AgentOps</h3>
        <p class="work-card__note">National Undergraduate Innovation Training Program · Selected as a municipal-level project</p>
        <p class="work-card__summary">This project develops a low-intrusion observability and diagnosis pipeline for LLM agents. It structures execution traces into aligned timelines, uses reflection-guided root-cause analysis to identify instruction drift, hallucinations, and tool-use failures, and closes the loop by translating verified diagnoses into prompt- and tool-level repair guidance.</p>
      </div>
    </article>

    <article class="work-card">
      <div class="work-card__visual">
        <img src="/images/projects/buildbench.png" alt="Iterative package-build repair and verification workflow used by BuildBench" loading="lazy">
        <span class="work-card__venue">ICSE 2027</span>
      </div>
      <div class="work-card__content">
        <p class="work-card__type">Team Member</p>
        <h3>ICSE 2027 Build-Bench Challenge Platform &amp; Preparation</h3>
        <p class="work-card__summary">Contributed to the preparation and platform development of the ICSE 2027 Build-Bench Challenge, where autonomous agents repair real package failures across x86_64, Arm64, and RISC-V environments. The platform evaluates patches by rebuilding clean packages on the target architecture, making successful compilation—not patch similarity—the central signal.</p>
        <div class="work-card__links">
          <a href="https://github.com/AIOps-Lab-NKU/BuildBench-Agent-Baseline" target="_blank" rel="noopener">Code <span aria-hidden="true">↗</span></a>
          <a href="https://arxiv.org/abs/2511.00780" target="_blank" rel="noopener">Paper <span aria-hidden="true">↗</span></a>
        </div>
      </div>
    </article>

    <article class="work-card">
      <div class="work-card__visual">
        <img src="/images/projects/bluecare.png" alt="BlueCare memory-companion flow from conversation and memory anchoring to story generation" loading="lazy">
        <span class="work-card__venue">Human-Centered AI</span>
      </div>
      <div class="work-card__content">
        <p class="work-card__type">Team Member</p>
        <h3>BlueCare: An AI Memory Companion for Older Adults</h3>
        <p class="work-card__summary">BlueCare is an AI memory companion shaped by field interviews with older adults. It brings conversations, photographs, relationships, and life events into a structured personal memory for personalized recall and story generation, while exploring offline and on-device capabilities to improve accessibility and protect sensitive personal data.</p>
        <div class="work-card__links">
          <a href="https://github.com/Nk-Five-Musketeers/aigc_five_men_team" target="_blank" rel="noopener">Code <span aria-hidden="true">↗</span></a>
        </div>
      </div>
    </article>

    <article class="work-card">
      <div class="work-card__visual">
        <img src="/images/projects/knowledge-graph-rag.png" alt="Knowledge-graph question-answering interface with an interactive entity graph" loading="lazy">
        <span class="work-card__venue">Knowledge Systems</span>
      </div>
      <div class="work-card__content">
        <p class="work-card__type">Team Member</p>
        <h3>Knowledge Graph-Enhanced RAG System</h3>
        <p class="work-card__summary">A full-stack knowledge system that combines interactive question answering with graph-aware recommendation. A Vue 3 interface visualizes entity relationships, while a Python backend ranks connected entities by graph weights to surface relevant concepts and support transparent, structure-aware retrieval.</p>
        <div class="work-card__links">
          <a href="https://github.com/terriyyy/Knowledge-Graph-enhanced-RAG-System" target="_blank" rel="noopener">Code <span aria-hidden="true">↗</span></a>
        </div>
      </div>
    </article>
  </div>
</section>

<footer class="home-footer">
  <span>Yihang Lin · Nankai University</span>
  <a href="mailto:2413578@mail.nankai.edu.cn">Let’s talk about reliable software agents <span aria-hidden="true">↗</span></a>
</footer>
