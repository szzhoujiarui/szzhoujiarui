<p align="right">
  <a href="./README.md">English</a> &nbsp;|&nbsp; <strong>简体中文</strong>
</p>

<p align="center">
  <img src="./assets/profile-header.svg?v=20260801-3" width="1280" alt="Zhou J. - 可靠 Python 系统、AI Agent 基础设施与数据工作流" />
</p>

<p align="center">
  <strong>为杂乱数据、脆弱集成与运营复杂度构建可靠系统。</strong><br />
  <sub>Python 工程 · AI Agent 基础设施 · 可观测工作流</sub>
</p>

## 开源协作 · Open Source

持续参与 AI Agent、Provider 集成、运行时可靠性与 TypeScript 平台工具相关的开源协作。

- **[#77522](https://github.com/NousResearch/hermes-agent/pull/77522) · Hermes Agent 工具集列表性能**<br />
  消除 Web 与 API 列表路径中重复解析订阅能力的问题。[#76072](https://github.com/NousResearch/hermes-agent/pull/76072) 的两个提交均由维护者原样 cherry-pick，作者署名完整保留。`已合入上游`
- **[#75561](https://github.com/NousResearch/hermes-agent/pull/75561) · Bedrock Mantle 会话稳定性**<br />
  提升跨 Provider 多轮工具会话的稳定性。`开放`
- **[#75480](https://github.com/NousResearch/hermes-agent/pull/75480) · Anthropic Transport 集成**<br />
  将 ProviderProfile hooks 接入 transport 生命周期。`开放`
- **[#9218](https://github.com/diegosouzapw/OmniRoute/pull/9218) · OmniRoute 模型可见性**<br />
  在目录、别名与实时获取路径中统一过滤隐藏模型。`开放`
- **[#756](https://github.com/HKUDS/DeepTutor/pull/756) · DeepTutor Obsidian Research 工具**<br />
  将安全、只读的 Vault 检索能力接入 Research Pipeline。`开放`
- **[#6088](https://github.com/koala73/worldmonitor/pull/6088) · WorldMonitor Collector 韧性**<br />
  在运行时 fallback 中保持 timeout 与 cancellation 语义。`开放`

**近期贡献：** [#78094](https://github.com/NousResearch/hermes-agent/pull/78094) 修复 Windows Updater Preflight 对超长虚拟环境进程命令行的处理。`开放`

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
