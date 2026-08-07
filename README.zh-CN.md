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

持续参与 AI Agent、Provider 集成、运行时可靠性、数据分析与 TypeScript 平台工具相关的开源协作。

**已合入上游**

- **[Apache Airflow #70937](https://github.com/apache/airflow/pull/70937) · Monaco Editor 0.56 兼容性** — 恢复 Airflow Monaco 集成对新版公共导出的兼容。
- **[DeepTutor #753](https://github.com/HKUDS/DeepTutor/pull/753) · 乐观编辑刷新可靠性** — 修复文档编辑后的陈旧刷新竞态。
- **[DeepTutor #756](https://github.com/HKUDS/DeepTutor/pull/756) · 只读 Obsidian Research 工具** — 将安全的 Vault 检索工具接入 Research Pipeline。
- **[OmniRoute #9218](https://github.com/diegosouzapw/OmniRoute/pull/9218) · 模型可见性一致性** — 在目录、别名与实时获取路径中统一过滤隐藏模型。
- **[WorldMonitor #6088](https://github.com/koala73/worldmonitor/pull/6088) · Collector 超时韧性** — 在运行时 fallback 中保持 timeout 与 cancellation 语义。
- **[Hermes Agent #77522](https://github.com/NousResearch/hermes-agent/pull/77522) · 工具集列表性能** — 包含 [#76072](https://github.com/NousResearch/hermes-agent/pull/76072) 的两个提交，由维护者原样 cherry-pick 并完整保留作者署名。

**评审中**

- **Hermes CN：** [Desktop Runtime 防降级 #540](https://github.com/Eynzof/Hermes-CN-Desktop/pull/540) · [Windows Runtime 文件占用 #544](https://github.com/Eynzof/Hermes-CN-Desktop/pull/544) · [冻结 Runtime 执行 Cron #134](https://github.com/Eynzof/Hermes-CN-Core/pull/134)
- **Hermes Agent：** [Anthropic Transport #75480](https://github.com/NousResearch/hermes-agent/pull/75480) · [Bedrock Mantle 会话 #75561](https://github.com/NousResearch/hermes-agent/pull/75561) · [Desktop Reactions 配置 #77302](https://github.com/NousResearch/hermes-agent/pull/77302) · [Windows Updater Preflight #78094](https://github.com/NousResearch/hermes-agent/pull/78094) · [npm Audit 修复 #79184](https://github.com/NousResearch/hermes-agent/pull/79184) · [xAI Search 路由 #79282](https://github.com/NousResearch/hermes-agent/pull/79282)

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
