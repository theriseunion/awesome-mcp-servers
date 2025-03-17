**English** | [中文](https://github.com/theriseunion/awesome-mcp-servers/blob/main/README_cn.md)

# MCP Servers for Developers

## Introduction
This document categorizes and organizes various Model Context Protocol (MCP) servers to assist developers in integrating AI models with various resources such as databases, file systems, APIs, cloud services, and automation tools.

## Categories

### 1. **File Systems** 📂
Provides access to local and remote file systems with configurable permissions.
- [Backup Server](https://github.com/hexitex/MCP-Backup-Server) - Provides file and folder backup and restoration capabilities for AI agents and code editing tools.
- [FileSystem](https://github.com/modelcontextprotocol/servers/tree/main/src/filesystem) - Enables direct access to the local file system with configurable permissions for reading, writing, and managing files.
- [Everything Search](https://github.com/mamertofabian/mcp-everything-search) - A high-speed file search MCP server utilizing the Everything SDK for fast indexing and retrieval on Windows.
- [llm-context](https://github.com/cyberchitta/llm-context.py) - Provides a way to share local code context with LLMs via Model Context Protocol or clipboard integration.

### 2. **Version Control** 🔄
Enables interaction with Git and other version control systems.
- [GitHub](https://github.com/modelcontextprotocol/servers/tree/main/src/github) - Allows integration with GitHub repositories, enabling features like repository browsing, issue tracking, and pull request management.
- [GitLab](https://github.com/modelcontextprotocol/servers/tree/main/src/gitlab) - Provides GitLab integration for project and repository management, CI/CD operations, and collaboration.
- [Git](https://github.com/modelcontextprotocol/servers/tree/main/src/git) - A server enabling direct interaction with local Git repositories, allowing operations like reading commits, searching history, and branch management.
- [Phabricator](https://github.com/baba786/phabricator-mcp-server) - Enables interaction with Phabricator for repository management, code review, and project tracking.

### 3. **Databases** 🗄️
Secure access to various databases with query capabilities.
- [PostgreSQL](https://github.com/modelcontextprotocol/servers/tree/main/src/postgres) - Provides secure access to PostgreSQL databases, supporting schema inspection, SQL queries, and data analysis.
- [SQLite](https://github.com/modelcontextprotocol/servers/tree/main/src/sqlite) - Enables lightweight and efficient SQLite database operations, useful for local data storage.
- [MongoDB](https://github.com/kiliczsh/mcp-mongo-server) - A MongoDB MCP server allowing AI models to query and analyze document-based NoSQL databases.
- [MySQL](https://github.com/designcomputer/mysql_mcp_server) - Facilitates integration with MySQL databases, supporting read and write operations with configurable security policies.
- [BigQuery](https://github.com/LucasHild/mcp-server-bigquery) - Allows interaction with Google BigQuery, supporting schema exploration, SQL queries, and data aggregation.
- [Qdrant](https://github.com/qdrant/mcp-server-qdrant/) - A vector database MCP server that enables semantic search, embeddings storage, and retrieval in AI applications.

### 4. **Cloud Storage** ☁️
Manages cloud storage solutions.
- [Google Drive](https://github.com/modelcontextprotocol/servers/tree/main/src/gdrive) - Enables AI models to access and manage files stored on Google Drive, supporting search, upload, and organization features.

### 5. **AI Services** 🤝
Provides AI model-related services and integrations.
- [OpenAI](https://github.com/pierrebrunelle/mcp-server-openai) - Integrates with OpenAI’s API, enabling AI models to query and retrieve text completions and embeddings.
- [LlamaCloud](https://github.com/run-llama/mcp-server-llamacloud) - Connects to LlamaCloud’s managed LLM service for enhanced AI interactions.
- [HuggingFace Spaces](https://github.com/evalstate/mcp-hfspace) - Allows AI models to interact with HuggingFace Spaces, supporting hosted models, datasets, and applications.
- [ReActMCP](https://github.com/mshojaei77/ReActMCP) - Implements the **ReAct framework** (Reasoning + Acting) to enable AI agents to make informed decisions and take actions based on contextual information. It enhances AI autonomy by combining logical reasoning with real-world interactions.

### 6. **System Automation** 🤖
Automates system and shell-level interactions.
- [Shell](https://github.com/rusiaaman/wcgw) - Provides autonomous shell execution and command-line control for system operations.
- [Windows CLI](https://github.com/SimonB97/win-cli-mcp-server) - Enables AI-driven command-line interactions on Windows systems, supporting secure execution of PowerShell, CMD, and Git Bash commands.
- [Apple Shortcuts](https://github.com/recursechat/mcp-server-apple-shortcuts) - Integrates with Apple Shortcuts to automate workflows and trigger predefined actions on macOS.

### 7. **Development Tools** 💻
Enhances developer workflows.
- [Figma](https://github.com/GLips/Figma-Context-MCP) - Allows AI models to extract design information from Figma projects, enabling code generation and UI implementation.
- [VSCode Devtools](https://github.com/biegehydra/BifrostMCP) - Provides integration with VSCode, allowing AI-driven code analysis and editing suggestions.
- [Postman](https://github.com/delano/postman-mcp-server) - Enables API testing and request management via Postman’s API service.
- [Chrome Network Analyzer](https://github.com/weetime/chrome-network-analyzer) - Captures and analyzes Chrome browser network activity, helping developers debug API requests and web interactions with AI-driven insights.

### 8. **Monitoring** 📈
Tracks application and system performance.
- [Sentry](https://github.com/modelcontextprotocol/servers/tree/main/src/sentry) - Monitors application errors, exceptions, and performance issues, providing AI-driven debugging insights.
- [Raygun](https://github.com/MindscapeHQ/mcp-server-raygun) - Integrates Raygun’s real user monitoring to track crashes, exceptions, and performance bottlenecks.
- [Grafana](https://github.com/grafana/mcp-grafana) - Connects with Grafana to query and visualize system metrics.
- [Prometheus MCP Server](https://github.com/weetime/prometheus-mcp-server) - Provides **Prometheus-based monitoring** capabilities, allowing AI models to query and analyze system metrics, logs, and alert conditions to detect performance anomalies.

### 9. **Search & Web** 🔍
Web scraping and search engine integration.
- [Puppeteer](https://github.com/modelcontextprotocol/servers/tree/main/src/puppeteer) - Automates browser interactions for web scraping and content extraction.
- [Google News](https://github.com/ChanMeng666/server-google-news) - Searches and retrieves news articles with AI-driven topic categorization.
- [ArXiv](https://github.com/blazickjp/arxiv-mcp-server) - Provides AI models with access to academic papers and research materials.

### 10. **Workflow Automation** ⚙️
Automates workflows and business processes.
- [Make](https://github.com/integromat/make-mcp-server) - Integrates AI-driven automation with Make.com to streamline repetitive tasks.

## Conclusion
This list provides a categorized view of MCP servers useful for developers. Each category groups similar functionalities to help developers find the best MCP server for their integration needs.

