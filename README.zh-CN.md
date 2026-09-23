<p align="right">
  <a href="./README.md">English</a> &nbsp;|&nbsp; <strong>简体中文</strong>
</p>

<p align="center">
  <img src="./assets/profile-header.svg?v=20260801-3" width="1280" alt="Zhou J. - Python 数据工作流、AI Agent 与自动化系统" />
</p>

<p align="center">
  <strong>专注于用 Python 构建可靠的数据工作流、AI Agent 基础设施和自动化系统。</strong><br />
  <sub>Python 工程 · AI Agent 基础设施 · 可追踪的自动化流程</sub>
</p>

<p align="center">
  <img src="./assets/capability-strip.svg" width="100%" alt="核心技术栈：数据系统、可靠集成、业务工具" />
</p>

## 开源协作 · Open Source

主要参与 AI Agent 运行时架构、大模型服务接入、跨平台底层性能优化、数据分析与 TypeScript 工具链等方向的开源协作。

### 🌟 已合入上游（Merged Upstream）

- **[Hugging Face PEFT #3546](https://github.com/huggingface/peft/pull/3546) · 为 MetaMathQA 新增 bank-1024 VBLoRA 配置** — 提交可复现的 Llama 3.2 3B 实验配置，通过有边界的参数搜索提升 GSM8K 准确率，并量化记录 adapter 体积增长的权衡。
- **[Apache Airflow #70937](https://github.com/apache/airflow/pull/70937) · 适配 Monaco Editor 0.56** — 改用新版公开导出接口，同时保留 Airflow 对 Python f-string 语法高亮的支持。
- **[DeepTutor #753](https://github.com/HKUDS/DeepTutor/pull/753) · 修复文档保存后首次编辑失败** — 页面刷新后直接使用最新持久化的快照，避免 React 旧状态影响第一次编辑。
- **[DeepTutor #756](https://github.com/HKUDS/DeepTutor/pull/756) · 赋予研究流程对 Obsidian 的只读访问能力** — 提供只读的笔记搜索、文件解析和目录浏览能力，无需挂载不可用的 RAG 索引。
- **[OmniRoute #9218](https://github.com/diegosouzapw/OmniRoute/pull/9218) · 隐藏模型不再出现在模型选择器中** — 统一过滤来自系统配置、备用策略、别名、自定义及实时获取等多渠道的隐藏模型。
- **[WorldMonitor #6088](https://github.com/koala73/worldmonitor/pull/6088) · 修复旧版运行环境中的采集请求超时** — 确保 20 秒超时和调用方取消在缺少新版 `AbortSignal` 接口时仍然生效。
- **[Hermes Agent #77522](https://github.com/NousResearch/hermes-agent/pull/77522) · 减少工具列表的重复状态查询** — 每次列表请求只读取一次订阅状态；[#76072](https://github.com/NousResearch/hermes-agent/pull/76072) 的两个提交由维护者原样合入并保留作者署名。

### 🚀 当前开放贡献（Open Contributions）

- **Hermes Agent：** [合并 Windows 硬件 SMI 轮询消除卡顿 #120285](https://github.com/NousResearch/hermes-agent/pull/120285) · [恢复未完结的桌面 Transcript 轮次 #88127](https://github.com/NousResearch/hermes-agent/pull/88127) · [识别 Slack 机器人 ID 提及 #85885](https://github.com/NousResearch/hermes-agent/pull/85885) · [校验 Webhook 投递目标 #84184](https://github.com/NousResearch/hermes-agent/pull/84184) · [恢复带时间戳的 Curator 归档 #83613](https://github.com/NousResearch/hermes-agent/pull/83613) · [修复 xAI 搜索工具路由冲突 #79282](https://github.com/NousResearch/hermes-agent/pull/79282) · [保存 Desktop 消息反应设置 #77302](https://github.com/NousResearch/hermes-agent/pull/77302) · [修复 Bedrock Mantle 多轮工具调用冲突 #75561](https://github.com/NousResearch/hermes-agent/pull/75561) · [让 Anthropic 兼容接口正确应用模型服务配置 #75480](https://github.com/NousResearch/hermes-agent/pull/75480)
- **Hermes CN：** [防止桌面端安装包覆盖较新的 Runtime #540](https://github.com/Eynzof/Hermes-CN-Desktop/pull/540) · [修复 Windows 更新时 Runtime 文件被占用 #544](https://github.com/Eynzof/Hermes-CN-Desktop/pull/544) · [修复冻结 Runtime 无法执行定时 Python 脚本 #134](https://github.com/Eynzof/Hermes-CN-Core/pull/134)

### 🔍 精选代码评审（Selected Review Work）

- **Hermes Agent：** [为 Gateway 通道目录初始化设置硬超时边界 #79060](https://github.com/NousResearch/hermes-agent/pull/79060) · [评审 Cron 定时重复生命周期校验 #82495](https://github.com/NousResearch/hermes-agent/pull/82495) · [评审二进制文件检测正确性 #82494](https://github.com/NousResearch/hermes-agent/pull/82494)

## 代表作品 · Selected Work

### 01 / [Portfolio Decision Workbench](https://github.com/szzhoujiarui/portfolio-decision-workbench)

一个可复现的 Python 后端工程案例，覆盖高韧性行情数据采集、数据源健康隔离、数据溯源追踪、数据质量审计和契约优先的 FastAPI 接口。项目提供无需实时行情和凭据的离线演示、固定 fixture、SQLite 持久化、OpenAPI 契约校验，以及从 legacy Flask 路由向模块化服务迁移的完整路径。

`Python` · `FastAPI` · `SQLite` · `Pydantic` · `pytest`

### 02 / [WebhookOps Reliability Console](https://github.com/szzhoujiarui/webhookops-reliability-console)

<p align="center">
  <img src="./assets/evidence-webhookops.svg" width="100%" alt="WebhookOps Reliability Console 架构示意" />
</p>

一个可以直接运行的 Webhook 处理演示。系统会验证请求签名、拦截重复事件，并在处理失败时自动重试；多次重试耗尽的事件会转入死信状态 (dead-letter)，用户可在控制台查看完整审计记录并手动重放。

`Python` · `FastAPI` · `React` · `SQLite` · `Docker`

### 03 / [Python Data Orchestration Lab](https://github.com/szzhoujiarui/python-data-orchestration-lab)

<p align="center">
  <img src="./assets/evidence-data-orchestration.svg" width="100%" alt="Python Data Orchestration Lab 数据流水线" />
</p>

通过适配器采集 Google Places 等多源企业数据，统一转换为经过校验的标准数据模型，自动完成跨源去重与记录合并，支持持久化至 SQLite 或导出为 CSV、Google Sheets。提供无需外部凭据即可运行的离线样例。

`Python` · `Pydantic` · `SQLite` · `pandas` · `pytest`

### 04 / [Lead Operations Automation](https://github.com/szzhoujiarui/lead-ops-automation)

<p align="center">
  <img src="./assets/evidence-lead-ops.svg" width="100%" alt="Lead Operations Automation 工作流示意" />
</p>

通过 n8n 自动校验、去重、评分和分流销售线索，再将处理结果发送到兼容 HubSpot 和 Slack 的接口。任务状态保存在 PostgreSQL 中，失败后支持自动重试和人工重放，并通过 25 项 Playwright 测试验证完整流程。

`n8n` · `PostgreSQL` · `Docker Compose` · `Playwright`

**其他项目：** [技术图纸矢量化](https://github.com/szzhoujiarui/opencv-technical-drawing-vectorizer) · [Deskflow Studio](https://github.com/szzhoujiarui/deskflow-studio) · [Excel 自动化](https://github.com/szzhoujiarui/xlsm-demo) · [WordPress 报价管理器](https://github.com/szzhoujiarui/wp-service-quote-manager)

## 工程方法 · Engineering Practice

- 开始开发前，先明确输入、输出、约束和验收标准。
- 外部服务通过清晰接口接入，便于替换、测试和故障恢复。
- 交付内容包括可复现的验证命令、自动化测试，以及明确的实现范围和限制。

<p align="center">
  <sub>中国开发者 / OPEN-SOURCE CONTRIBUTOR / ZHOU J.</sub>
</p>
