# Ian Harman

**Healthtech CTO and founder. I build the systems behind provider networks, eligibility, claims, and payments — and lead the teams that ship them.**

Fifteen-plus years in healthcare technology: first product manager at PerfectServe as it grew from $2M to $40M ARR, digital products for 3.5M BlueCross BlueShield members, then co-founder of [TheraMatch](https://atomandbits.com/work/theramatch/), acquired by TPN.health in 2025 ([announcement](https://tpn.health/resources/news/tpn.health-acquires-all-counseling-to-advance-behavioral-health-access-and-provider-client-matching)). I work from strategy through code: set the roadmap, run the engineering team, and build in the codebase every day.

## Now

- **[Claims Native](https://atomandbits.com/claimsnative/)** — AI claim preparation for independent practices that want to accept insurance without adding a billing department. Starts from completed visits, sends judgment calls to a short approval queue, and prepares the next claim package. Paid-pilot beta.
- **Fractional CTO / CPO** through [Atom & Bits](https://atomandbits.com) — codebase and architecture audits, team assessment, turning a founder's vision into a technical roadmap, and day-to-day engineering leadership for early-stage healthtech.
- **[Merchant Context](https://github.com/ihint/merchant-context)** — an open merchant preflight for software agents: sourced facts, visible unknowns, and clear approval rules before paid or high-impact actions.

## Engineering Leadership

- **TPN.health** — VP, Provider Networks & Technology, 2025–26. Led product and engineering for the platform that connects provider access to reimbursement: 270/271 eligibility, 837 claims, 835 remittance, contracted-rate repricing, payer and provider ledgers, ACH/NACHA treasury, settlement, and reconciliation. Standardized the engineering team on Claude Code. Drove HIPAA and SOC 2 Type II readiness. Scaled TPN Match to $1M+ ARR and 1 million members in under 12 months.
- **One to One Health** — VP, Product & Engineering and Chief Privacy Officer, 2023–24. Built the function from zero: took over the platform an outside dev shop had built, moved it to a nearshore team in Latin America that I managed directly, hired the founding engineers, and replaced the ones who weren't delivering. Launched a virtual direct-primary-care platform and cut annualized IT spend 17%.
- **BlueCross BlueShield of Tennessee** — Senior / Group Digital Product Manager, 2016–23. Founding member of the digital team; led member web and mobile products for ~3.5M members with 22 direct reports, 130+ matrixed, and a $10M budget — including offshore engineering teams of 15+ across Latin America and Southeast Asia, spanning multiple organizations. More than doubled digital adoption and sustained member NPS above 60.

## AI in Production

Shipped, measured, and kept under control — not demos:

- **SOAP-note generation** (One to One Health) — cut clinician charting from 22 to 17.5 minutes across all encounters while clinician and patient satisfaction held or improved.
- **Negotiated-rate estimation** (TPN.health) — a model in production for estimates, with contracted-rate repricing kept deterministic by code, location, and contract terms. 99.59% first-pass repricing across about 4,000 claims.
- **AI-assisted intake** (TPN.health) — staff work from what the model collects; a person reviews before any navigation action.

## How I Build

- Models draft or propose work. People or policy approve actions.
- Each action keeps a record of what was requested, what happened, and what remains unknown.
- Tests cover the handoffs where money, claims, or customer trust can fail.
- A result means an outcome we can prove, not a forecast.
- Day to day I build with Claude Code, with tests, type checks, CI, and browser checks as the proof layer. I don't merge generated code I can't verify.

## Work You Can Inspect

- **[TheraMatch case study](https://atomandbits.com/work/theramatch/)** — The founder path from a clinical matching thesis through product, acquisition, and integration.
- **[TPN Match case study](https://atomandbits.com/work/tpn-match/)** — The move from provider matching into eligibility, claims, reimbursement, and payment operations.
- **[Claims Native](https://atomandbits.com/claimsnative/)** — A narrow insurance workflow for independent practices: one payer, one service, one location, one 90-day test.
- **[Merchant Context](https://github.com/ihint/merchant-context)** — An open schema, checklist, and running MCP/HTTP service for merchant discovery. Returns sources, freshness, unknowns, and safe next actions.
- **[AETHER case study](https://github.com/ihint/aether-case-study)** — A sanitized view of an AI-assisted market research system: how a hypothesis moves through replay, scorecards, promotion gates, and human approval.
- **[RFP Responder](https://github.com/ihint/rfp-responder)** — AI-assisted RFP drafting with a knowledge base, confidence scores, human review, and Word export.

## Selected Results

- Provider-network, eligibility, claims, repricing, and payment products that supported 120 contracted TPAs and 1.5 million eligible lives; first payment in under 30 days; more than $1 million in claims processed in six months.
- Brought in TheraMatch's first customers before institutional capital — 12 physician clients across three practices — then led the acquisition, integration, and go-to-market as TPN Match.
- Ran point on a $500K annual enterprise contract for a manufacturing client, the largest in its history, and guided its AI product pivot.

**Stack:** Elixir / Phoenix / LiveView · TypeScript / React / Node · Python / FastAPI · Postgres · GCP · Cloudflare Workers · MCP · X12 EDI · HIPAA / SOC 2

## Let's Talk

If you are building healthcare infrastructure or applied AI and need a CTO who can audit the codebase, lead the team, and still ship, [email me](mailto:Ian@atomandbits.com) or [connect on LinkedIn](https://www.linkedin.com/in/ianjharman).
