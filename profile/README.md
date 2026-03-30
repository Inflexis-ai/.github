<div align="center">

<img src="https://img.shields.io/badge/AIXaaS™-Enterprise%20AI%20Orchestration-0078D4?style=for-the-badge&logo=microsoftazure&logoColor=white" alt="AIXaaS™"/>

# Inflexis

**Enterprise AI Orchestration — Governed, Auditable, Production-Ready**

[![Platform](https://img.shields.io/badge/Platform-Azure%20Container%20Apps-0078D4?style=flat-square&logo=microsoftazure)](https://app.inflexis.ai)
[![Auth](https://img.shields.io/badge/Auth-Azure%20Entra%20SSO-0078D4?style=flat-square&logo=microsoftazure)](https://app.inflexis.ai/auth/login)
[![LLMs](https://img.shields.io/badge/LLMs-Claude%20%7C%20GPT--5.4%20%7C%20Gemini-8B5CF6?style=flat-square&logo=anthropic)](https://github.com/inflexis-ai/aixaas-docs/blob/main/docs/integrations/llm-providers.md)
[![Python](https://img.shields.io/badge/Python-3.12-3776AB?style=flat-square&logo=python&logoColor=white)](https://www.python.org/)
[![FastAPI](https://img.shields.io/badge/FastAPI-0.109-009688?style=flat-square&logo=fastapi)](https://fastapi.tiangolo.com/)
[![License](https://img.shields.io/badge/License-Proprietary-red?style=flat-square)](https://inflexis.ai)

<br/>

[**Live Platform →**](https://app.inflexis.ai) &nbsp;·&nbsp; [**Documentation →**](https://github.com/inflexis-ai/aixaas-docs) &nbsp;·&nbsp; [**Examples →**](https://github.com/inflexis-ai/mao-examples) &nbsp;·&nbsp; [**Contact →**](mailto:bryan.shaw@inflexis.ai)

</div>

---

## What We Build

**Inflexis** develops the **AIXaaS™ platform** (AI-as-a-Service) — enterprise AI orchestration infrastructure that gives organizations governed, auditable, multi-agent intelligence on their own data, deployed inside their own Azure tenant.

Where most AI tools give you a chatbot, AIXaaS™ gives you an **orchestration layer**: multiple specialized agents, a structured compliance engine, a hybrid RAG knowledge base, and a full audit trail — with your data never leaving your control.

---

## The MAO Platform

**MAO (Multi-Agent Orchestration)** is the core engine behind AIXaaS™ — a production-grade system designed around a single principle: **aviation-grade dual redundancy**. Every agent handoff produces an auditable decision record. Every stage has a validated fallback. No single point of failure.

<details>
<summary><strong>🏗️ 10-Layer Architecture</strong></summary>

<br/>

```
Layer 0   Foundation          Deterministic compliance detection (23 frameworks, zero LLM cost)
Layer 1   Agent Architecture  8-role RBAC: admin → founder → cro → marketing → developer → member → client → demo
Layer 2   LLMs & APIs         6-tier cost routing: Ollama → Gemini → GPT-4.1-nano → Haiku → GPT-4.1-mini → GPT-4o → Sonnet
Layer 3   Tool Use            Universal Ingestor (20+ file types), Compliance Engine, PII masking
Layer 4   Agent Frameworks    FastAPI, Claude Agent SDK, MCP server (8+ tools for Claude Desktop)
Layer 5   Orchestration DAG   parse → PII mask → compliance scan → chunk → store (ADR logged at every stage)
Layer 6   Memory Management   4-tier hybrid storage, disk persistence, semantic response cache (30–60% cost reduction)
Layer 7   Knowledge & RAG     Hybrid BM25 + dense vector retrieval, sector governance, namespace isolation
Layer 8   Deployment          Azure Container Apps, GitHub Actions CI/CD, custom domains, managed TLS
Layer 9   Monitoring          ADR audit trail, guardrails (token budget + loop caps), App Insights
Layer 10  Security & Gov.     Change control with diff review, archive/rollback, PII masking, sector RBAC
```

</details>

<details>
<summary><strong>📦 Core Capabilities</strong></summary>

<br/>

| Capability | Description |
|---|---|
| **Multi-Agent Orchestration** | Specialized agents coordinated via a structured DAG pipeline |
| **Hybrid RAG** | 4-tier knowledge retrieval: keyword → semantic vector → cloud vector → Azure AI Search |
| **Zero-Token Compliance** | 23 regulatory frameworks detected deterministically — no LLM API cost |
| **20+ File Types** | PDF, DOCX, PPTX, XLSX, audio recordings, YouTube, web pages, and more |
| **ADR Change Control** | Every agent instruction change is proposed, reviewed, versioned, and recoverable |
| **Meeting Intelligence** | Auto-transcription, SPICED sales scoring, per-attendee summaries, CRM sync |
| **Cost-Aware Model Routing** | Routes to cheapest model meeting quality requirements — ~98% gross margin at scale |
| **Azure-Native** | Container Apps, Key Vault, Entra SSO, AI Search, Blob — production from day one |
| **Sub-Agent Isolation** | Namespace-scoped execution with RBAC boundaries — structured task decomposition across agent roles |
| **Token-Aware Payloads** | Zero-token compliance detection + semantic cache reduce LLM spend by 30-60% without quality loss |
| **ZeroTrusted SOAR Integration** | 57+ AI security agent compatibility — anomaly detection, threat classification, automated response orchestration |

</details>

---

## Live Deployments

| URL | Purpose | Status |
|---|---|---|
| [app.inflexis.ai](https://app.inflexis.ai) | Employee portal — internal KB, compliance, meeting intelligence | ![Live](https://img.shields.io/badge/status-live-brightgreen?style=flat-square) |
| [app.aixaas.org](https://app.aixaas.org) | Client portal — isolated tenant environments | ![Live](https://img.shields.io/badge/status-live-brightgreen?style=flat-square) |
| [Demo Hub](https://inflexis-ai.github.io/mao-examples/demos/) | Interactive demos — runs in browser, no login required | ![Live](https://img.shields.io/badge/status-live-brightgreen?style=flat-square) |

Both portals run on Azure Container Apps with Azure-managed TLS, Entra SSO, and GitHub Actions CI/CD (~5 min deploy on every `git push main`). The demo hub is hosted on GitHub Pages.

---

## Repositories

| Repo | Type | Description |
|---|---|---|
| [**aixaas-docs**](https://github.com/inflexis-ai/aixaas-docs) | 📖 Public | Platform documentation, API reference, architecture guides, integration specs |
| [**mao-examples**](https://github.com/inflexis-ai/mao-examples) | 💻 Public | Integration examples, Python scripts, Jupyter notebooks, [interactive demos](https://inflexis-ai.github.io/mao-examples/demos/) |
| **mao-platform** | 🔒 Private | Core AIXaaS™ engine — proprietary MAO platform source |
| **team-workspace** | 🔒 Private | Internal design docs, architecture pages, revenue models, client materials |

---

## Technology Stack

```
Cloud        Azure Container Apps · ACR · Key Vault · AI Search · Blob · Files · Entra · App Insights
AI / LLMs    Anthropic Claude · Azure OpenAI · Google Gemini · Ollama · Azure Speech · Azure Doc Intelligence
Backend      Python 3.12 · FastAPI · Uvicorn · Jinja2
Knowledge    Qdrant · Pinecone · Azure AI Search · BM25 keyword (4-tier hybrid)
Auth         HTTP Basic Auth · Azure Entra SSO (OIDC) · Signed session cookies
CI/CD        GitHub Actions → Azure Container Registry → Container Apps (~5 min)
Compliance   23 frameworks: GDPR · HIPAA · PCI-DSS · SOC 2 · NIST · ISO 27001 · NERC CIP · IEC 62443 · +15 more
```

---

## Ecosystem & Related Projects

AIXaaS™ is built on and alongside the best open-source AI infrastructure available. These are the projects we watch closely, draw from, and complement:

| Project | What It Is | Relationship to MAO |
|---|---|---|
| [anthropics/anthropic-sdk-python](https://github.com/anthropics/anthropic-sdk-python) | Official Anthropic Python SDK | Primary LLM integration |
| [anthropics/anthropic-cookbook](https://github.com/anthropics/anthropic-cookbook) | Claude API usage patterns | Reference for agent prompt patterns |
| [modelcontextprotocol/servers](https://github.com/modelcontextprotocol/servers) | MCP server implementations | MAO ships its own MCP server (8 tools) |
| [microsoft/autogen](https://github.com/microsoft/autogen) | Microsoft's multi-agent framework | Architectural comparison — MAO's ADR system fills AutoGen's governance gap |
| [langchain-ai/langgraph](https://github.com/langchain-ai/langgraph) | Agent orchestration via DAG | MAO uses a similar DAG pipeline pattern, custom-built without framework overhead |
| [joaomdmoura/crewAI](https://github.com/joaomdmoura/crewAI) | Role-based agent crews | MAO's 8-role RBAC is the enterprise governance layer CrewAI lacks |
| [BerriAI/litellm](https://github.com/BerriAI/litellm) | Unified LLM API routing | MAO's model router solves the same problem with per-role cost governance built in |
| [qdrant/qdrant](https://github.com/qdrant/qdrant) | High-performance vector database | MAO's Tier 2 semantic store |
| [run-llama/llama_index](https://github.com/run-llama/llama_index) | Data framework for LLM applications | RAG architecture reference |
| [NVIDIA AI-Q + NeMo Agent Toolkit](https://developer.nvidia.com/blog/how-to-build-deep-agents-for-enterprise-search-with-nvidia-ai-q-and-langchain/) | Hierarchical planner→researcher agent pattern, NIM microservices, LangGraph orchestration | Architectural alignment — MAO implements the same sub-agent isolation, structured task decomposition, and 3-tier LLM strategy independently |
| [langchain-ai/langsmith](https://github.com/langchain-ai/langsmith-sdk) | LLM observability, agent tracing, and evaluation platform | MAO's ADR audit trail solves the same agent observability problem — LangSmith integration is a roadmap item |
| [huggingface/smolagents](https://github.com/huggingface/smolagents) | Lightweight code-first agent framework (~1,000 lines) supporting any LLM provider | Model-agnostic agent design — complements MAO's multi-provider LLM routing and namespace isolation pattern |
| [huggingface/transformers](https://github.com/huggingface/transformers) | 800K+ models, datasets, Inference Endpoints, Enterprise Hub (SOC 2, AWS/Azure/GCP) | MAO's local semantic store (Tier 2) uses HuggingFace sentence-transformers for embedding; HF Enterprise Hub is a candidate for private model hosting |

---

## Contact

**Bryan Shaw** — CTO & Founding Partner, Inflexis
📧 [bryan.shaw@inflexis.ai](mailto:bryan.shaw@inflexis.ai) · 🌐 [inflexis.ai](https://inflexis.ai) · 💼 [LinkedIn](https://www.linkedin.com/in/bryanjshaw/)

---

<div align="center">
<sub>© 2026 Inflexis · AIXaaS™ is a trademark of Inflexis · MAO Platform source code is proprietary and confidential</sub>
</div>
