<img src="banner.svg" alt="Understand the workflow. Then build the AI. Tracy Anne Griffin Manning, AI Architect, Austin." width="100%">

**AI Architect** · Texas Triangle (San Antonio / Austin / Dallas–Fort Worth)  
[Website](https://tam-ds.github.io/) · [Email](mailto:tmanning@post.harvard.edu) · [LinkedIn](https://www.linkedin.com/in/tracymanning) · [X](https://x.com/TAGM2025)

I design agentic systems where a model can propose and cannot grant itself permission.  
Financial services trained the consequence. Founding trained the ownership.  
The public repositories are the parts a reviewer can inspect.

**Current:** Founder, Apex AI|ML  
**Prior:** Minotaur Consulting · Office of the CIO · Wall Street

---

## The rule

A recommendation is not permission.  
Approval is bound to the exact action.  
Current evidence is checked again at execution.  
If the control cannot be shown, the claim is not made.

---

## Three flagship systems — business problems, governed execution, inspectable evidence

Three different enterprise decisions. One architectural principle: **the model can propose; the system determines what is authorized.**

| | Flagship | Business problem | What a reviewer can verify |
|---|---|---|---|
| **01** | **[SignalDesk — AI-assisted lead intelligence](https://github.com/TAM-DS/SignalDesk-Acquisition-Intelligence)** | How can sales teams investigate opportunities without letting AI authorize outreach or bypass CRM opt-outs? | Bounded OpenAI research, source-linked findings, per-lead review, Salesforce **GET-only** preview with opt-out/deletion checks, fail-closed restrictions, no automated CRM writes or outreach. **135 tests and 46 subtests passed; lint passed.** *Developer-org and simulated-HTTP evidence; not a production CRM rollout or proven revenue uplift.* |
| **02** | **[AEGIS-NHI — cyber risk and AI infrastructure economics](https://github.com/TAM-DS/AEGIS-NHI)** | How can risk and finance leaders see what warrants investigation, what was blocked, and what remains uncertain? | Deterministic investigation logic, evidence-linked findings, modeled financial exposure, executive dashboard, and human-reviewed recommendations. Scenarios distinguish **one executed unregistered-tool request** from **two blocked attempts**; authenticity, evidence gaps, and actual harm remain uncertain. *Synthetic reference scenarios, not live bank monitoring, autonomous remediation, or verified prevented losses.* |
| **03** | **[VANGUARD-Guard — AI governance workbench](https://github.com/TAM-DS/VANGUARD-Guard)** | Who owns the AI in use, how is risk assessed, and what evidence supports accountable decisions? | Local-first Streamlit/SQLite workbench for inventory, risk assessment, ownership, and review workflows with documented checks. *Illustrative governance tooling; not certified compliance, automated bias certification, or enterprise-enforced authorization.* |

**Shared architecture:** understand the workflow → define the business decision → bound model and tool authority → verify evidence → require accountable human approval.

**Additional engineering proof:** [GuardRails-MCP](https://github.com/TAM-DS/guardrails-mcp) demonstrates prompt-regression testing, evidence snapshots, read-only MCP tools, and human release authority. [PyPI package](https://pypi.org/project/guardrails-mcp/) · [MCP Registry](https://registry.modelcontextprotocol.io/v0.1/servers/io.github.TAM-DS%2Fguardrails-mcp/versions/0.1.1). *Publishing and registration are not certification.*

---

## Multi-model engineering & runtime architecture

**The model is a component. The architecture is the product.**

I assess OpenAI GPT/Codex, Anthropic Claude, Google Gemini, and xAI Grok according to workload fit: reasoning and structured output, code and tool-use workflows, context requirements, retrieval, latency, cost, and failure behavior. **Model evaluation is not the same as a deployed four-provider orchestration layer.**

The governing design principle remains independent of provider: **explicit tool grants, deterministic policy checks, source-linked evidence, bounded execution, and human accountability.** See [SignalDesk](https://github.com/TAM-DS/SignalDesk-Acquisition-Intelligence), [AEGIS-NHI](https://github.com/TAM-DS/AEGIS-NHI), and [Agent Foundry](https://github.com/TAM-DS/agent-foundry) for inspectable examples of these boundaries.

---

## Open-source reference engineering

**XERJ Corpus Hub selection (2026) — SignalDesk Salesforce GET-only integration**

The XERJ team selected a bounded Salesforce GET-only preview implementation from [SignalDesk](https://github.com/TAM-DS/SignalDesk-Acquisition-Intelligence) for inclusion in its public code-reference corpus. The selected work focuses on validation, fail-closed behavior, opt-out checks, and deterministic restrictions around enterprise API access.

**Engineering lesson:** The model may propose; the system determines what is authorized.

*Selection for indexing is external recognition of an implementation—not certification, formal peer review, a universal reference standard, proof of agent adoption, or measured token savings. A direct corpus citation can be added when publicly verified.*

---

## Featured technical work

Depth in governed AI and breadth across capital markets, energy, supply chain, and cybersecurity assurance.

| | Repository | Sector | What it proves |
|---|---|---|---|
| **01** | **[Agent Foundry](https://github.com/TAM-DS/agent-foundry)** | Enterprise AI | Capability, identity, and runtime grants are separate. 399 tests. AWS DEV. |
| **02** | **[Monster Heavy](https://github.com/TAM-DS/monster-heavy)** | Capital Markets | Durable paper execution survives retry, concurrency, and worker death. |
| **03** | **[AI-Ready Data Platform](https://github.com/TAM-DS/ai-ready-data-platform)** | Retail / Analytics | Multi-agent chain where claims are checked against bounded facts before they become enterprise truth. |
| **04** | **[Capital Markets Research Desk](https://github.com/TAM-DS/capital-markets-research-desk)** | Energy Trading | Historical evidence + fixed-rule holdout + skeptical CrewAI research brief. |
| **05** | **[Energy Equity Investment Gems](https://github.com/TAM-DS/energy-equity-investment-gems)** | Screening | Explicit momentum, volatility, and liquidity hurdles; bounded agent challenge. |
| **06** | **[Paper Trading Floor](https://github.com/TAM-DS/paper-trading-floor)** | Multi-Agent + MCP | Agents only propose; local ledger validates cash, risk limits, and replay protection. |
| **07** | **[BALLAST](https://github.com/TAM-DS/ballast)** | Supply Chain | Explainable risk, what-if shocks, and a disruptive-action approval gate (Gradio). |
| **08** | **[AEGIS Evidence](https://github.com/TAM-DS/aegis-evidence)** | Cybersecurity | Replayable assurance workpaper, human acceptance, open gaps, SHA-256-verifiable archives. |

Supporting boundary examples: [Monster Desk](https://github.com/TAM-DS/monster-desk), [Monster Light](https://github.com/TAM-DS/monster-light-v0.1-v0.2), [AEGIS Analyst](https://github.com/TAM-DS/aegis-analyst).

---

## Data & platform foundations

| Repository | Focus |
|---|---|
| **[Databricks AI-Ready Lakehouse](https://github.com/TAM-DS/databricks-ai-ready-lakehouse)** | Governed Spark / PySpark pipelines, Unity Catalog, Delta Lake, read-only MCP boundaries |
| **[Idempotent Data Engineering Foundation](https://github.com/TAM-DS/Idempotent-Data-Engineering-Foundation-System)** | One-command path from raw CSV to market intelligence with true idempotency |
| **[FinOps for M&A Infrastructure DD](https://github.com/TAM-DS/FinOps-for-M-A-Infrastructure-Due-Diligence-Dashboard)** | Modeled multi-cloud infrastructure risk scenarios (illustrative savings, not a client result) |
| **[AI Infrastructure Intelligence](https://github.com/TAM-DS/AI-Infrastructure-Intelligence-Platform)** | Modeled multi-cloud GPU cost scenarios |

---

## Interactive demos (local only)

No hosted production systems are implied. Each repository documents its own dependencies and entry points.

**Gradio**
- [BALLAST](https://github.com/TAM-DS/ballast) — supply-chain control tower (energy routes, semiconductor concentration, approval-gated mitigation)
- [AEGIS Analyst](https://github.com/TAM-DS/aegis-analyst) — SOC analyst console with policy checks and sandboxed actions

**Streamlit trading workbenches** (historical daily data + Python metrics + bounded CrewAI; agents have no order tools)
- [Capital Markets Research Desk](https://github.com/TAM-DS/capital-markets-research-desk)
- [Energy Equity Investment Gems](https://github.com/TAM-DS/energy-equity-investment-gems)
- [Paper Trading Floor](https://github.com/TAM-DS/paper-trading-floor)

```bash
# typical Streamlit entry
python -m streamlit run app.py
```

---

## What I bring

**Enterprise AI implementation & delivery · C-suite advisory · agentic AI architecture & governance · technical pre-sales.**

Verifiable shipped code. Python, cloud architecture, and MCP integration. Bounded tool authority and model evaluation. Founder-level ownership. Translation from an executive business problem to a reviewed technical decision.

These are reference implementations. They demonstrate architecture and controls a reviewer can inspect—not claims of paying customers or enterprise production deployment.
