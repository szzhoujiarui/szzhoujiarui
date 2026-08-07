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

## 开源协作 · Open Source

主要参与 AI Agent、模型服务接入、跨平台 Runtime、数据分析与 TypeScript 工具链等方向的开源项目。

**已合入上游**

- **[Apache Airflow #70937](https://github.com/apache/airflow/pull/70937) · 适配 Monaco Editor 0.56** — 改用新版公开接口，同时保留 Airflow 对 Python f-string 语法高亮的支持。
- **[DeepTutor #753](https://github.com/HKUDS/DeepTutor/pull/753) · 修复文档保存后首次编辑失败** — 页面刷新后直接使用最新保存结果，避免旧状态影响第一次编辑。
- **[DeepTutor #756](https://github.com/HKUDS/DeepTutor/pull/756) · 让研究流程直接读取 Obsidian 知识库** — 提供受限的搜索、笔记读取和目录浏览能力，无需依赖尚未建立的 RAG 索引。
- **[OmniRoute #9218](https://github.com/diegosouzapw/OmniRoute/pull/9218) · 隐藏模型不再出现在模型选择器中** — 统一过滤系统、备用、别名、自定义和实时获取的模型。
- **[WorldMonitor #6088](https://github.com/koala73/worldmonitor/pull/6088) · 修复旧版运行环境中的采集请求超时** — 确保 20 秒超时和用户取消在缺少新版 `AbortSignal` 接口时仍然生效。
- **[Hermes Agent #77522](https://github.com/NousResearch/hermes-agent/pull/77522) · 减少工具列表的重复状态查询** — 每次列表请求只读取一次订阅状态；[#76072](https://github.com/NousResearch/hermes-agent/pull/76072) 的两个提交由维护者原样合入并保留作者署名。

**评审中**

- **Hermes CN：** [防止桌面端安装包覆盖较新的 Runtime #540](https://github.com/Eynzof/Hermes-CN-Desktop/pull/540) · [修复 Windows 更新时 Runtime 文件被占用 #544](https://github.com/Eynzof/Hermes-CN-Desktop/pull/544) · [修复冻结 Runtime 无法执行定时 Python 脚本 #134](https://github.com/Eynzof/Hermes-CN-Core/pull/134)
- **Hermes Agent：** [让 Anthropic 兼容接口正确应用模型服务配置 #75480](https://github.com/NousResearch/hermes-agent/pull/75480) · [修复 Bedrock Mantle 多轮工具调用冲突 #75561](https://github.com/NousResearch/hermes-agent/pull/75561) · [保存 Desktop 消息反应设置 #77302](https://github.com/NousResearch/hermes-agent/pull/77302) · [修复 Windows 更新程序误报 Runtime 正在使用 #78094](https://github.com/NousResearch/hermes-agent/pull/78094) · [修复 npm 高危依赖漏洞 #79184](https://github.com/NousResearch/hermes-agent/pull/79184) · [修复 xAI 搜索工具路由冲突 #79282](https://github.com/NousResearch/hermes-agent/pull/79282)

## 项目案例 · Selected Work

### 01 / [WebhookOps Reliability Console](https://github.com/szzhoujiarui/webhookops-reliability-console)

一个可以直接运行的 Webhook 处理演示。系统会验证请求签名、拦截重复事件，并在处理失败时自动重试；多次失败的事件会进入待处理状态，用户可以在控制台查看完整记录并手动重放。

`Python` · `FastAPI` · `React` · `SQLite` · `Docker`

### 02 / [Python Data Orchestration Lab](https://github.com/szzhoujiarui/python-data-orchestration-lab)

将 Google Places 等不同来源的企业数据整理成统一格式，自动完成校验、去重和记录合并，再保存到 SQLite 或导出为 CSV、Google Sheets。项目提供无需外部账号即可运行的离线样例。

`Python` · `Pydantic` · `SQLite` · `pandas` · `pytest`

### 03 / [Lead Ops Automation](https://github.com/szzhoujiarui/lead-ops-automation)

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
