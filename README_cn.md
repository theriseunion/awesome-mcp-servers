**[English](https://github.com/theriseunion/awesome-mcp-servers/blob/main/README.md)** | **中文**

# 面向开发者的 MCP 服务器

## 介绍
本文件分类整理了各类 Model Context Protocol（MCP）服务器，帮助开发者将 AI 模型无缝集成至数据库、文件系统、API、云服务及自动化工具等各类资源。

## 分类

### 1. **文件系统** 📂
提供对本地及远程文件系统的访问，支持权限配置：
- [Backup Server](https://github.com/hexitex/MCP-Backup-Server) - 提供文件及文件夹的备份与恢复功能，适用于 AI 代理及代码编辑工具。
- [FileSystem](https://github.com/modelcontextprotocol/servers/tree/main/src/filesystem) - 允许 AI 直接访问本地文件系统，支持文件读写及管理，并提供可配置的访问权限。
- [Everything Search](https://github.com/mamertofabian/mcp-everything-search) - 基于 Everything SDK 的高效文件搜索 MCP 服务器，适用于 Windows 快速索引与检索。
- [llm-context](https://github.com/cyberchitta/llm-context.py) - 通过 MCP 或剪贴板集成，为 LLM 提供本地代码上下文。

### 2. **版本控制** 🔄
支持与 Git 及其他版本控制系统集成：
- [GitHub](https://github.com/modelcontextprotocol/servers/tree/main/src/github) - 提供 GitHub 仓库集成，支持浏览、Issue 追踪及 Pull Request 管理。
- [GitLab](https://github.com/modelcontextprotocol/servers/tree/main/src/gitlab) - 提供 GitLab 仓库管理、CI/CD 操作及协作支持。
- [Git](https://github.com/modelcontextprotocol/servers/tree/main/src/git) - 允许直接操作本地 Git 仓库，支持提交读取、历史搜索及分支管理。
- [Phabricator](https://github.com/baba786/phabricator-mcp-server) - 支持 Phabricator 代码审查、项目跟踪及仓库管理。

### 3. **数据库** 🗄️
提供安全的数据库访问及查询能力：
- [PostgreSQL](https://github.com/modelcontextprotocol/servers/tree/main/src/postgres) - 支持 PostgreSQL 数据库访问，提供模式检索、SQL 查询及数据分析功能。
- [SQLite](https://github.com/modelcontextprotocol/servers/tree/main/src/sqlite) - 轻量级数据库操作支持，适用于本地数据存储。
- [MongoDB](https://github.com/kiliczsh/mcp-mongo-server) - 提供 MongoDB 查询及 NoSQL 数据分析能力。
- [MySQL](https://github.com/designcomputer/mysql_mcp_server) - 允许与 MySQL 数据库交互，支持可配置的读写访问。
- [BigQuery](https://github.com/LucasHild/mcp-server-bigquery) - 提供对 Google BigQuery 的访问，支持 SQL 查询及数据聚合。
- [Qdrant](https://github.com/qdrant/mcp-server-qdrant/) - 矢量数据库 MCP 服务器，支持语义搜索及嵌入数据存储。

### 4. **云存储** ☁️
支持主流云存储解决方案：
- [Google Drive](https://github.com/modelcontextprotocol/servers/tree/main/src/gdrive) - 允许 AI 访问 Google Drive 文件，支持搜索、上传及组织管理。

### 5. **AI 服务** 🤝
集成 AI 模型相关的服务：
- [OpenAI](https://github.com/pierrebrunelle/mcp-server-openai) - 连接 OpenAI API，支持文本生成及嵌入查询。
- [LlamaCloud](https://github.com/run-llama/mcp-server-llamacloud) - 接入 LlamaCloud 托管 LLM 服务。
- [HuggingFace Spaces](https://github.com/evalstate/mcp-hfspace) - 允许 AI 访问 HuggingFace Spaces，支持模型、数据集及应用托管。
- [ReActMCP](https://github.com/mshojaei77/ReActMCP) - 实现 ReAct（Reasoning + Acting）框架，使 AI 具备推理和决策能力，提升自主性。

### 6. **系统自动化** 🤖
提供系统级别的自动化能力：
- [Shell](https://github.com/rusiaaman/wcgw) - 允许 AI 通过命令行执行自动化操作。
- [Windows CLI](https://github.com/SimonB97/win-cli-mcp-server) - 支持 AI 远程执行 Windows PowerShell、CMD 及 Git Bash 命令。
- [Apple Shortcuts](https://github.com/recursechat/mcp-server-apple-shortcuts) - 通过 Apple Shortcuts 实现 macOS 端的自动化工作流。

### 7. **开发工具** 💻
优化开发者的工作流：
- [Figma](https://github.com/GLips/Figma-Context-MCP) - 允许 AI 解析 Figma 设计文件，辅助代码生成及 UI 实现。
- [VSCode Devtools](https://github.com/biegehydra/BifrostMCP) - 提供 VSCode 集成，支持 AI 代码分析及优化建议。
- [Postman](https://github.com/delano/postman-mcp-server) - 允许 AI 进行 API 测试及请求管理。
- [Chrome Network Analyzer](https://github.com/weetime/chrome-network-analyzer) - 监控 Chrome 网络请求，辅助 API 调试。

### 8. **监控与分析** 📈
支持应用及系统性能监控：
- [Sentry](https://github.com/modelcontextprotocol/servers/tree/main/src/sentry) - 监测应用错误及性能问题，提供 AI 诊断支持。
- [Raygun](https://github.com/MindscapeHQ/mcp-server-raygun) - 集成 Raygun 实时用户监控，追踪崩溃及异常。
- [Grafana](https://github.com/grafana/mcp-grafana) - 连接 Grafana，支持查询及可视化系统指标。
- [Prometheus MCP Server](https://github.com/weetime/prometheus-mcp-server) - 基于 Prometheus 监控，支持 AI 识别系统指标、日志及告警信息。

### 9. **搜索与网络** 🔍
提供 Web 爬取及搜索引擎集成：
- [Puppeteer](https://github.com/modelcontextprotocol/servers/tree/main/src/puppeteer) - 通过 Puppeteer 自动化网页浏览，支持数据抓取。
- [Google News](https://github.com/ChanMeng666/server-google-news) - 提供 AI 新闻搜索及主题分类功能。
- [ArXiv](https://github.com/blazickjp/arxiv-mcp-server) - 允许 AI 访问 ArXiv 论文库，支持研究资料检索。

### 10. **工作流自动化** ⚙️
实现业务流程自动化：
- [Make](https://github.com/integromat/make-mcp-server) - 连接 Make.com，支持 AI 驱动的自动化任务管理。

## 结论
本文对 MCP 服务器进行了分类整理，帮助开发者根据需求选择最适合的集成方案。每个类别都涵盖了多个 MCP 服务器，以满足开发、测试、DevOps 及 AI 相关应用的需求。
