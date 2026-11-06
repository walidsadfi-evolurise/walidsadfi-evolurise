# Walid Sadfi

**Forward Deployed Engineer · AI agents in production · WooCommerce · Infrastructure**

[![Malt](https://img.shields.io/badge/Malt-available-ff5a5f?logo=malt&logoColor=white)](https://www.malt.fr/profile/walidsadfi) [![LinkedIn](https://img.shields.io/badge/LinkedIn-walid--s-0a66c2?logo=linkedin&logoColor=white)](https://www.linkedin.com/in/walid-s) [![Evolurise](https://img.shields.io/badge/Evolurise-web%20%26%20AI%20agency-111827)](https://www.evolurise.com)

![TypeScript](https://img.shields.io/badge/TypeScript-3178c6?logo=typescript&logoColor=white) ![Python](https://img.shields.io/badge/Python-3776ab?logo=python&logoColor=white) ![PHP](https://img.shields.io/badge/PHP-777bb4?logo=php&logoColor=white) ![WordPress](https://img.shields.io/badge/WordPress-21759b?logo=wordpress&logoColor=white) ![WooCommerce](https://img.shields.io/badge/WooCommerce-96588a?logo=woocommerce&logoColor=white) ![Docker](https://img.shields.io/badge/Docker-2496ed?logo=docker&logoColor=white) ![Kubernetes](https://img.shields.io/badge/Kubernetes-326ce5?logo=kubernetes&logoColor=white) ![Terraform](https://img.shields.io/badge/Terraform-7b42bc?logo=terraform&logoColor=white) ![AWS](https://img.shields.io/badge/AWS-232f3e?logo=amazonaws&logoColor=white) ![nginx](https://img.shields.io/badge/nginx-009639?logo=nginx&logoColor=white)

[![CI woocommerce-agent-ready](https://github.com/walidsadfi-evolurise/woocommerce-agent-ready/actions/workflows/ci.yml/badge.svg)](https://github.com/walidsadfi-evolurise/woocommerce-agent-ready/actions) [![CI private-rag-kit](https://github.com/walidsadfi-evolurise/private-rag-kit/actions/workflows/ci.yml/badge.svg)](https://github.com/walidsadfi-evolurise/private-rag-kit/actions) [![CI woocommerce-mcp-server](https://github.com/walidsadfi-evolurise/woocommerce-mcp-server/actions/workflows/ci.yml/badge.svg)](https://github.com/walidsadfi-evolurise/woocommerce-mcp-server/actions) [![CI lead-triage-agent](https://github.com/walidsadfi-evolurise/lead-triage-agent/actions/workflows/ci.yml/badge.svg)](https://github.com/walidsadfi-evolurise/lead-triage-agent/actions) [![CI wordpress-k8s-stack](https://github.com/walidsadfi-evolurise/wordpress-k8s-stack/actions/workflows/ci.yml/badge.svg)](https://github.com/walidsadfi-evolurise/wordpress-k8s-stack/actions) [![CI aws-rag-infra](https://github.com/walidsadfi-evolurise/aws-rag-infra/actions/workflows/ci.yml/badge.svg)](https://github.com/walidsadfi-evolurise/aws-rag-infra/actions)

I join a team, scope one process with the people who run it, and ship an AI agent that holds up in production: connected to the tools the company already uses (WooCommerce, CRM, LMS, ERP), with guardrails, evals and monitoring. Eight years of WordPress/WooCommerce and PHP/TypeScript before that, so the agent lands in a system I can also build and operate.

## What I ship

| | |
| --- | --- |
| **Agents & RAG** | Lead qualification and routing, on-demand drafting over private document indexes, explainable scoring. Code-first agents, versioned, evaluated on every change. |
| **Agentic commerce** | Making WooCommerce stores readable and buyable by AI shopping agents: product data, structured data, Store API, MCP, ACP readiness. |
| **Infrastructure** | nginx, Docker, Kubernetes, AWS. The agent and the platform it runs on come from the same person. |

## Open source

**Agents & RAG**

| Repo | What it does |
| --- | --- |
| [private-rag-kit](https://github.com/walidsadfi-evolurise/private-rag-kit) | Self-hosted RAG over private documents: hybrid search, verified citations, refusal when the sources are missing, eval loop. Python, pgvector. |
| [lead-triage-agent](https://github.com/walidsadfi-evolurise/lead-triage-agent) | Inbound lead qualification: LLM extraction with rule fallback, explainable scoring, declarative routing, guardrails and audit. Python. |
| [agent-evals-harness](https://github.com/walidsadfi-evolurise/agent-evals-harness) | Evaluate any LLM agent from YAML: checks, judges, repeated trials, latency percentiles, baseline regressions, JUnit, CI gate. Python. |
| [home-assistant-llm-agent](https://github.com/walidsadfi-evolurise/home-assistant-llm-agent) | Natural-language control of Home Assistant: LLM planner behind an allowlist, confirmation for risky actions, state verification, audit. Python. |

**Agentic commerce**

| Repo | What it does |
| --- | --- |
| [woocommerce-agent-ready](https://github.com/walidsadfi-evolurise/woocommerce-agent-ready) | Audit a WooCommerce store for agentic commerce readiness. Score /100, a fix for every point lost. |
| [woocommerce-mcp-server](https://github.com/walidsadfi-evolurise/woocommerce-mcp-server) | MCP server for WooCommerce: read tools with PII redaction, every write goes through a human-approved proposal. TypeScript. |
| [wp-ai-disclosure](https://github.com/walidsadfi-evolurise/wp-ai-disclosure) | WordPress plugin: detects AI assistants on the site and shows the EU AI Act art. 50 transparency notice. |

**Infrastructure**

| Repo | What it does |
| --- | --- |
| [docker-wordpress-prod](https://github.com/walidsadfi-evolurise/docker-wordpress-prod) | Production WordPress/WooCommerce stack: Caddy, nginx FastCGI cache, PHP-FPM, MariaDB, Redis, encrypted S3 backups. |
| [wordpress-k8s-stack](https://github.com/walidsadfi-evolurise/wordpress-k8s-stack) | WordPress/WooCommerce on Kubernetes: immutable image, FastCGI cache, HPA, default-deny NetworkPolicies, PSS restricted, encrypted backups, kind e2e in CI. |
| [aws-rag-infra](https://github.com/walidsadfi-evolurise/aws-rag-infra) | Terraform: private RAG API on AWS — VPC + endpoints, ALB/TLS, ECS Fargate autoscaling, RDS pgvector Multi-AZ, S3, Secrets Manager, alarms. tflint + checkov in CI. |

**WordPress & Drupal utilities**

| Repo | What it does |
| --- | --- |
| [Basic-Auth-for-WP-Admin](https://github.com/walidsadfi-evolurise/Basic-Auth-for-WP-Admin) | HTTP basic auth in front of wp-admin and wp-login. |
| [bulk-plugin-uploader](https://github.com/walidsadfi-evolurise/bulk-plugin-uploader) | Upload, install and activate many WordPress plugins in one go. |
| [Exit-intent-popup](https://github.com/walidsadfi-evolurise/Exit-intent-popup) | Lightweight exit-intent popup for WordPress. |
| [drupal-user-switcher](https://github.com/walidsadfi-evolurise/drupal-user-switcher) | Impersonate any Drupal account to debug permissions, with a one-click return. |
| [Evolurise-Conditionnal-Maintenance-Mode](https://github.com/walidsadfi-evolurise/Evolurise-Conditionnal-Maintenance-Mode) | Maintenance mode that stays off for the people who need to keep working on the site. |

Next: WAF and Bedrock providers for the AWS module, a reranker for the RAG kit, multi-turn cases in the evals harness. Issues and PRs welcome.

## How I work

- One process at a time, measured before and after.
- Human approval on every irreversible action an agent could take.
- AI disclosure built in (EU AI Act, art. 50).
- Six months of evals and monitoring included on everything I deploy.

## Contact

<a href="https://github.com/walidsadfi-evolurise"><img src="https://github-readme-stats.vercel.app/api?username=walidsadfi-evolurise&show_icons=true&include_all_commits=true&theme=default&hide_border=true" height="150" alt="GitHub stats" /></a> <a href="https://github.com/walidsadfi-evolurise"><img src="https://github-readme-stats.vercel.app/api/top-langs/?username=walidsadfi-evolurise&layout=compact&hide_border=true&langs_count=8" height="150" alt="Top languages" /></a>

[Malt](https://www.malt.fr/profile/walidsadfi) · [LinkedIn](https://www.linkedin.com/in/walid-s) · [evolurise.com](https://www.evolurise.com)

Based in France, working remotely, on-site when it helps.
