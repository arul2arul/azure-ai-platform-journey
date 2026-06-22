Phase 1 — Audit & Fill Gaps (2 weeks: late June)

Compressed — you've already shipped this in production.


Map your existing agent work against AI-103 exam objectives (Microsoft Learn AI-103 study guide)
Identify real gaps only: likely candidates — Azure AI Content Safety, Translator/Speech services, Knowledge Mining specifics
Build artifact: gap-analysis doc in GitHub repo


Phase 2 — Azure AI Foundry & RAG Deep Dive (3 weeks: July)


Azure AI Foundry: project structure, model deployment, evaluation, prompt flow
Azure AI Search: vector + hybrid search, indexing strategies, chunking patterns
RAG patterns: grounding, citation, hallucination mitigation
Build artifact: one RAG app on AI Foundry, properly evaluated (not just "it runs")


Phase 3 — AI-103 Exam (Late July / Early August)


Sit the exam while Phases 1–2 are fresh
Why now, not at the end: validates platform fundamentals before you build the higher-value client-facing pieces; gives EPAM a deliverable early rather than in December


Phase 4 — Copilot Studio & M365 Copilot Extension (August–September)

This is your highest client-value phase — expand it.


Copilot Studio: custom agent authoring, connectors, topics, generative answers
Microsoft Graph: extending M365 Copilot with custom plugins/connectors
Governance: data loss prevention, sensitivity labels, agent permission scoping (client will care about this more than the agent logic itself)
Build artifact: one Copilot Studio agent integrated with a real M365 Graph data source, documented end-to-end


Phase 5 — AI Platform Engineering (October–November)

Your differentiator — DevOps background applied to AI infra.


IaC for AI resources: Bicep/Terraform modules for AI Foundry projects, AI Search, OpenAI deployments
CI/CD for AI: prompt/RAG regression testing in pipelines, automated evaluation gates
AKS for AI workloads: hosting inference services, autoscaling for token-heavy workloads
Security: Managed Identity for AI resources, API Management fronting AI endpoints, monitoring (Azure Monitor + Application Insights for agent telemetry)
Build artifact: a GitOps-managed AI Foundry deployment — infra and agent config both as code


Phase 6 — Portfolio Consolidation (December)


Clean up and document all 3 build artifacts in GitHub with architecture diagrams
Internal write-up for EPAM: "what I built, what it solves for the client"
Decide: continue toward a second Microsoft cert (e.g., Copilot-related path, check current Learn catalog) or pivot toward Claude Architect cert in Q1 2027