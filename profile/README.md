<div align="center">

# Inflexis

### Enterprise AI Orchestration — Built for Governed Intelligence at Scale

**[inflexis.ai](https://inflexis.ai)** · **[AIXaaS™ Platform](https://app.inflexis.ai)** · [Contact Us](mailto:bryan.shaw@inflexis.ai)

---

</div>

## What We Build

**Inflexis** develops the **AIXaaS™ platform** — AI-as-a-Service infrastructure that gives enterprises governed, auditable, multi-agent intelligence on their own data. We handle the architecture so your teams can focus on outcomes.

Where most AI tools give you a chatbot, AIXaaS™ gives you an orchestration layer: multiple specialized agents, a compliance engine, a structured knowledge base, and a full audit trail — all deployable in your Azure tenant with your data never leaving your control.

---

## The MAO Platform

**MAO (Multi-Agent Orchestration)** is the core engine behind AIXaaS™. It is a production-grade, enterprise-class AI system designed around a single principle: **aviation-grade dual redundancy**. Every agent handoff produces an auditable decision record. Every stage has a validated fallback. No single point of failure.

### Core Capabilities

| Capability | What It Means |
|---|---|
| **Multi-Agent Orchestration** | Specialized agents for compliance, knowledge, meetings, and analysis — coordinated via a structured pipeline |
| **Hybrid RAG Architecture** | 4-tier knowledge retrieval: keyword → semantic vector → cloud vector → Azure AI Search |
| **Zero-Token Compliance** | 23 regulatory frameworks detected deterministically — no LLM API cost for compliance scanning |
| **Enterprise Knowledge Base** | 20+ file types ingested: PDF, DOCX, PPTX, XLSX, audio recordings, YouTube, web pages, and more |
| **Governed Change Control** | ADR (Architectural Decision Record) system: every agent instruction change is proposed, reviewed, and versioned |
| **Meeting Intelligence** | Automatic transcription, SPICED sales scoring, per-attendee summaries, CRM sync |
| **Cost-Aware Model Routing** | Frugal LLM selection per query type: routes to the cheapest model meeting quality requirements |
| **Azure-Native Deployment** | Container Apps, Key Vault, Entra SSO, AI Search, Blob Storage, Application Insights — production-ready from day one |

---

## Who We Work With

AIXaaS™ is built for enterprises where AI governance is not optional:

- **Industrial & OT/ICS operators** — where process data, compliance docs, and threat intelligence must stay inside a hardened perimeter
- **Energy & commodities companies** — where pricing data, contracts, and market intelligence require structured, auditable AI access
- **Professional services firms** — where client data must remain isolated, searchable, and governed by role
- **Technology companies** building AI-native products who need the orchestration layer without building it themselves

---

## Architecture Principles

```
Layer 0   Foundation          Zero-token compliance detection, deterministic pattern matching
Layer 1   Agent Architecture  8-role RBAC, role-specific agent directives, namespace governance
Layer 2   LLMs & APIs         Multi-provider routing: Claude, Azure OpenAI, Gemini, local Ollama
Layer 3   Tool Use            Universal Ingestor, Compliance Engine, PII masking layer
Layer 4   Agent Frameworks    FastAPI, Jinja2, Claude Agent SDK, MCP server (8 tools)
Layer 5   Orchestration       Multi-agent DAG: parse → mask → comply → chunk → store
Layer 6   Memory Management   4-tier hybrid storage, disk persistence, semantic response cache
Layer 7   Knowledge & RAG     Hybrid BM25 + dense vector retrieval, sector governance
Layer 8   Deployment          Azure Container Apps, CI/CD, custom domains, managed TLS
Layer 9   Monitoring          ADR audit trail, guardrails, budget tracking, App Insights
Layer 10  Security & Gov.     Change control, archive/rollback, sector RBAC, PII masking
```

---

## Live Deployments

| URL | Purpose |
|---|---|
| [app.inflexis.ai](https://app.inflexis.ai) | Employee portal — internal knowledge base, compliance tools, meeting intelligence |
| [app.aixaas.org](https://app.aixaas.org) | Client portal — isolated tenant environments (Phase 7) |

Both domains run on Azure Container Apps with Azure-managed TLS, Entra SSO, and continuous deployment via GitHub Actions.

---

## Repositories

| Repo | Visibility | Contents |
|---|---|---|
| [aixaas-docs](https://github.com/inflexis-ai/aixaas-docs) | Public | Platform documentation, integration guides, architecture references |
| [mao-examples](https://github.com/inflexis-ai/mao-examples) | Public | Integration examples, API usage patterns, demo notebooks |
| `mao-platform` | Private | Core MAO platform — proprietary AIXaaS™ engine |

---

## Technology Stack

**Cloud:** Azure Container Apps · Azure AI Search · Azure Blob Storage · Azure Key Vault · Azure Entra ID · Application Insights · Azure Files
**AI / LLMs:** Anthropic Claude · Azure OpenAI · Google Gemini · Ollama (local)
**Backend:** Python 3.12 · FastAPI · Uvicorn · Jinja2
**Knowledge:** Qdrant · Pinecone · Azure AI Search · BM25 keyword index
**Data Formats:** PDF · DOCX · PPTX · XLSX · Markdown · Audio (MP3/WAV/MP4) · YouTube · Web pages
**Compliance Frameworks:** GDPR · HIPAA · PCI-DSS · SOC2 · NIST · ISO 27001 · CCPA · FedRAMP · and 15 more
**Auth:** HTTP Basic Auth · Azure Entra SSO (OIDC) · Signed session cookies

---

## Contact

**Bryan Shaw** — CTO & Founding Partner
📧 [bryan.shaw@inflexis.ai](mailto:bryan.shaw@inflexis.ai)
🌐 [inflexis.ai](https://inflexis.ai)
💼 [LinkedIn](https://www.linkedin.com/in/bryanjshaw/)

---

<div align="center">
<sub>© 2026 Inflexis · AIXaaS™ is a trademark of Inflexis · All MAO Platform source code is proprietary and confidential</sub>
</div>
