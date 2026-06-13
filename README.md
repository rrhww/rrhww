<h1 align="center">RrH</h1>

<p align="center">
  Building toward agent observability, evaluation, and security governance.
</p>

<p align="center">
  <a href="https://github.com/rrhww?tab=repositories">
    <img src="https://img.shields.io/badge/Focus-Agent%20Systems-0f766e?style=for-the-badge" alt="Focus: Agent Systems" />
  </a>
  <a href="https://github.com/langfuse/langfuse">
    <img src="https://img.shields.io/badge/Studying-Langfuse-171717?style=for-the-badge" alt="Studying Langfuse" />
  </a>
  <a href="https://github.com/rrhww/inkdesk">
    <img src="https://img.shields.io/badge/Project-Inkvault-2563eb?style=for-the-badge" alt="Project Inkvault" />
  </a>
</p>

I am a student and independent developer focused on agent systems, full-stack product engineering, and reliable AI workflows.

My current direction is to build a concrete specialization around **agent observability, agent evaluation, and agent security governance**. The near-term plan is to study and contribute to the Langfuse ecosystem, then build a companion project on top of Langfuse for replayable agent risk evaluation, evidence records, and policy decisions.

## Current Focus

- Agent observability: traces, tool calls, handoff context, runtime metadata
- Agent evaluation: replay inputs, evaluation plumbing, regression datasets
- Security governance: prompt injection, tool misuse, data leakage, risk decisions
- Full-stack implementation: product surfaces that make AI behavior inspectable and reviewable

## What I Am Building

### Langfuse Agent Security Governance

An upcoming companion project built around Langfuse traces, datasets, scores, and replay inputs.

The goal is not to replace Langfuse. The goal is to use Langfuse as the system of record, then add a focused governance layer for:

- replayable agent task flows
- prompt-injection and tool-misuse evaluation
- structured risk evidence
- allow / warn / fail policy decisions
- demoable audit trails for agent behavior

### Inkvault

[Inkvault](https://github.com/rrhww/inkdesk) is a vault-first research memory system built around:

```text
raw -> ingest -> wiki -> ask
```

It explores how to combine AI-assisted knowledge ingestion with human-reviewed long-term memory, while keeping accepted knowledge recoverable from the vault itself.

This project shows my work on:

- full-stack implementation with Next.js and FastAPI
- workflow and data modeling for knowledge systems
- reviewable AI proposals instead of silent generation
- product boundaries, architecture, and documentation

## Tech I Use

**Current stack**

- TypeScript, React, Next.js
- Python, FastAPI
- PostgreSQL, SQLAlchemy
- Tailwind CSS
- Docker
- Playwright, Vitest, pytest

**Currently exploring**

- Langfuse internals and contribution workflow
- Agent runtime telemetry
- Trace replay and evaluation pipelines
- RAG and grounded QA
- Reviewable ingestion pipelines
- Policy-driven agent safety workflows

## Open Source Direction

I am using open-source work as a way to make my engineering growth visible:

- read production codebases deeply before proposing changes
- contribute small, reviewable improvements with tests
- write down architecture decisions and implementation notes
- turn project work into reusable examples and demos

The main thread for the next stage is:

```text
Langfuse ecosystem contributions
  -> agent observability and evaluation gaps
  -> companion security governance project
  -> portfolio-ready engineering narrative
```

## Contact

- GitHub: [rrhww](https://github.com/rrhww)
- Project: [Inkvault / inkdesk](https://github.com/rrhww/inkdesk)
