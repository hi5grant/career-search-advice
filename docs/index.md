---
title: Career Search Advice
---

Finding a job gets harder every year. Put AI to work on the parts that consume the most time: make sense of your experience, research opportunities, and build a resume that speaks to each role. A better-targeted resume gives the right experience a better chance to be seen.

<div class="career-flow" role="img" aria-label="Career workflow: past resumes feed an AI interview, which builds a master career inventory that branches into tailored resumes for different opportunities.">
  <svg viewBox="0 0 1000 390" xmlns="http://www.w3.org/2000/svg" role="presentation" focusable="false">
    <defs>
      <marker id="career-arrow" markerWidth="9" markerHeight="9" refX="7" refY="4.5" orient="auto">
        <path d="M0 0 L9 4.5 L0 9 Z" fill="currentColor" />
      </marker>
    </defs>
    <g fill="none" stroke="currentColor" stroke-width="2" opacity=".55" marker-end="url(#career-arrow)">
      <path d="M205 104 H255" />
      <path d="M435 104 H485" />
      <path d="M665 104 H710 V48 H755" />
      <path d="M710 104 V132 H755" />
      <path d="M710 132 V216 H755" />
      <path d="M710 216 V300 H755" />
    </g>
    <g font-family="inherit" text-anchor="middle">
      <rect x="25" y="62" width="180" height="84" rx="12" fill="#64748b" fill-opacity=".13" stroke="#64748b" stroke-width="1.5"/>
      <text x="115" y="96" font-size="17" font-weight="600" fill="currentColor">Your past resumes</text>
      <text x="115" y="120" font-size="12" fill="currentColor" opacity=".75">Starting material</text>

      <rect x="255" y="62" width="180" height="84" rx="12" fill="#0d9488" fill-opacity=".12" stroke="#0d9488" stroke-width="1.5"/>
      <text x="345" y="96" font-size="17" font-weight="600" fill="currentColor">AI interview</text>
      <text x="345" y="120" font-size="12" fill="currentColor" opacity=".75">Explore and verify experience</text>

      <rect x="485" y="62" width="180" height="84" rx="12" fill="#2563eb" fill-opacity=".12" stroke="#2563eb" stroke-width="2"/>
      <text x="575" y="94" font-size="16" font-weight="700" fill="currentColor">Master career</text>
      <text x="575" y="115" font-size="16" font-weight="700" fill="currentColor">inventory</text>
      <text x="575" y="133" font-size="11" fill="currentColor" opacity=".75">Reusable source of truth</text>

      <g fill="#64748b" fill-opacity=".12" stroke="#64748b" stroke-width="1.3">
        <rect x="755" y="15" width="220" height="64" rx="10"/>
        <rect x="755" y="100" width="220" height="64" rx="10"/>
        <rect x="755" y="185" width="220" height="64" rx="10"/>
        <rect x="755" y="270" width="220" height="64" rx="10"/>
      </g>
      <g fill="currentColor" font-size="15" font-weight="600">
        <text x="865" y="53">Custom resume — Role A</text>
        <text x="865" y="138">Custom resume — Role B</text>
        <text x="865" y="223">Custom resume — Role C</text>
        <text x="865" y="308">…and the next opportunity</text>
      </g>
    </g>
  </svg>
  <p class="career-flow-caption">One complete career record. Many targeted resumes—each tailored to a specific role.</p>
</div>

<style>
  .career-flow { margin: 1.5rem 0 2rem; padding: 1rem .75rem .5rem; border: 1px solid var(--bs-border-color, #dee2e6); border-radius: 14px; overflow: hidden; }
  .career-flow svg { display: block; width: 100%; height: auto; }
  .career-flow-caption { margin: .35rem 0 0; text-align: center; font-size: .9rem; opacity: .78; }
  @media (max-width: 650px) { .career-flow { padding: .5rem .25rem; } .career-flow svg { min-width: 650px; } .career-flow { overflow-x: auto; } }
</style>

## The Career Search System

Most people find a job posting and immediately rewrite their resume. That starts too late. A resume is a short marketing document, not a reliable place to store a decade of career evidence.

This system creates a reusable source of truth first, then uses it to evaluate roles and produce tailored application materials.

## Start with what you already have

Before the interview process, give your AI model an existing resume. It gives the model a baseline for your career timeline, titles, skills, projects, and the claims you've made before. That context helps it ask better questions instead of starting from a blank page.

Don't treat the resume as complete or automatically accurate. It is a compressed snapshot, often tailored to an old opportunity. The goal is to expand and verify it into a much richer master inventory—not simply reformat it.

## Start the process

Want an AI assistant to guide you through the entire workflow? Copy the [seven-stage kickoff prompt](start-here.md) into a new conversation. It starts with your existing resume, works through each stage with you, and creates portable checkpoints so you can continue across sessions.

## The seven stages

1. [Interview yourself](interview-process.md): start with your resume, then reconstruct roles and projects through targeted questions.
2. [Build the master inventory](master-inventory.md): preserve the full story, technical detail, scope, and evidence.
3. [Set up GitHub](github-setup.md): store the private working record and reusable prompts.
4. [Evaluate opportunities](opportunity-evaluation.md): research the company and role before investing in an application.
5. [Generate the resume](resume-generation.md): select evidence that supports the role.
6. **Review:** remove unsupported claims and make every bullet interview-defensible.
7. **Repeat:** update the inventory as new details emerge; do not rebuild from scratch.

## Why this order works

If you start with the resume alone, you tend to forget older work, compress distinct projects, and overemphasize whatever is easiest to remember. The inventory gives you a larger evidence pool. Each application selects the most relevant subset without changing the underlying facts.

## What AI should and should not do

AI can ask structured follow-up questions, organize notes, identify missing evidence, research public information, compare requirements, and draft. It cannot know whether a metric is true unless you provide evidence. You remain responsible for validating every claim.



---

<blockquote>
  <p align="right"><em>“I see surprisingly well for someone with such terrible eyesight.”</em></p>
</blockquote>

---

<p align="right"><em>made in less than an hour by Grant</em></p>
