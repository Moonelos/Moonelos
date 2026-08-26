<div align="center">

<img src="./assets/systems-blueprint.png" width="100%" alt="From an idea to a production-grade intelligent system" />

<h1>Georgios Agrafiotis</h1>

<p><strong>Senior AI Engineer · AI Solutions Architect</strong></p>

<p>
I design the layer between an LLM demo and a system people can trust:<br/>
<strong>agents, tools, identity, state, observability, and infrastructure.</strong>
</p>

<p>
  <a href="https://www.linkedin.com/in/giorgos-agrafiotis-7b580020b/">LinkedIn</a>
  &nbsp;·&nbsp;
  <a href="mailto:gagrafio@gmail.com">Email</a>
  &nbsp;·&nbsp;
  <a href="https://github.com/balalaika-tools?tab=repositories">Repositories</a>
</p>

</div>

---

## About

```python
from dataclasses import dataclass


@dataclass(frozen=True)
class AIEngineer:
    name: str = "Georgios (Giorgos) Agrafiotis"
    role: str = "Senior AI Engineer · AI Solutions Architect"
    experience: str = "7+ years building production software"
    mission: str = "Turn ambitious AI ideas into governed, observable systems"

    def expertise(self) -> dict[str, tuple[str, ...]]:
        return {
            "agentic_systems": ("LangGraph", "MCP", "multi-agent workflows", "memory"),
            "ai_governance": ("OAuth/OIDC", "RBAC", "tenant isolation", "tool access"),
            "platforms": ("AWS Bedrock", "Azure AI Foundry", "Google Vertex AI"),
            "backend": ("Python", "FastAPI", "asyncio", "Go", "PostgreSQL"),
            "production": ("OpenTelemetry", "Langfuse", "Kubernetes", "Terraform", "CI/CD"),
        }
```

> I work where agents stop being demos and start becoming systems.

---

## Selected client systems

<sub>Public summaries of private client work. Source code and confidential implementation details remain private.</sub>

### 01 · Governed Agentic Pricing Platform

**[Quicklizard](https://quicklizard.com) · Private repositories**

Designed and built the AI layer around a dynamic-pricing platform:

- **Custom Pricing MCP** — turns internal pricing capabilities into structured tools for AI agents.
- **Multi-tenant MCP Gateway** — governs how authenticated users and machine clients access those tools.
- **Stateful Pricing Agent** — explains live pricing decisions through a streaming, multi-turn experience with durable session memory.
- **Production observability** — connects agent, model, tool, and service behavior into one operational view.

`LangGraph` `MCP` `Go` `AWS Bedrock` `Kubernetes` `PostgreSQL` `OpenTelemetry`

### 02 · Stateful Agentic Exception Management

**[Gresham Tech](https://www.greshamtech.com) · Private repository**

Designed and implemented a durable exception-management system for financial-data operations. It coordinates intake, resolution workflows, external interactions, recovery paths, and human review while keeping workflow state explicit and auditable.

`Python` `PostgreSQL` `AWS` `Playwright` `Terraform` `OpenTelemetry`

### 03 · Production Agentic RAG Service

**[XGS.AI](https://xgs.ai) · Private repository**

Took an existing RAG proof of concept to production: redesigned the service architecture, built the FastAPI and LangGraph integration layer, moved model and database paths to async workflows, and added conversation memory, delivery automation, and observability.

`FastAPI` `LangGraph` `Azure AI Search` `Cosmos DB` `Azure Container Apps` `OpenTelemetry`

---

## Selected public builds

<sub>Small, focused builds: technical assessments, applied prototypes, and ideas worth testing in public.</sub>

### [LangGraph E-Commerce Agent](https://github.com/balalaika-tools/langraph-ecommerce-agent)

**Technical assessment · Conversational analytics agent**

A stateful LangGraph system that routes questions, generates and retries BigQuery SQL, synthesizes business insights, and preserves conversational context behind a FastAPI service.

### [Tariff Calculator](https://github.com/balalaika-tools/Tariff-Calculator)

**Technical assessment · Hybrid AI/deterministic backend**

Turns natural-language vessel descriptions into auditable port-tariff breakdowns: an LLM extracts structured inputs, while typed Python domain logic owns every financial calculation.

### [Sheet-Agent](https://github.com/balalaika-tools/Sheet-Agent)

**Applied R&D prototype · Agentic spreadsheet automation**

A decomposer–actor–reflector workflow that translates natural-language spreadsheet tasks into sandboxed Python execution, evaluates the result, and repairs failures through bounded feedback loops.

---

## Working stack

| Layer | Tools I reach for |
|---|---|
| **Agent systems** | LangGraph, LangChain, MCP/FastMCP, multi-agent workflows, persistent memory |
| **Models & retrieval** | Amazon Bedrock/AgentCore, Azure AI Foundry, Vertex AI, OpenAI, Anthropic, RAG, hybrid search, reranking |
| **Backend & data** | Python, FastAPI, asyncio, Go, PostgreSQL, Redis, Kafka, Celery, Pydantic |
| **Identity & governance** | OAuth 2.0/OIDC, M2M, RBAC, tenant isolation, governed tool access, AI gateways |
| **Reliability & evaluation** | OpenTelemetry, Langfuse, LangSmith, Groundcover, Ragas, DeepEval, distributed tracing |
| **Cloud & delivery** | AWS, Azure, Google Cloud, Docker, Kubernetes, Terraform, Bicep, GitHub Actions |

---

<div align="center">

### Agents reason. Software enforces. Traces tell the truth.

<sub>Thessaloniki, Greece · Building production AI systems from architecture to operations</sub>

</div>
