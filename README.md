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

## Products — intelligence is useful; accountable execution is the product

Three practical systems. Three different business problems. One architectural constraint: **the model can propose; the system determines what is authorized.**

| | Product | Hook | What a reviewer can verify |
|---|---|---|---|
| **01** | **[SignalDesk](https://github.com/TAM-DS/SignalDesk-Acquisition-Intelligence)** | What if AI could find the opportunity—but could not approve its own outreach? | OpenAI-powered candidate discovery, source-linked findings, explicit human-review → SDR handoff, evidence holds, rate-limited live attempts, simulated-only delivery. MIT v0.4 · **108 local tests** · passing CI. *Commercially oriented architecture; not a production SaaS.* |
| **02** | **[AI Governance Helper for HR](https://github.com/TAM-DS/ai-governance-app)** | Your organization has an AI strategy. Who owns the AI already in use? | Local Streamlit app for tool inventory, risk assessment, accountable ownership, and summary views. SQLite persistence · documented tests. *Illustrative HR/governance workflow — not certified compliance.* |
| **03** | **[GuardRails-MCP](https://github.com/TAM-DS/guardrails-mcp)** | A prompt changed. What broke—and who has the evidence to decide? | Local prompt-regression harness, bounded live comparison, evidence snapshots, four read-only MCP tools, human release authority. **[PyPI v0.1.1](https://pypi.org/project/guardrails-mcp/)** · [MCP Registry](https://registry.modelcontextprotocol.io/v0.1/servers/io.github.TAM-DS%2Fguardrails-mcp/versions/0.1.1). *Registration is not certification.* |

**Operating pattern:** understand the workflow → bound the intelligence → require human authorization → verify current evidence → preserve the outcome.

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

Verifiable shipped code. Python, cloud architecture, and MCP integration. Bounded tool authority and model evaluation. Founder-level ownership. Translation from an executive business problem to a reviewed technical decision.

These are reference implementations. They demonstrate architecture and controls a reviewer can inspect—not claims of paying customers or enterprise production deployment.
