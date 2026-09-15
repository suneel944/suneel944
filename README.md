# Hi there, I'm Suneel! 👋

> Automation, AI, and problems worth solving — less manual grind, more leverage.

---
## 💫 About Me

- Building **multi-agent developer tooling** — coordination, isolation and retrieval layers that keep coding agents honest about what they touched.
- Build **testing platforms** (UAF · Critter · ATAS): web, API, mobile, device farms, CI/CD, reporting.
- **Enterprise-grade automation** — frameworks and control planes for UI/API/mobile with orchestration, runners, CI/CD, and reporting at scale.
- **AI-assisted testing:** tickets/designs → scaffolding & gaps; humans keep assertions and prod realism.
- Stack: **Python, TypeScript, Java**, Docker, K8s, PostgreSQL, Playwright, Selenium/Appium, Spring Boot.

## 🔭 What I'm building now

**[agent-parley](https://github.com/suneel944/agent-parley)** — run Claude Code, Codex, Copilot, Gemini, OpenCode and Amp side by side in isolated Git worktrees. Shared issue ownership, reservations, explicit handoffs, and one read-only screen showing who owns what. Every claim, handoff and refusal is recorded and attributed. MIT, Python 3.12+, zero runtime dependencies, installs with `uv tool install agent-parley`.

<p align="center">
<a href="https://github.com/suneel944/agent-parley/releases"><img src="https://img.shields.io/github/v/release/suneel944/agent-parley?style=flat&color=blue" alt="Release"/></a>
<img src="https://img.shields.io/badge/runtime_dependencies-0-brightgreen?style=flat" alt="Zero runtime dependencies"/>
<img src="https://img.shields.io/badge/python-3.12%2B-blue?style=flat" alt="Python 3.12+"/>
<a href="https://github.com/suneel944/agent-parley/blob/main/LICENSE"><img src="https://img.shields.io/badge/license-MIT-green?style=flat" alt="MIT license"/></a>
</p>

<p align="center">
<a href="https://github.com/suneel944/agent-parley"><img src="https://cdn.jsdelivr.net/gh/suneel944/agent-parley@main/docs/assets/screenshot-top.svg" width="820" alt="agent-parley showing three lanes with issues, mail, leases, denials and served calls"/></a>
</p>

**A context fabric for coding agents** (in-house) — subsystem summaries plus AST-level code chunks plus call/impact graphs, fused into one retrieval path so an agent cites `file:line` instead of guessing. Paired with enforcement hooks and token-burn telemetry that measure whether retrieval actually earned its cost.

The through-line with the testing work: an agent is only useful when its output can be checked. Grounding, attribution and gates are how you check it.

## 🏗️ Platform work (private)

**MTAAS — Testing-as-a-Service, built end to end.** A test suite stops being a command you run on a laptop and becomes a service you call. A Spring Boot control plane exposes REST APIs to discover, execute, monitor and report; execution is decoupled into runners — local CLI, external process, or ephemeral Kubernetes Jobs. Runners stream lifecycle events back over an internal API, the server persists every execution, result, step and media attachment, and fans real-time updates to dashboards over Redis Pub/Sub and Server-Sent Events.

A 9-module Maven monorepo keeps orchestration, execution, the Playwright and Appium libraries, shared contracts, configuration and the product test layer separate while sharing one set of DTOs and one config source. Java 21 · Spring Boot · JUnit · Playwright · Appium · Testcontainers · PostgreSQL · Redis · S3 · Allure · Kubernetes.

## AI & tooling

- **Graphs + MCP:** ground agents in the repo, not guesses.  
- **Spec-first:** extend tests from real API/UI specs — no toy shortcuts.  
- **Split roles:** runners prove correctness; LLMs speed drafting and exploration.
- **Attribution over trust:** who claimed, who changed, what was denied — recorded, not assumed.

<table><tr>
<td><img src="https://img.shields.io/badge/Cursor-000000?style=flat&logo=cursor&logoColor=white" alt="Cursor"/></td>
<td><img src="https://img.shields.io/badge/Anthropic-191919?style=flat&logo=anthropic&logoColor=white" alt="Anthropic"/></td>
<td><img src="https://img.shields.io/badge/OpenAI-412991?style=flat&logo=openai&logoColor=white" alt="OpenAI"/></td>
<td><img src="https://img.shields.io/badge/Claude_Code-D97757?style=flat&logo=claude&logoColor=white" alt="Claude Code"/></td>
<td><img src="https://img.shields.io/badge/Codex-412991?style=flat&logo=openai&logoColor=white" alt="Codex"/></td>
<td><img src="https://img.shields.io/badge/MCP-242424?style=flat&logo=modelcontextprotocol&logoColor=white" alt="MCP"/></td>
<td><img src="https://img.shields.io/badge/Milvus-00A1EA?style=flat&logo=milvus&logoColor=white" alt="Milvus"/></td>
<td><img src="https://img.shields.io/badge/Ollama-000000?style=flat&logo=ollama&logoColor=white" alt="Ollama"/></td>
</tr></table>

## Banking Standards
<table><tr>
<td><img src="https://github.com/user-attachments/assets/f206469c-32fd-4822-a12f-5d40de9ffc9d" alt="Open Banking" width="40" height="30"/></td>
<td><img src="https://github.com/user-attachments/assets/41eeb366-c575-4cfa-bdfc-7ae8c0f74bd3" alt="Open Finance" width="40" height="30"/></td>
</tr></table>

## Languages
<table><tr>
<td><img src="https://www.vectorlogo.zone/logos/python/python-icon.svg" alt="Python" width="30" height="30"/></td>
<td><img src="https://www.vectorlogo.zone/logos/typescriptlang/typescriptlang-icon.svg" alt="TypeScript" width="30" height="30"/></td>
<td><img src="https://www.vectorlogo.zone/logos/javascript/javascript-icon.svg" alt="JavaScript" width="30" height="30"/></td>
<td><img src="https://www.vectorlogo.zone/logos/java/java-icon.svg" alt="Java" width="30" height="30"/></td>
<td><img src="https://www.vectorlogo.zone/logos/w3_html5/w3_html5-icon.svg" alt="HTML5" width="30" height="30"/></td>
</tr></table>

## Task Queue
<table><tr>
<td><img src="https://github.com/user-attachments/assets/d8bb4930-3c8d-416a-a356-a6e81fdfe1fb" alt="Celery" width="30" height="30"/></td>
</tr></table>

## Message Brokers
<table><tr>
<td><img src="https://www.vectorlogo.zone/logos/rabbitmq/rabbitmq-icon.svg" alt="RabbitMQ" width="30" height="30"/></td>
<td><img src="https://github.com/user-attachments/assets/c6f69b08-29be-4466-9af4-bbcd69eb0275" alt="Kafka" width="30" height="30"/></td>
</tr></table>

## Protocols
<table><tr>
<td><img src="https://github.com/user-attachments/assets/8f0e6367-4e0b-4dd0-aaed-36863c14fe23" alt="MQTT" width="30" height="30"/></td>
</tr></table>

## Frameworks
<table><tr>
<td><img src="https://www.vectorlogo.zone/logos/palletsprojects_flask/palletsprojects_flask-icon.svg" alt="Flask" width="30" height="30"/></td>
<td><img src="https://raw.githubusercontent.com/gilbarbara/logos/main/logos/selenium.svg" alt="Selenium" width="30" height="30"/></td>
<td><img src="https://raw.githubusercontent.com/gilbarbara/logos/main/logos/playwright.svg" alt="Playwright" width="30" height="30"/></td>
<td><img src="https://github.com/user-attachments/assets/5d135fd8-1c10-4c29-aede-b377759bade6" alt="WebdriverIO" width="30" height="30"/></td>
<td><img src="https://github.com/user-attachments/assets/27d6dc4c-f5b5-43f1-9eb8-1d1155e0042d" alt="FastAPI" width="30" height="30"/></td>
<td><img src="https://github.com/user-attachments/assets/5ab21a24-5a8d-456a-934a-c400461e8c1f" alt="LocustIO" width="30" height="30"/></td>
<td><img src="https://github.com/user-attachments/assets/7e3a1333-adb3-4dc3-b483-4ede66b8ca54" alt="Appium" width="30" height="30"/></td>
<td><img src="https://www.vectorlogo.zone/logos/browserstack/browserstack-icon.svg" alt="BrowserStack" width="30" height="30"/></td>
<td><img src="https://www.vectorlogo.zone/logos/pytest/pytest-icon.svg" alt="Pytest" width="30" height="30"/></td>
<td><img src="https://www.vectorlogo.zone/logos/springio/springio-icon.svg" alt="Spring Boot" width="30" height="30"/></td>
<td><img src="https://img.shields.io/badge/JUnit-25A162?style=flat&logo=junit5&logoColor=white" alt="JUnit"/></td>
<td><img src="https://img.shields.io/badge/Testcontainers-291A3F?style=flat&logo=docker&logoColor=white" alt="Testcontainers"/></td>
<td><img src="https://img.shields.io/badge/Allure-6E4AFF?style=flat" alt="Allure"/></td>
</tr></table>

## Databases
<table><tr>
<td><img src="https://github.com/user-attachments/assets/0bf9f278-8072-4fa1-8353-e9b80196f2b5" alt="Mongo" width="30" height="30"/></td>
<td><img src="https://github.com/user-attachments/assets/cc6032c6-4e04-43f4-ac74-f520e4f7abd1" alt="ElasticSearch" width="30" height="30"/></td>
<td><img src="https://github.com/user-attachments/assets/58629608-a022-4898-879d-22e03627bbfe" alt="Redis" width="30" height="30"/></td>
<td><img src="https://github.com/user-attachments/assets/7389d83d-7089-40b7-980a-1894e9323cc8" alt="PostgresSQL" width="30" height="30"/></td>
</tr></table>

## Observability
<table><tr>
<td><img src="https://github.com/user-attachments/assets/f04efe0e-0372-4bb5-aa31-d4687e51e0c3" alt="Prometheus" width="30" height="30"/></td>
<td><img src="https://www.vectorlogo.zone/logos/grafana/grafana-icon.svg" alt="Grafana" width="30" height="30"/></td>
</tr></table>

## Tools
<table><tr>
<td><img src="https://www.vectorlogo.zone/logos/kubernetes/kubernetes-icon.svg" alt="Kubernetes" width="30" height="30"/></td>
<td><img src="https://www.vectorlogo.zone/logos/argoprojio/argoprojio-icon.svg" alt="ArgoCD" width="30" height="30"/></td>
<td><img src="https://github.com/user-attachments/assets/399b274c-10b2-4172-ab86-829b330e037a" alt="Docker" width="30" height="30"/></td>
<td><img src="https://www.vectorlogo.zone/logos/amazon_aws/amazon_aws-icon.svg" alt="AWS" width="30" height="30"/></td>
<td><img src="https://github.com/user-attachments/assets/1cc76822-262d-4269-9570-37f6a8b84c73" alt="Jira" width="30" height="30"/></td>
<td><img src="https://www.vectorlogo.zone/logos/apache_maven/apache_maven-icon.svg" alt="Maven" width="30" height="30"/></td>
<td><img src="https://github.com/user-attachments/assets/18d8fb39-aab2-4efa-ae97-c2a1d3829382" alt="n8n" width="30" height="30"/></td>
<td><img src="https://github.com/user-attachments/assets/86096fe0-77ac-4102-834e-52154243e9ee" alt="GitHub" width="30" height="30"/></td>
<td><img src="https://www.vectorlogo.zone/logos/jenkins/jenkins-icon.svg" alt="Jenkins" width="30" height="30"/></td>
</tr></table>

## 🌐 Socials
<table><tr>
<td><a href="https://linkedin.com/in/suneel944" target="_blank" rel="noopener noreferrer"><img src="https://www.vectorlogo.zone/logos/linkedin/linkedin-icon.svg" alt="LinkedIn" height="30" width="30"/></a></td>
<td><a href="https://stackoverflow.com/users/6090958" target="_blank" rel="noopener noreferrer"><img src="https://www.vectorlogo.zone/logos/stackoverflow/stackoverflow-icon.svg" alt="Stack Overflow" height="30" width="30"/></a></td>
<td><a href="mailto:suneel944@live.com"><img src="https://github.com/user-attachments/assets/9f1f973d-83fb-465c-90dc-09c40bd75bf1" alt="Email" height="30" width="30"/></a></td>
</tr></table>
