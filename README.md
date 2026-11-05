# Venkata G

Engineer who builds **agentic systems and the context architecture behind them**  MCP servers,
governed retrieval, and the product surfaces people actually use. My recurring theme: deciding the
right *shape* for an AI solution (MCP server vs. agent vs. plugin vs. platform) and then shipping it
with tests, guardrails, and observability  not a demo that falls over.

## Agentic & context systems

| Project | What it proves | |
|---|---|---|
| **[traveler-data-access-demo](https://github.com/venkata-gv/traveler-data-access-demo)** | How content reaches an AI agent safely: one governed read path enforcing consent, PII removal, provenance, and audit  an MCP server over an incremental pipeline that survives duplicate/late/out-of-order events. Spec-first with Claude Code, 99 tests, CI. | |
| **[sec-analyzer](https://github.com/venkata-gv/sec-analyzer)** | Context architecture matters: structure-aware retrieval beats naive vector RAG on financial tables — benchmarked (+40pp table-retrieval accuracy, +28pp answer correctness), with token-conscious chunking and reranking. | [live](https://filingsiq.vercel.app) |
| **[unified-enterprise-data-port](https://github.com/venkata-gv/unified-enterprise-data-port)** | Policy enforced once, at the transport boundary: an MCP server giving agents a governed port into enterprise data — contextual PII fencing + a data-movement audit ledger. | |
| **[dora-mifid-compliance](https://github.com/venkata-gv/dora-mifid-compliance)** | A full agent in a regulated domain: ReAct loop over an MCP tool registry, semantic PII kill-switch, SHA-256 forensic snapshots. | [live](https://dora-mifid-compliance.vercel.app) |

## AI tools that amplify a profession

| Project | What it does | |
|---|---|---|
| **[sarops-agent](https://github.com/venkata-gv/sarops-agent)** | Agentic AML investigation workbench — transaction-graph reasoning, typology detection, source-linked evidence, hard human-in-the-loop review gate. | |
| **[evidenceiq](https://github.com/venkata-gv/evidenceiq)** | Turns hours of manual claims-evidence assembly into minutes — multi-agent extraction, source-linked timeline, exportable evidence pack. Playwright e2e coverage. | [live](https://evidenceiq-psi.vercel.app) |
| **[ai-roi-calculator](https://github.com/venkata-gv/ai-roi-calculator)** | AI-vs-headcount cost modeling with an LLM-generated rollout playbook — zod-validated LLM JSON, unit-tested math. | |

## Front-end & design craft

| Project | What it shows | |
|---|---|---|
| **[shipflix](https://github.com/venkata-gv/shipflix)** | Netflix-style persona-aware portfolio — Next.js 16 parallel/intercepted routes, Framer Motion shared transitions, reduced-motion support, edge-generated OG images, and a token-economics visualization. | |
| **[turn-here-nursery](https://github.com/venkata-gv/turn-here-nursery)** | Marketing site + zero-cost ordering system (Google Sheets backend) for a real nursery — no framework, no build step, shipped for a real client. | |
| **[pure-cleaning-services](https://github.com/venkata-gv/pure-cleaning-services)** | Mobile-first marketing site for a real cleaning business, with a unit-tested vanilla-JS booking flow and an honest README about static-site limits. | |

## Experience

- **AI Engineer (Contract), Meta** — Jun 2025 – present
  Internal AI agent that helps engineers investigate production regressions: typed
  tool-execution layer (Scala), incremental retrieval pipeline (Kafka, Spark),
  guardrails and golden-set evaluation.
- **Machine Learning Engineer Intern / Co-op, UnitedHealthcare** — Jun 2024 – May 2025
  Claims-review prioritization: point-in-time feature pipelines on Spark and Iceberg,
  batch scoring, explainability and monitoring over de-identified healthcare data.
- **Data Scientist, Birlasoft** — Jan 2020 – Aug 2023
  Predictive models and Spark/Databricks pipelines for enterprise clients.

## Education

MS Business Analytics, DePaul University (2025)

## Tools

TypeScript · React/Next.js · Python · Java · Scala · SQL · LLMs · RAG · **MCP** · LangGraph ·
Claude Code · Spark · Kafka · Iceberg · PostgreSQL · Docker · Kubernetes · AWS
