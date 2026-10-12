# What I studied, and what the projects show

Certificates prove a course was finished, not what was learned. This page maps my study to evidence,
in three levels:

- **Studied:** covered in a course.
- **Practiced:** used in my work as a Product Owner at Wine Locals. That code is private (it carries
  client and revenue data), so this is my own account, not something you can check here.
- **Demonstrated:** you can verify it in a public repository: code, tests and the reasoning in the README.

Where something was only studied, it says so.

## Alura careers (completed October 2026)

### AI Product Builder · 4 levels

| Level | Courses |
|---|---|
| Thinking with AI | Prompt Engineering · Context Engineering |
| 1. Strategy in building products | Product management fundamentals · AI applied to products · Design Thinking · Product Discovery · Lumina case · Checkpoint |
| 2. Automation and prototyping | Claude Code · Codex · Lovable · Claude + Lovable, problem to prototype · Supabase · Process automation with n8n · PM3 case · Checkpoint |
| 3. Validation and metrics | Microsoft Clarity · User research and testing with Maze · AI products: evals, observability and compliance · Grupo Boticário case · Checkpoint |

### AI Specialist · 3 levels

| Level | Courses |
|---|---|
| 1. AI at work | Computational thinking · Python for AI · AI assistants and agents · n8n (flows, data collection, knowledge bases) · Langflow · Copilot Studio · Claude Cowork |
| 2. Agents and RAG | AI for the job market · RAG with LangChain · Advanced RAG · LangGraph · Agent protocols (MCP, A2A, AG-UI) · MCP with n8n · Hugging Face · CrewAI |
| 3. Strategy and operations | AI strategy · LLM observability with LangFuse · AI governance · AI applied to products · Building a business with AI · AI pipelines on Azure, AWS and GCP · MLflow |

### Tech Lead in the AI Era · 3 levels

| Level | Courses |
|---|---|
| 1. Leading people | Technical leadership · Self-leadership · Leadership profiles · Tech Lead and AI · Psychological safety · Leadership in the AI era |
| 2. Engineering practice | Extreme Programming · Kanban and Scrum · Code review · Technical debt · Strategic communication · Feedback · Agile soft skills |
| 3. Systems and strategy | Software architecture for tech leads · Cost of engineering · AI literacy · High-performance teams · Talent retention · Learning agility · Flow and predictability · Engineering and the product lifecycle · Stakeholder management · Change management · Strategic leadership |

Also: Alura track *Product Management* (discovery, roadmap, prioritization, validation, growth,
Design Sprint) and *Scrum*.

## Competencies and evidence

| Competency | Studied | Practiced at work | Demonstrated |
|---|---|---|---|
| Framing a problem, users and a testable hypothesis | Product Discovery, Design Thinking | Yes | All three READMEs separate the problem, the audience and unvalidated hypotheses |
| Data cleaning and analysis in Python | Python for AI | Yes (GA4, sales and ad pipelines) | [Atraso](https://github.com/BernardoBonecher/atraso): 1M rows of ANAC data; a time-zone assumption and mixed timestamp formats found by testing the data, not the docs |
| Honest metrics | Validation: actionable vs. vanity metrics | Yes | [Atraso](https://github.com/BernardoBonecher/atraso): 95% Wilson intervals, thin samples hidden; [Sinal](https://github.com/BernardoBonecher/sinal): an eval that first overstated recall, caught and corrected |
| Data visualization and accessibility | Claude + Lovable | Yes (dashboards) | [Atraso](https://github.com/BernardoBonecher/atraso): color palette checked for color blindness, table view for every chart |
| Prompt and context engineering, structured output | Thinking with AI | Daily, with Claude Code | [Sinal](https://github.com/BernardoBonecher/sinal): JSON-schema-bound extraction and theming |
| Evals, grounding, LLM observability | Evals and observability; LangFuse | No | [Sinal](https://github.com/BernardoBonecher/sinal): every quote verified against the transcript; recall and precision against planted ground truth; per-call token and time log |
| AI governance and privacy | AI governance | Yes (no personal data in public code) | [Sinal](https://github.com/BernardoBonecher/sinal): personal data redacted before the model; local model so transcripts stay on the machine. [Rede de Cuidado](https://github.com/BernardoBonecher/rede-de-cuidado): closed sign-ups for a health-adjacent app |
| Backend with auth and authorization (Supabase) | Supabase; Lovable | No | [Rede de Cuidado](https://github.com/BernardoBonecher/rede-de-cuidado): Row Level Security, database functions, realtime; 14 security tests as real users |
| Accessible, mobile-first UX | Product Design; Maze; Clarity | Partly | [Rede de Cuidado](https://github.com/BernardoBonecher/rede-de-cuidado): legible type, large targets, status never by color alone |
| Testing and CI | XP; code review | Partly | All three have automated tests (Atraso 21, Sinal 35, Rede de Cuidado 21 + 14 security tests). In Rede de Cuidado, CI runs them and deploys only if they pass |
| AI-assisted development (Claude Code) | Claude Code; Codex | Daily | All three were built with Claude Code; the READMEs document the decisions and the mistakes |
| Process automation (n8n) | n8n (4 courses) | No | Only studied |
| RAG, LangChain, LangGraph, CrewAI, multi-agent systems | AI Specialist level 2 | No | Only studied |
| MLflow, cloud AI pipelines, Hugging Face | AI Specialist levels 2–3 | No | Only studied |
| Technical leadership, stakeholders, change management | Tech Lead career | As a Product Owner | Not something code can show |
