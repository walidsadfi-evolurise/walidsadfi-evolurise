# Walid Sadfi

**Forward Deployed Engineer · AI agents in production · WooCommerce · Infrastructure**

I join a team, scope one process with the people who run it, and ship an AI agent that holds up in production: connected to the tools the company already uses (WooCommerce, CRM, LMS, ERP), with guardrails, evals and monitoring. Eight years of WordPress/WooCommerce and PHP/TypeScript before that, so the agent lands in a system I can also build and operate.

## What I ship

| | |
| --- | --- |
| **Agents & RAG** | Lead qualification and routing, on-demand drafting over private document indexes, explainable scoring. Code-first agents, versioned, evaluated on every change. |
| **Agentic commerce** | Making WooCommerce stores readable and buyable by AI shopping agents: product data, structured data, Store API, MCP, ACP readiness. |
| **Infrastructure** | nginx, Docker, Kubernetes, AWS. The agent and the platform it runs on come from the same person. |

## Open source

| Repo | What it does |
| --- | --- |
| [woocommerce-agent-ready](https://github.com/walidsadfi-evolurise/woocommerce-agent-ready) | Audit a WooCommerce store for agentic commerce readiness. Score /100, a fix for every point lost. |
| [woocommerce-mcp-server](https://github.com/walidsadfi-evolurise/woocommerce-mcp-server) | MCP server for WooCommerce: read tools with PII redaction, every write goes through a human-approved proposal. TypeScript. |
| [lead-triage-agent](https://github.com/walidsadfi-evolurise/lead-triage-agent) | Inbound lead qualification: LLM extraction with rule fallback, explainable scoring, declarative routing, guardrails and audit. Python. |
| [agent-evals-harness](https://github.com/walidsadfi-evolurise/agent-evals-harness) | Evaluate any LLM agent from YAML: checks, judges, repeated trials, latency percentiles, baseline regressions, JUnit, CI gate. Python. |
| [private-rag-kit](https://github.com/walidsadfi-evolurise/private-rag-kit) | Self-hosted RAG over private documents: hybrid search, verified citations, refusal when the sources are missing, eval loop. Python, pgvector. |
| [docker-wordpress-prod](https://github.com/walidsadfi-evolurise/docker-wordpress-prod) | Production WordPress/WooCommerce stack: Caddy, nginx FastCGI cache, PHP-FPM, MariaDB, Redis, encrypted S3 backups. |
| [home-assistant-llm-agent](https://github.com/walidsadfi-evolurise/home-assistant-llm-agent) | Natural-language control of Home Assistant: LLM planner behind an allowlist, confirmation for risky actions, state verification, audit. Python. |
| [wordpress-k8s-stack](https://github.com/walidsadfi-evolurise/wordpress-k8s-stack) | WordPress/WooCommerce on Kubernetes: immutable image, FastCGI cache, HPA, default-deny NetworkPolicies, PSS restricted, encrypted backups, kind e2e in CI. |
| [aws-rag-infra](https://github.com/walidsadfi-evolurise/aws-rag-infra) | Terraform: private RAG API on AWS — VPC + endpoints, ALB/TLS, ECS Fargate autoscaling, RDS pgvector Multi-AZ, S3, Secrets Manager, alarms. tflint + checkov in CI. |
| [wp-ai-disclosure](https://github.com/walidsadfi-evolurise/wp-ai-disclosure) | WordPress plugin: detects AI assistants on the site and shows the EU AI Act art. 50 transparency notice. |
| [Basic-Auth-for-WP-Admin](https://github.com/walidsadfi-evolurise/Basic-Auth-for-WP-Admin) | HTTP basic auth in front of wp-admin and wp-login. |
| [bulk-plugin-uploader](https://github.com/walidsadfi-evolurise/bulk-plugin-uploader) | Upload, install and activate many WordPress plugins in one go. |
| [drupal-user-switcher](https://github.com/walidsadfi-evolurise/drupal-user-switcher) | Impersonate any Drupal account to debug permissions, with a one-click return. |
| [Exit-intent-popup](https://github.com/walidsadfi-evolurise/Exit-intent-popup) | Lightweight exit-intent popup for WordPress. |

Next: WAF and Bedrock providers for the AWS module, a reranker for the RAG kit, multi-turn cases in the evals harness. Issues and PRs welcome.

## How I work

- One process at a time, measured before and after.
- Human approval on every irreversible action an agent could take.
- AI disclosure built in (EU AI Act, art. 50).
- Six months of evals and monitoring included on everything I deploy.

## Contact

[Malt](https://www.malt.fr/profile/walidsadfi) · [LinkedIn](https://www.linkedin.com/in/walid-s) · [evolurise.com](https://www.evolurise.com)

Based in France, working remotely, on-site when it helps.
