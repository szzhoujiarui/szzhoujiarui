<p align="right">
  <a href="./README.md">English</a> &nbsp;|&nbsp; <strong>简体中文</strong>
</p>

<p align="center">
  <img src="./assets/profile-header.svg?v=20260801-3" width="1280" alt="Zhou J. - Python 自动化、数据系统与集成" />
</p>

<p align="center">
  <strong>为杂乱数据、脆弱集成与运营复杂度构建可靠系统。</strong><br />
  <sub>Python 工程 · 可观测工作流 · 开源协作</sub>
</p>

## 开源协作 · Open Source

持续参与 [NousResearch/hermes-agent](https://github.com/NousResearch/hermes-agent)，贡献方向涵盖 Provider 集成、Agent 运行稳定性与工具集性能。

- **[#76072](https://github.com/NousResearch/hermes-agent/pull/76072) · 工具集列表性能**<br />
  在相邻 API 路径间复用请求级 subscription snapshot。`审核中`
- **[#75561](https://github.com/NousResearch/hermes-agent/pull/75561) · Bedrock Mantle 会话稳定性**<br />
  提升跨 Provider 多轮工具会话的稳定性。`审核中`
- **[#75480](https://github.com/NousResearch/hermes-agent/pull/75480) · Anthropic Transport 集成**<br />
  将 ProviderProfile hooks 接入 transport 生命周期。`审核中`

## 代表作品 · Selected Work

### 01 / [WebhookOps 可靠性控制台](https://github.com/szzhoujiarui/webhookops-reliability-console)

基于 FastAPI 与 React，实现原始字节 HMAC 验证、幂等交付、重试、死信处理、人工重放与审计追踪。

`Python` · `FastAPI` · `React` · `PostgreSQL` · `Docker`

### 02 / [Python 数据编排实验室](https://github.com/szzhoujiarui/python-data-orchestration-lab)

包含基于 Schema 的标准化、多键去重、记录合并、SQLite Upsert、结构化导出与自动化测试。

`Python` · `Pydantic` · `SQLite` · `pandas` · `pytest`

### 03 / [销售线索运营自动化](https://github.com/szzhoujiarui/lead-ops-automation)

使用持久化任务状态、租约、Fencing、可重试与终止失败路径、人工重放，并提供 Playwright 验收证据。

`n8n` · `PostgreSQL` · `Docker Compose` · `Playwright`

**作品归档：** [技术图纸矢量化](https://github.com/szzhoujiarui/opencv-technical-drawing-vectorizer) · [Deskflow Studio](https://github.com/szzhoujiarui/deskflow-studio) · [Excel 自动化](https://github.com/szzhoujiarui/xlsm-demo) · [WordPress 报价管理器](https://github.com/szzhoujiarui/wp-service-quote-manager)

## 工程方法 · Engineering Practice

- 实施前明确输入、输出、约束与验收标准。
- 让外部集成保持可替换，让失败状态可观察、可恢复。
- 交付验证命令、自动化测试、假设条件与真实实现边界。

<p align="center">
  <sub>中国开发者 / OPEN-SOURCE CONTRIBUTOR / ZHOU J.</sub>
</p>
