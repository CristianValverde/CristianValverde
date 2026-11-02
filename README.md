# Hi, I'm Cristian 👋

**Data & AI Engineer** in IE University's Digital Learning department · Madrid · building toward **agentic engineering**.

I own the data processes (ELT/ETL, metrics, reporting) that run on AWS for our learning analytics. On my own initiative I design the agentic systems around them: the harnesses that let coding agents work safely in production repositories, and multi-agent pipelines with a human in the loop. I'm interested in agentic systems that produce consistent, reliable outputs through guardrails, observability and evals.

## What I work on

- **Data engineering.** Daily ELT/ETL in Python, SQL and Papermill notebooks feeding an S3 + Redshift lakehouse, custom learning-analytics metrics, and Power BI reporting.
- **Agentic engineering.**
  - A harness that lets coding agents (Claude Code, Codex) operate safely on a production ETL repository: hooks, guardrails, commit and release-tagging conventions, and automatic validation with Docker + Papermill.
  - A multi-agent self-healing data pipeline (n8n, Amazon Bedrock AgentCore, LangGraph): agents fix a failed notebook and open a pull request, I approve it, and an automated recovery reprocesses the affected days. *Currently being implemented.*
- **LLM tooling.** Internal Custom GPTs, context and instruction engineering.
- **Currently exploring.** Spec-driven development (SDD).

## Featured projects

| Project | What it is |
| --- | --- |
| [gridguard-espana](https://github.com/CristianValverde/gridguard-espana) | Multi-agent system (Google ADK + Gemini) that monitors the Spanish power grid: 5 custom MCP servers, deterministic ML, RAG and guardrail hooks. When the LLM did not reliably follow the escalation policy, I moved it into a unit-tested deterministic planner. 300 offline tests; runs locally. |
| [hermes-dashboard](https://github.com/CristianValverde/hermes-dashboard) | Local analytics cockpit for LLM-agent telemetry: sessions, tool calls, token spend, errors and system health. Python/Flask + React. |
| [tldr-newsletter-digest](https://github.com/CristianValverde/tldr-newsletter-digest) | Daily pipeline: Gmail intake, article extraction and deduplication, an LLM-written digest, delivered by email and Telegram. Runs as a scheduled Codex task. |
| [mcp-shell-server](https://github.com/CristianValverde/mcp-shell-server) | Run Claude as a remote dev agent on a local machine via Docker + ngrok MCP. A development tool: read the security notes before exposing it. |
| [neotokyo-powershell-theme](https://github.com/CristianValverde/neotokyo-powershell-theme) | Windows Terminal + PowerShell theme with an automated installer. |

## Tech

![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat&logo=postgresql&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat&logo=amazonaws&logoColor=white)
![Amazon Redshift](https://img.shields.io/badge/Redshift-8C4FFF?style=flat&logo=amazonredshift&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat&logo=git&logoColor=white)
![LangGraph](https://img.shields.io/badge/LangChain%20%7C%20LangGraph-1C3C3C?style=flat&logo=langchain&logoColor=white)
![Google ADK](https://img.shields.io/badge/Google%20ADK%20%2B%20Gemini-8E75B2?style=flat&logo=googlegemini&logoColor=white)
![MCP](https://img.shields.io/badge/MCP-000000?style=flat&logo=modelcontextprotocol&logoColor=white)
![n8n](https://img.shields.io/badge/n8n-EA4B71?style=flat&logo=n8n&logoColor=white)
![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=flat&logo=powerbi&logoColor=black)

## Background

MSc in Big Data & Business Analytics (9.78/10) and a BBA, with earlier experience in IT-services bids at Minsait (Indra), e-invoicing at IBM and operations at a design-software startup. Trilingual: English, Spanish and Portuguese.

📫 [LinkedIn](https://www.linkedin.com/in/cristian-de-andrade-valverde/)
