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

- **[Apache Airflow #70937](https://github.com/apache/airflow/pull/70937) · Support Monaco Editor 0.56** — moves Airflow's Monaco integration to public package exports while preserving its patched Python f-string highlighting.
- **[DeepTutor #753](https://github.com/HKUDS/DeepTutor/pull/753) · Fix editing immediately after save** — uses the newly persisted message snapshot so a stale React state value cannot break the first edit.
- **[DeepTutor #756](https://github.com/HKUDS/DeepTutor/pull/756) · Give research read-only access to Obsidian** — lets the research pipeline search, read, and list trusted vault content without mounting an unavailable RAG index.
- **[OmniRoute #9218](https://github.com/diegosouzapw/OmniRoute/pull/9218) · Keep hidden models out of the picker** — filters operator-hidden models across system, fallback, alias, custom, and live-fetched sources.
- **[WorldMonitor #6088](https://github.com/koala73/worldmonitor/pull/6088) · Preserve collector timeouts on older runtimes** — keeps the 20-second deadline and caller cancellation working when modern `AbortSignal` helpers are unavailable.
- **[Hermes Agent #77522](https://github.com/NousResearch/hermes-agent/pull/77522) · Reduce repeated subscription lookups** — reuses one feature snapshot per toolset-list request; both commits from [#76072](https://github.com/NousResearch/hermes-agent/pull/76072) were cherry-picked unchanged with authorship preserved.

**Active reviews**

- **Hermes CN:** [Prevent Desktop runtime downgrades #540](https://github.com/Eynzof/Hermes-CN-Desktop/pull/540) · [Handle locked runtime files on Windows #544](https://github.com/Eynzof/Hermes-CN-Desktop/pull/544) · [Run cron Python scripts in the frozen runtime #134](https://github.com/Eynzof/Hermes-CN-Core/pull/134)
- **Hermes Agent:** [Apply provider hooks to the Anthropic transport #75480](https://github.com/NousResearch/hermes-agent/pull/75480) · [Stabilize Bedrock Mantle multi-turn sessions #75561](https://github.com/NousResearch/hermes-agent/pull/75561) · [Persist Desktop message reaction settings #77302](https://github.com/NousResearch/hermes-agent/pull/77302) · [Prevent false Windows updater blockers #78094](https://github.com/NousResearch/hermes-agent/pull/78094) · [Patch npm security vulnerabilities #79184](https://github.com/NousResearch/hermes-agent/pull/79184) · [Fix xAI web-search alias routing #79282](https://github.com/NousResearch/hermes-agent/pull/79282)

## Selected Work · 代表作品

### 01 / [WebhookOps Reliability Console](https://github.com/szzhoujiarui/webhookops-reliability-console)

A runnable FastAPI and React demo that verifies signed webhooks, rejects duplicate events, retries failures, moves exhausted events to a dead-letter state, and supports manual replay with a complete audit history.

`Python` · `FastAPI` · `React` · `SQLite` · `Docker`

### 02 / [Python Data Orchestration Lab](https://github.com/szzhoujiarui/python-data-orchestration-lab)

Collects business data through provider adapters, converts it to one validated record model, deduplicates and merges matching companies, then saves to SQLite or exports to CSV and Google Sheets. The offline sample runs without external credentials.

`Python` · `Pydantic` · `SQLite` · `pandas` · `pytest`

### 03 / [Lead Operations Automation](https://github.com/szzhoujiarui/lead-ops-automation)

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
