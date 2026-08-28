<p align="right">
  <strong>English</strong> &nbsp;|&nbsp; <a href="./README.zh-CN.md">简体中文</a>
</p>

<p align="center">
  <img src="./assets/profile-header.svg?v=20260801-3" width="1280" alt="Zhou J. - Python systems for data workflows, AI agents, and automation" />
</p>

<p align="center">
  <strong>I build reliable Python systems for data workflows, AI agents, and automation.</strong><br />
  <sub>Python engineering · AI agent infrastructure · observable automation</sub>
</p>

## Open Source · 开源协作

I contribute to AI agents, model-provider integrations, cross-platform runtimes, analytics, and TypeScript tooling.

**Merged upstream**

- **[Hugging Face PEFT #3546](https://github.com/huggingface/peft/pull/3546) · Add a bank-1024 VBLoRA configuration for MetaMathQA** — contributes a reproducible Llama 3.2 3B experiment configuration selected through a bounded search that improved GSM8K accuracy while documenting the adapter-size trade-off.
- **[Apache Airflow #70937](https://github.com/apache/airflow/pull/70937) · Support Monaco Editor 0.56** — moves Airflow's Monaco integration to public package exports while preserving its patched Python f-string highlighting.
- **[DeepTutor #753](https://github.com/HKUDS/DeepTutor/pull/753) · Fix editing immediately after save** — uses the newly persisted message snapshot so a stale React state value cannot break the first edit.
- **[DeepTutor #756](https://github.com/HKUDS/DeepTutor/pull/756) · Give research read-only access to Obsidian** — lets the research pipeline search, read, and list trusted vault content without mounting an unavailable RAG index.
- **[OmniRoute #9218](https://github.com/diegosouzapw/OmniRoute/pull/9218) · Keep hidden models out of the picker** — filters operator-hidden models across system, fallback, alias, custom, and live-fetched sources.
- **[WorldMonitor #6088](https://github.com/koala73/worldmonitor/pull/6088) · Preserve collector timeouts on older runtimes** — keeps the 20-second deadline and caller cancellation working when modern `AbortSignal` helpers are unavailable.
- **[Hermes Agent #77522](https://github.com/NousResearch/hermes-agent/pull/77522) · Reduce repeated subscription lookups** — reuses one feature snapshot per toolset-list request; both commits from [#76072](https://github.com/NousResearch/hermes-agent/pull/76072) were cherry-picked unchanged with authorship preserved.

**Open contributions**

- **Hermes CN:** [Prevent Desktop runtime downgrades #540](https://github.com/Eynzof/Hermes-CN-Desktop/pull/540) · [Handle locked runtime files on Windows #544](https://github.com/Eynzof/Hermes-CN-Desktop/pull/544) · [Run cron Python scripts in the frozen runtime #134](https://github.com/Eynzof/Hermes-CN-Core/pull/134)
- **Hermes Agent:** [Apply provider hooks to the Anthropic transport #75480](https://github.com/NousResearch/hermes-agent/pull/75480) · [Stabilize Bedrock Mantle multi-turn sessions #75561](https://github.com/NousResearch/hermes-agent/pull/75561) · [Persist Desktop message reaction settings #77302](https://github.com/NousResearch/hermes-agent/pull/77302) · [Fix xAI web-search alias routing #79282](https://github.com/NousResearch/hermes-agent/pull/79282) · [Restore timestamped curator archives #83613](https://github.com/NousResearch/hermes-agent/pull/83613) · [Validate webhook delivery targets #84184](https://github.com/NousResearch/hermes-agent/pull/84184) · [Recognize Slack app bot ID mentions #85885](https://github.com/NousResearch/hermes-agent/pull/85885)

**Selected review work**

- **Hermes Agent:** [Bound Gateway channel-directory initialization #79060](https://github.com/NousResearch/hermes-agent/pull/79060) · [Review cron repeat lifecycle validation #82495](https://github.com/NousResearch/hermes-agent/pull/82495) · [Review binary detection correctness #82494](https://github.com/NousResearch/hermes-agent/pull/82494)

## Selected Work · 代表作品

### 01 / [Portfolio Decision Workbench](https://github.com/szzhoujiarui/portfolio-decision-workbench)

A reproducible Python backend case study for resilient market-data ingestion, provider health isolation, provenance-preserving delivery, data-quality audits, and contract-first FastAPI APIs. It includes a deterministic offline demo, committed fixtures, SQLite persistence, OpenAPI contract checks, and a documented migration path from legacy Flask routes.

`Python` · `FastAPI` · `SQLite` · `Pydantic` · `pytest`

### 02 / [WebhookOps Reliability Console](https://github.com/szzhoujiarui/webhookops-reliability-console)

A runnable FastAPI and React demo that verifies signed webhooks, rejects duplicate events, retries failures, moves exhausted events to a dead-letter state, and supports manual replay with a complete audit history.

`Python` · `FastAPI` · `React` · `SQLite` · `Docker`

### 03 / [Python Data Orchestration Lab](https://github.com/szzhoujiarui/python-data-orchestration-lab)

Collects business data through provider adapters, converts it to one validated record model, deduplicates and merges matching companies, then saves to SQLite or exports to CSV and Google Sheets. The offline sample runs without external credentials.

`Python` · `Pydantic` · `SQLite` · `pandas` · `pytest`

### 04 / [Lead Operations Automation](https://github.com/szzhoujiarui/lead-ops-automation)

Validates, deduplicates, scores, and routes incoming leads through n8n. PostgreSQL-backed jobs support retries and manual replay, while 25 Playwright tests verify HubSpot- and Slack-compatible delivery.

`n8n` · `PostgreSQL` · `Docker Compose` · `Playwright`

**Other projects:** [Drawing Vectorization](https://github.com/szzhoujiarui/opencv-technical-drawing-vectorizer) · [Deskflow Studio](https://github.com/szzhoujiarui/deskflow-studio) · [Excel Automation](https://github.com/szzhoujiarui/xlsm-demo) · [WordPress Quote Manager](https://github.com/szzhoujiarui/wp-service-quote-manager)

## Engineering Practice · 工程方法

- Define inputs, outputs, constraints, and acceptance criteria before implementation.
- Integrate external services through clear interfaces that support replacement, testing, and recovery.
- Deliver reproducible verification commands, automated tests, and documented scope and limitations.

<p align="center">
  <sub>中国开发者 / OPEN-SOURCE CONTRIBUTOR / ZHOU J.</sub>
</p>
