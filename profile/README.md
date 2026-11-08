<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/ai-v5/.github/main/profile/assets/banner-dark.svg">
  <img src="https://raw.githubusercontent.com/ai-v5/.github/main/profile/assets/banner-light.svg" alt="AI V5 — 大模型工程 · 性能剖析 · 部署 · Agent 工具链">
</picture>

<br>

**把大模型真正跑起来、跑得更快、用得更顺手。**

<sub>Open-source tooling for LLM performance engineering, deployment and agent workflows.</sub>

<br>

<a href="https://ai-v5.github.io/"><img src="https://img.shields.io/badge/website-ai--v5.github.io-3176de?style=flat-square&logo=githubpages&logoColor=white" alt="website"></a> <a href="https://awesome-dsh-plugin.com"><img src="https://img.shields.io/badge/dsh%20plugins-awesome--dsh--plugin-213e68?style=flat-square" alt="dsh plugins"></a> <a href="https://github.com/ai-v5/keyless-web-mcp"><img src="https://img.shields.io/badge/MCP-ready-477dbb?style=flat-square" alt="MCP"></a> <a href="https://github.com/orgs/ai-v5/repositories"><img src="https://img.shields.io/badge/repos-14-8795a6?style=flat-square" alt="repos"></a>

</div>

---

## 精选项目

**[LLMInsight](https://github.com/ai-v5/LLMInsight)** &nbsp; ![stars](https://img.shields.io/github/stars/ai-v5/LLMInsight?style=flat-square&label=%E2%98%85&color=213e68) ![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) ![AGPL-3.0](https://img.shields.io/badge/license-AGPL--3.0-213e68?style=flat-square)

面向大模型训练 / 推理的性能剖析与分析平台：从真实运行的 timeline / trace、算子 kernel、HCCL / NCCL 通信与显存指标中定位瓶颈、归因热点、对比多次运行。

**[keyless-web-mcp](https://github.com/ai-v5/keyless-web-mcp)** &nbsp; ![stars](https://img.shields.io/github/stars/ai-v5/keyless-web-mcp?style=flat-square&label=%E2%98%85&color=213e68) ![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) ![MIT](https://img.shields.io/badge/license-MIT-3176de?style=flat-square)

免 API key、免账号的联网检索与正文抓取：无头浏览器读 Google，多引擎并发汇总，可直接替换 DSH 的 `web_search` / `web_fetch`。

**[dsh-plugin-aside](https://github.com/ai-v5/dsh-plugin-aside)** &nbsp; ![stars](https://img.shields.io/github/stars/ai-v5/dsh-plugin-aside?style=flat-square&label=%E2%98%85&color=213e68) ![JavaScript](https://img.shields.io/badge/JavaScript-F1E05A?style=flat-square&logo=javascript&logoColor=black) ![AGPL-3.0](https://img.shields.io/badge/license-AGPL--3.0-213e68?style=flat-square)

旁白（Aside）：把当前对话 fork 到右侧边栏，自己的模型与工具，主线程完全不受影响，刷新或重启后仍在。

**[LLMDeploy](https://github.com/ai-v5/LLMDeploy)** &nbsp; ![stars](https://img.shields.io/github/stars/ai-v5/LLMDeploy?style=flat-square&label=%E2%98%85&color=213e68) ![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) ![AGPL-3.0](https://img.shields.io/badge/license-AGPL--3.0-213e68?style=flat-square)

LLM 部署配方、配置与迁移笔记，配套可检索的文档站。

**[LLMDSHPlugin_token-usage](https://github.com/ai-v5/LLMDSHPlugin_token-usage)** &nbsp; ![stars](https://img.shields.io/github/stars/ai-v5/LLMDSHPlugin_token-usage?style=flat-square&label=%E2%98%85&color=213e68) ![JavaScript](https://img.shields.io/badge/JavaScript-F1E05A?style=flat-square&logo=javascript&logoColor=black) ![MIT](https://img.shields.io/badge/license-MIT-3176de?style=flat-square)

仅本地、只读、不上传的 DSH Token 面板：历史总量、365 天热力图、输入 / 输出与缓存明细、轮次与 tok/s。

**[LLMMarkUp](https://github.com/ai-v5/LLMMarkUp)** &nbsp; ![stars](https://img.shields.io/github/stars/ai-v5/LLMMarkUp?style=flat-square&label=%E2%98%85&color=213e68) ![JavaScript](https://img.shields.io/badge/JavaScript-F1E05A?style=flat-square&logo=javascript&logoColor=black) ![AGPL-3.0](https://img.shields.io/badge/license-AGPL--3.0-213e68?style=flat-square)

简洁顺手的 Windows Markdown 编辑器：文件树、多标签、实时预览与 LaTeX 公式。

---

## 按能力线

### 大模型工程与性能

- **[LLMInsight](https://github.com/ai-v5/LLMInsight)** · 训练 / 推理性能剖析与瓶颈归因平台
- **[LLMDeploy](https://github.com/ai-v5/LLMDeploy)** · 部署配方、配置与迁移笔记
- **[deepinfer_ascend](https://github.com/ai-v5/deepinfer_ascend)** · DeepSeek 模型的大规模高性能推理框架 · `Apache-2.0`

### DeepSeek Harness 插件

- **[dsh-plugin-aside](https://github.com/ai-v5/dsh-plugin-aside)** · 侧边栏 fork 旁聊，主线程不受影响
- **[LLMDSHPlugin_token-usage](https://github.com/ai-v5/LLMDSHPlugin_token-usage)** · 本地 Token 用量面板与 365 天热力图
- **[LLMAgentChatRoom](https://github.com/ai-v5/LLMAgentChatRoom)** · 本地多 Agent 聊天室
- **[awesome-dsh-plugin](https://github.com/ai-v5/awesome-dsh-plugin)** · 插件精选索引，可直接填入插件市场的索引源

### MCP 与联网检索

- **[keyless-web-mcp](https://github.com/ai-v5/keyless-web-mcp)** · 免 key 的搜索与正文抓取，多引擎汇总
- **[LLMMcp](https://github.com/ai-v5/LLMMcp)** · 走企业代理的 Google 搜索与网页抓取 MCP server

### 本地效率与评测

- **[LLMMarkUp](https://github.com/ai-v5/LLMMarkUp)** · Windows Markdown 编辑器
- **[LLMLocalSearch](https://github.com/ai-v5/LLMLocalSearch)** · Windows 离线文件搜索，Rust 实现
- **[LLMAgentBench](https://github.com/ai-v5/LLMAgentBench)** · 面向工程 AI agent 的可复现、代码优先评测
- **[LLMNews](https://github.com/ai-v5/LLMNews)** · AI 信号、资讯与分析

---

## 入口

- 🧭 **项目导航** — [ai-v5.github.io](https://ai-v5.github.io/)，按场景浏览全部项目与插件说明
- 🛒 **插件市场索引** — [market/index.json](https://ai-v5.github.io/market/index.json)，在 DSH「插件 → 发现 → 索引源」填入即可安装
- 🧰 **部署文档** — [ai-v5.github.io/LLMDeploy](https://ai-v5.github.io/LLMDeploy/)

<div align="center">
<sub>各项目许可证以对应仓库为准；工具默认本地优先，不上传任何运行数据。</sub>
</div>
