# Ian Hintz

I build AI-assisted systems for messy, high-stakes workflows: research loops, evaluation pipelines, trading-system infrastructure, and human-in-the-loop control surfaces.

My recent private work is **AETHER**, an AI-assisted futures research-to-operations platform that turns ambiguous hypotheses and noisy local market data into reproducible workflows, compiler blueprints, replay/event artifacts, scorecards, candidate registries, promotion gates, and an operator-readable control surface. The repositories are private because they contain operational details and domain-specific logic, but I can share sanitized architecture, design decisions, testing strategy, and representative artifacts.

## What I Care About

- AI products that survive contact with real users, incomplete data, and operational risk.
- Systems that separate generated ideas from approved actions.
- Evaluation, auditability, and human control in agentic workflows.
- Fast prototypes that harden into legible, tested workflows.
- Trading systems where speed matters but proof matters more.

## Representative Work

### AETHER: Private AI Research-To-Operations Platform

Built across two generations: a legacy runtime/research system and a cleaner AI-first research platform.

Highlights:

- Automated coverage around the risky parts: ingestion, replay, persistence, schemas, risk gates, registry behavior, compiler behavior, and execution-boundary logic.
- Explicit candidate states: research-only, review-only, paper-permission, and live approval only by human authority.
- Local and cloud workflows for messy data, incomplete coverage, scorecards, runbooks, operator state, and audit artifacts.
- Evidence gates that can kill attractive candidates when cost-adjusted expectancy fails.
- A control surface showing state, risk, market context, decision gates, next actions, and audit trail.

The core lesson:

> Useful AI is not just about generating ideas. It is about proving which ideas deserve to move forward.

Sanitized artifacts:

- [`aether-case-study`](https://github.com/ihint/aether-case-study): founder-facing case study, AETHER control surface, and sanitized promotion packet sample.

## Public Repos To Start With

- `aether-case-study`: sanitized AI research-to-operations case study.
- `rfp-responder`: AI-assisted document workflow.
- `claude-code-starter-kit`: agent workflow scaffolding and automation hooks.
- `atomandbitsweb`: consulting/product strategy site.

## Current Focus

I am looking for a small, serious team building applied AI systems where the hard part is not a demo, but the workflow: context, evaluation, infrastructure, operational safety, and speed.

Alongside this private systems work, I joined TPN Health after my previous company was acquired. Healthcare keeps the stakes honest: real users, sensitive context, incomplete information, and software that has to earn trust.
