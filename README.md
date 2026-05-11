# Hi, I'm Ian.

I build AI-assisted systems for messy, high-stakes workflows: research loops, decision support, evaluation pipelines, and human-in-the-loop control surfaces.

My recent private work is **AETHER**, an AI-assisted research-to-operations platform that turns ambiguous hypotheses and noisy local data into reproducible workflows, replay artifacts, scorecards, candidate registries, and reviewable promotion packets. The repositories are private because they contain operational details and domain-specific logic, but I can share sanitized architecture, design decisions, testing strategy, and representative artifacts.

## What I Care About

- AI products that survive contact with real users, incomplete data, and operational risk.
- Systems that separate generated ideas from approved actions.
- Evaluation, auditability, and human control in agentic workflows.
- Fast prototypes that harden into legible, tested workflows.

## Representative Work

### AETHER: Private AI Research-To-Operations Platform

Built across two generations: a legacy runtime/research system and a cleaner AI-first research platform.

Highlights:

- Automated coverage around the risky parts: ingestion, replay, persistence, schemas, risk gates, registry behavior, and execution-boundary logic.
- Explicit candidate states: research-only, paper/shadow, recommended, and armed only by human approval.
- Local-first workflows for messy data, incomplete coverage, scorecards, runbooks, and audit artifacts.
- Review artifacts that can block a promising candidate when the evidence is thin.
- A control-surface mockup showing state, risk, event context, decision gates, and audit trail.

The core lesson:

> Useful AI is not just about generating ideas. It is about proving which ideas deserve to move forward.

Sanitized artifacts I can share:

- [`aether-case-study`](https://github.com/ihint/aether-case-study): founder-facing case study, AETHER control-surface mockup, and sanitized promotion packet sample.

## Public Repos To Start With

- `aether-case-study`: sanitized AI research-to-operations case study.
- `rfp-responder`: AI-assisted document workflow.
- `claude-code-starter-kit`: agent workflow scaffolding and automation hooks.
- `atomandbitsweb`: consulting/product strategy site.

## Current Focus

I am looking for a small, serious product team building applied AI systems where the hard part is not a demo, but the workflow: context, evaluation, user trust, operational safety, and speed.
