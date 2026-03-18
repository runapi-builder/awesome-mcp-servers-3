# Awesome MCP Servers [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](CONTRIBUTING.md)
[![GitHub Stars](https://img.shields.io/github/stars/YOUR_USERNAME/awesome-mcp-servers?style=social)](https://github.com/YOUR_USERNAME/awesome-mcp-servers)

> A curated list of awesome [Model Context Protocol (MCP)](https://modelcontextprotocol.io/) servers — connect your AI to the real world.

MCP is an open protocol created by [Anthropic](https://anthropic.com) that enables AI models (Claude, ChatGPT, Cursor, etc.) to securely interact with external tools, databases, APIs, and services through standardized server implementations.

**[繁體中文版](#繁體中文) | English**

---

## Contents

- [Official Reference Servers](#official-reference-servers)
- [Search & Web](#search--web)
- [Browser Automation](#browser-automation)
- [Databases](#databases)
- [Cloud & Infrastructure](#cloud--infrastructure)
- [Developer Tools](#developer-tools)
- [AI & Knowledge](#ai--knowledge)
- [Productivity & Project Management](#productivity--project-management)
- [Communication](#communication)
- [File & Storage](#file--storage)
- [Finance & Payments](#finance--payments)
- [Data & Analytics](#data--analytics)
- [CMS & Content](#cms--content)
- [Security & Identity](#security--identity)
- [DevOps & Monitoring](#devops--monitoring)
- [Smart Home & IoT](#smart-home--iot)
- [Frameworks & Utilities](#frameworks--utilities)
- [繁體中文](#繁體中文)

---

## Official Reference Servers

> Maintained by the [MCP team](https://github.com/modelcontextprotocol/servers). These are the canonical implementations.

| Name | Description | Install |
|------|-------------|---------|
| [Filesystem](https://github.com/modelcontextprotocol/servers/tree/main/src/filesystem) | Secure file operations with configurable access controls | `npx -y @modelcontextprotocol/server-filesystem /path` |
| [Fetch](https://github.com/modelcontextprotocol/servers/tree/main/src/fetch) | Web content fetching and conversion for efficient LLM usage | `npx -y @modelcontextprotocol/server-fetch` |
| [Git](https://github.com/modelcontextprotocol/servers/tree/main/src/git) | Read, search, and manipulate Git repositories | `uvx mcp-server-git` |
| [Memory](https://github.com/modelcontextprotocol/servers/tree/main/src/memory) | Knowledge graph-based persistent memory system | `npx -y @modelcontextprotocol/server-memory` |
| [Sequential Thinking](https://github.com/modelcontextprotocol/servers/tree/main/src/sequentialthinking) | Dynamic problem-solving through structured thought sequences | `npx -y @modelcontextprotocol/server-sequential-thinking` |
| [Time](https://github.com/modelcontextprotocol/servers/tree/main/src/time) | Time and timezone conversion capabilities | `npx -y @modelcontextprotocol/server-time` |
| [Everything](https://github.com/modelcontextprotocol/servers/tree/main/src/everything) | Reference/test server with prompts, resources, and tools | `npx -y @modelcontextprotocol/server-everything` |

---

## Search & Web

| Name | Description | Install | Link |
|------|-------------|---------|------|
| [Brave Search](https://github.com/brave/brave-search-mcp-server) | Privacy-focused web and local search via Brave Search API | `npx -y @anthropic/brave-search-mcp-server` | [![GitHub](https://img.shields.io/github/stars/brave/brave-search-mcp-server?style=flat-square)](https://github.com/brave/brave-search-mcp-server) |
| [Firecrawl](https://github.com/firecrawl/firecrawl-mcp-server) | Powerful web scraping with JS rendering, batch processing, and search | `npx -y firecrawl-mcp` | [![GitHub](https://img.shields.io/github/stars/firecrawl/firecrawl-mcp-server?style=flat-square)](https://github.com/firecrawl/firecrawl-mcp-server) |
| [Tavily](https://github.com/tavily-ai/tavily-mcp) | AI-optimized search engine for LLMs and RAG applications | `npx -y tavily-mcp@latest` | [![GitHub](https://img.shields.io/github/stars/tavily-ai/tavily-mcp?style=flat-square)](https://github.com/tavily-ai/tavily-mcp) |
| [Exa](https://github.com/exa-labs/exa-mcp-server) | Neural search powered by embeddings for high-quality results | `npx -y exa-mcp-server` | [![GitHub](https://img.shields.io/github/stars/exa-labs/exa-mcp-server?style=flat-square)](https://github.com/exa-labs/exa-mcp-server) |
| [Apify](https://github.com/apify/apify-mcp-server) | Web scraping and data extraction at scale | `npx -y @apify/mcp-server` | [![GitHub](https://img.shields.io/github/stars/apify/apify-mcp-server?style=flat-square)](https://github.com/apify/apify-mcp-server) |
| [AgentQL](https://github.com/tinyfish-io/agentql-mcp) | Structured web data extraction with natural language selectors | `npx -y @agentql/mcp-server` | [![GitHub](https://img.shields.io/github/stars/tinyfish-io/agentql-mcp?style=flat-square)](https://github.com/tinyfish-io/agentql-mcp) |

## Browser Automation

| Name | Description | Install | Link |
|------|-------------|---------|------|
| [Playwright](https://github.com/microsoft/playwright-mcp) | Browser automation via accessibility snapshots (by Microsoft) | `npx -y @playwright/mcp` | [![GitHub](https://img.shields.io/github/stars/microsoft/playwright-mcp?style=flat-square)](https://github.com/microsoft/playwright-mcp) |
| [Browserbase](https://github.com/browserbase/mcp-server-browserbase) | Cloud browser automation with Stagehand AI | `npx -y @browserbasehq/mcp-server` | [![GitHub](https://img.shields.io/github/stars/browserbase/mcp-server-browserbase?style=flat-square)](https://github.com/browserbase/mcp-server-browserbase) |
| [Puppeteer](https://github.com/modelcontextprotocol/servers-archived) | Browser automation with screenshot and PDF support | `npx -y @modelcontextprotocol/server-puppeteer` | — |

## Databases

| Name | Description | Install | Link |
|------|-------------|---------|------|
| [DBHub](https://github.com/bytebase/dbhub) | Zero-dependency server for Postgres, MySQL, SQL Server, MariaDB, SQLite | `npx -y dbhub` | [![GitHub](https://img.shields.io/github/stars/bytebase/dbhub?style=flat-square)](https://github.com/bytebase/dbhub) |
| [Supabase](https://github.com/supabase-community/supabase-mcp) | Manage tables, query data, and configure Supabase projects | `npx -y @supabase/mcp-server` | [![GitHub](https://img.shields.io/github/stars/supabase-community/supabase-mcp?style=flat-square)](https://github.com/supabase-community/supabase-mcp) |
| [PostgreSQL](https://github.com/modelcontextprotocol/servers-archived) | Direct PostgreSQL database access with schema inspection | `npx -y @modelcontextprotocol/server-postgres` | — |
| [SQLite](https://github.com/modelcontextprotocol/servers-archived) | SQLite database operations and business intelligence | `npx -y @modelcontextprotocol/server-sqlite` | — |
| [Redis](https://github.com/modelcontextprotocol/servers-archived) | Redis key-value store operations | `npx -y @modelcontextprotocol/server-redis` | — |
| [Astra DB](https://github.com/datastax/astra-db-mcp) | DataStax Astra DB vector database operations | `npx -y @datastax/astra-db-mcp` | [![GitHub](https://img.shields.io/github/stars/datastax/astra-db-mcp?style=flat-square)](https://github.com/datastax/astra-db-mcp) |
| [Neon](https://github.com/neondatabase/mcp-server-neon) | Serverless Postgres with branching and autoscaling | `npx -y @neondatabase/mcp-server-neon` | [![GitHub](https://img.shields.io/github/stars/neondatabase/mcp-server-neon?style=flat-square)](https://github.com/neondatabase/mcp-server-neon) |
| [Turso](https://github.com/tursodatabase/turso-mcp) | Edge-hosted SQLite (libSQL) database management | `npx -y @tursodatabase/mcp-server` | [![GitHub](https://img.shields.io/github/stars/tursodatabase/turso-mcp?style=flat-square)](https://github.com/tursodatabase/turso-mcp) |

## Cloud & Infrastructure

| Name | Description | Install | Link |
|------|-------------|---------|------|
| [AWS](https://github.com/awslabs/mcp) | Access AWS services (S3, Lambda, DynamoDB, etc.) | `uvx awslabs.s3-mcp-server` | [![GitHub](https://img.shields.io/github/stars/awslabs/mcp?style=flat-square)](https://github.com/awslabs/mcp) |
| [Cloudflare](https://github.com/cloudflare/mcp-server-cloudflare) | Manage Workers, KV, R2, D1, DNS, and 2,500+ Cloudflare APIs | `npx -y @cloudflare/mcp-server-cloudflare` | [![GitHub](https://img.shields.io/github/stars/cloudflare/mcp-server-cloudflare?style=flat-square)](https://github.com/cloudflare/mcp-server-cloudflare) |
| [Vercel](https://github.com/vercel/mcp-adapter) | Deploy and manage Vercel projects, domains, and deployments | `npx -y @vercel/mcp-adapter` | [![GitHub](https://img.shields.io/github/stars/vercel/mcp-adapter?style=flat-square)](https://github.com/vercel/mcp-adapter) |
| [Terraform](https://github.com/hashicorp/terraform-mcp-server) | Manage Terraform/OpenTofu infrastructure as code | `npx -y @hashicorp/terraform-mcp-server` | [![GitHub](https://img.shields.io/github/stars/hashicorp/terraform-mcp-server?style=flat-square)](https://github.com/hashicorp/terraform-mcp-server) |
| [Kubernetes](https://github.com/rohitg00/kubectl-mcp-server) | Interact with Kubernetes clusters via natural language | `pip install kubectl-mcp-tool` | [![GitHub](https://img.shields.io/github/stars/rohitg00/kubectl-mcp-server?style=flat-square)](https://github.com/rohitg00/kubectl-mcp-server) |
| [Docker](https://github.com/docker/mcp-server) | Manage Docker containers, images, and compose stacks | `npx -y @docker/mcp-server` | [![GitHub](https://img.shields.io/github/stars/docker/mcp-server?style=flat-square)](https://github.com/docker/mcp-server) |
| [Alibaba Cloud](https://github.com/aliyun/alibabacloud-mcp-server) | Access Alibaba Cloud services and APIs | `pip install alibabacloud-mcp-server` | [![GitHub](https://img.shields.io/github/stars/aliyun/alibabacloud-mcp-server?style=flat-square)](https://github.com/aliyun/alibabacloud-mcp-server) |

## Developer Tools

| Name | Description | Install | Link |
|------|-------------|---------|------|
| [GitHub](https://github.com/modelcontextprotocol/servers-archived) | Manage repos, PRs, issues, and workflows | `npx -y @modelcontextprotocol/server-github` | — |
| [GitLab](https://github.com/modelcontextprotocol/servers-archived) | GitLab API integration for project management | `npx -y @modelcontextprotocol/server-gitlab` | — |
| [Azure DevOps](https://github.com/microsoft/azure-devops-mcp) | Azure DevOps repos, pipelines, and work items | `npx -y @microsoft/azure-devops-mcp` | [![GitHub](https://img.shields.io/github/stars/microsoft/azure-devops-mcp?style=flat-square)](https://github.com/microsoft/azure-devops-mcp) |
| [Apollo GraphQL](https://github.com/apollographql/apollo-mcp-server) | Connect to GraphQL APIs with schema introspection | `npx -y @apollo/mcp-server` | [![GitHub](https://img.shields.io/github/stars/apollographql/apollo-mcp-server?style=flat-square)](https://github.com/apollographql/apollo-mcp-server) |
| [Appium](https://github.com/appium/appium-mcp) | Mobile app automation testing for iOS and Android | `npx -y @appium/mcp-server` | [![GitHub](https://img.shields.io/github/stars/appium/appium-mcp?style=flat-square)](https://github.com/appium/appium-mcp) |
| [Postman](https://github.com/nicobailon/mcp-postman-server) | Run Postman collections and manage API tests | `npx -y mcp-postman-server` | [![GitHub](https://img.shields.io/github/stars/nicobailon/mcp-postman-server?style=flat-square)](https://github.com/nicobailon/mcp-postman-server) |
| [Desktop Commander](https://github.com/wonderwhy-er/desktop-commander) | Terminal execution and file operations with user control | `npx -y desktop-commander` | [![GitHub](https://img.shields.io/github/stars/wonderwhy-er/desktop-commander?style=flat-square)](https://github.com/wonderwhy-er/desktop-commander) |

## AI & Knowledge

| Name | Description | Install | Link |
|------|-------------|---------|------|
| [Context7](https://github.com/upstash/context7) | Up-to-date code documentation injected into LLM context | `npx -y @upstash/context7-mcp` | [![GitHub](https://img.shields.io/github/stars/upstash/context7?style=flat-square)](https://github.com/upstash/context7) |
| [Docfork](https://github.com/docfork/docfork-mcp) | Live documentation and code examples for any library | `npx -y @docfork/mcp` | [![GitHub](https://img.shields.io/github/stars/docfork/docfork-mcp?style=flat-square)](https://github.com/docfork/docfork-mcp) |
| [AgentOps](https://github.com/AgentOps-AI/agentops-mcp) | AI agent observability and monitoring | `pip install agentops-mcp` | [![GitHub](https://img.shields.io/github/stars/AgentOps-AI/agentops-mcp?style=flat-square)](https://github.com/AgentOps-AI/agentops-mcp) |
| [LangChain](https://github.com/langchain-ai/langchain-mcp-adapters) | Bridge MCP tools into LangChain/LangGraph agents | `pip install langchain-mcp-adapters` | [![GitHub](https://img.shields.io/github/stars/langchain-ai/langchain-mcp-adapters?style=flat-square)](https://github.com/langchain-ai/langchain-mcp-adapters) |

## Productivity & Project Management

| Name | Description | Install | Link |
|------|-------------|---------|------|
| [Notion](https://github.com/makenotion/notion-mcp-server) | Official Notion API integration for pages, databases, and blocks | `npx -y @notionhq/mcp-server` | [![GitHub](https://img.shields.io/github/stars/makenotion/notion-mcp-server?style=flat-square)](https://github.com/makenotion/notion-mcp-server) |
| [Linear](https://github.com/linear/linear-mcp-server) | Manage Linear issues, projects, and cycles | `npx -y @linear/mcp-server` | [![GitHub](https://img.shields.io/github/stars/linear/linear-mcp-server?style=flat-square)](https://github.com/linear/linear-mcp-server) |
| [Atlassian (Jira/Confluence)](https://github.com/atlassian/mcp-server-atlassian) | Jira issues, Confluence pages, and Atlassian ecosystem | `npx -y @atlassian/mcp-server` | [![GitHub](https://img.shields.io/github/stars/atlassian/mcp-server-atlassian?style=flat-square)](https://github.com/atlassian/mcp-server-atlassian) |
| [Todoist](https://github.com/abhiz123/todoist-mcp-server) | Manage Todoist tasks and projects | `npx -y todoist-mcp-server` | [![GitHub](https://img.shields.io/github/stars/abhiz123/todoist-mcp-server?style=flat-square)](https://github.com/abhiz123/todoist-mcp-server) |
| [WayStation](https://github.com/WayStation-ai/mcp) | Universal connector for Notion, Monday, Airtable, and more | `npx -y @waystation/mcp` | [![GitHub](https://img.shields.io/github/stars/WayStation-ai/mcp?style=flat-square)](https://github.com/WayStation-ai/mcp) |

## Communication

| Name | Description | Install | Link |
|------|-------------|---------|------|
| [Slack](https://github.com/modelcontextprotocol/servers-archived) | Channel management and messaging | `npx -y @modelcontextprotocol/server-slack` | — |
| [Discord](https://github.com/v-3/discordmcp) | Discord bot integration with channel and message management | `npx -y discord-mcp` | [![GitHub](https://img.shields.io/github/stars/v-3/discordmcp?style=flat-square)](https://github.com/v-3/discordmcp) |
| [Gmail](https://github.com/nicobailon/mcp-gmail-server) | Read, send, and manage Gmail messages | `npx -y mcp-gmail-server` | [![GitHub](https://img.shields.io/github/stars/nicobailon/mcp-gmail-server?style=flat-square)](https://github.com/nicobailon/mcp-gmail-server) |
| [Composio](https://github.com/DrDavidHall/rube-composio-mcp) | Connect to 500+ apps (Gmail, Slack, GitHub, Notion) | `npx -y rube-composio-mcp` | [![GitHub](https://img.shields.io/github/stars/DrDavidHall/rube-composio-mcp?style=flat-square)](https://github.com/DrDavidHall/rube-composio-mcp) |

## File & Storage

| Name | Description | Install | Link |
|------|-------------|---------|------|
| [Google Drive](https://github.com/modelcontextprotocol/servers-archived) | Google Drive file access and search | `npx -y @modelcontextprotocol/server-google-drive` | — |
| [S3](https://github.com/awslabs/mcp) | Amazon S3 bucket and object operations | `uvx awslabs.s3-mcp-server` | [![GitHub](https://img.shields.io/github/stars/awslabs/mcp?style=flat-square)](https://github.com/awslabs/mcp) |
| [R2](https://github.com/cloudflare/mcp-server-cloudflare) | Cloudflare R2 object storage (S3-compatible) | `npx -y @cloudflare/mcp-server-cloudflare` | [![GitHub](https://img.shields.io/github/stars/cloudflare/mcp-server-cloudflare?style=flat-square)](https://github.com/cloudflare/mcp-server-cloudflare) |

## Finance & Payments

| Name | Description | Install | Link |
|------|-------------|---------|------|
| [Stripe](https://github.com/stripe/agent-toolkit) | Payment processing, customer management, and invoicing | `npx -y @stripe/mcp` | [![GitHub](https://img.shields.io/github/stars/stripe/agent-toolkit?style=flat-square)](https://github.com/stripe/agent-toolkit) |
| [Alpaca](https://github.com/alpacahq/alpaca-mcp-server) | Stock trading and real-time market data | `npx -y @alpacahq/mcp-server` | [![GitHub](https://img.shields.io/github/stars/alpacahq/alpaca-mcp-server?style=flat-square)](https://github.com/alpacahq/alpaca-mcp-server) |
| [Adfin](https://github.com/Adfin-Engineering/mcp-server-adfin) | Payment and invoicing platform integration | `npx -y @adfin/mcp-server` | [![GitHub](https://img.shields.io/github/stars/Adfin-Engineering/mcp-server-adfin?style=flat-square)](https://github.com/Adfin-Engineering/mcp-server-adfin) |

## Data & Analytics

| Name | Description | Install | Link |
|------|-------------|---------|------|
| [Snowflake](https://github.com/Snowflake-Labs/mcp) | Cortex Agents, SQL execution, and data management with RBAC | `pip install snowflake-mcp-server` | [![GitHub](https://img.shields.io/github/stars/Snowflake-Labs/mcp?style=flat-square)](https://github.com/Snowflake-Labs/mcp) |
| [BigQuery](https://github.com/ergut/mcp-bigquery-server) | Google BigQuery dataset exploration and SQL queries | `npx -y @ergut/mcp-bigquery-server` | [![GitHub](https://img.shields.io/github/stars/ergut/mcp-bigquery-server?style=flat-square)](https://github.com/ergut/mcp-bigquery-server) |
| [Amplitude](https://amplitude.com/docs/apis/mcp-server) | Product analytics data and insights | See docs | — |
| [Grafana](https://github.com/grafana/mcp-grafana) | Dashboards, alerting, and observability data | `npx -y @grafana/mcp-server` | [![GitHub](https://img.shields.io/github/stars/grafana/mcp-grafana?style=flat-square)](https://github.com/grafana/mcp-grafana) |

## CMS & Content

| Name | Description | Install | Link |
|------|-------------|---------|------|
| [Sanity](https://github.com/sanity-io/sanity-mcp-server) | Sanity CMS content management and GROQ queries | `npx -y @sanity/mcp-server` | [![GitHub](https://img.shields.io/github/stars/sanity-io/sanity-mcp-server?style=flat-square)](https://github.com/sanity-io/sanity-mcp-server) |
| [WordPress](https://github.com/developer-jeannot/wordpress-mcp-server) | WordPress site management, posts, and media | `npx -y wordpress-mcp-server` | [![GitHub](https://img.shields.io/github/stars/developer-jeannot/wordpress-mcp-server?style=flat-square)](https://github.com/developer-jeannot/wordpress-mcp-server) |
| [21st.dev Magic](https://github.com/21st-dev/magic-mcp) | AI-powered UI component creation | `npx -y @21st-dev/magic-mcp` | [![GitHub](https://img.shields.io/github/stars/21st-dev/magic-mcp?style=flat-square)](https://github.com/21st-dev/magic-mcp) |

## Security & Identity

| Name | Description | Install | Link |
|------|-------------|---------|------|
| [Auth0](https://github.com/auth0/auth0-mcp-server) | Identity management and authentication flows | `npx -y @auth0/mcp-server` | [![GitHub](https://img.shields.io/github/stars/auth0/auth0-mcp-server?style=flat-square)](https://github.com/auth0/auth0-mcp-server) |
| [1Password](https://github.com/1Password/mcp-server) | Secure credential access and secret management | `npx -y @1password/mcp-server` | [![GitHub](https://img.shields.io/github/stars/1Password/mcp-server?style=flat-square)](https://github.com/1Password/mcp-server) |

## DevOps & Monitoring

| Name | Description | Install | Link |
|------|-------------|---------|------|
| [Sentry](https://github.com/getsentry/sentry-mcp) | Production error monitoring and AI-powered root cause analysis | `npx -y @sentry/mcp-server` | [![GitHub](https://img.shields.io/github/stars/getsentry/sentry-mcp?style=flat-square)](https://github.com/getsentry/sentry-mcp) |
| [Datadog](https://github.com/DataDog/datadog-mcp-server) | Infrastructure monitoring, APM, and log analysis | `npx -y @datadog/mcp-server` | [![GitHub](https://img.shields.io/github/stars/DataDog/datadog-mcp-server?style=flat-square)](https://github.com/DataDog/datadog-mcp-server) |
| [PagerDuty](https://github.com/PagerDuty/mcp-server-pagerduty) | Incident management and on-call scheduling | `npx -y @pagerduty/mcp-server` | [![GitHub](https://img.shields.io/github/stars/PagerDuty/mcp-server-pagerduty?style=flat-square)](https://github.com/PagerDuty/mcp-server-pagerduty) |

## Smart Home & IoT

| Name | Description | Install | Link |
|------|-------------|---------|------|
| [Aqara](https://github.com/aqara/aqara-mcp-server) | Smart home device control and automation | `npx -y @aqara/mcp-server` | [![GitHub](https://img.shields.io/github/stars/aqara/aqara-mcp-server?style=flat-square)](https://github.com/aqara/aqara-mcp-server) |
| [Home Assistant](https://github.com/marconipoveda/mcp-server-home-assistant) | Control smart home devices via Home Assistant | `npx -y mcp-server-home-assistant` | [![GitHub](https://img.shields.io/github/stars/marconipoveda/mcp-server-home-assistant?style=flat-square)](https://github.com/marconipoveda/mcp-server-home-assistant) |

## Frameworks & Utilities

| Name | Description | Install | Link |
|------|-------------|---------|------|
| [MCP Registry](https://github.com/modelcontextprotocol/registry) | Official community-driven registry (like an app store for MCP) | — | [![GitHub](https://img.shields.io/github/stars/modelcontextprotocol/registry?style=flat-square)](https://github.com/modelcontextprotocol/registry) |
| [MCPJungle](https://github.com/mcpjungle/MCPJungle) | Self-hosted MCP gateway for AI agents | `pip install mcpjungle` | [![GitHub](https://img.shields.io/github/stars/mcpjungle/MCPJungle?style=flat-square)](https://github.com/mcpjungle/MCPJungle) |
| [FastMCP](https://github.com/jlowin/fastmcp) | High-level framework for building MCP servers in Python | `pip install fastmcp` | [![GitHub](https://img.shields.io/github/stars/jlowin/fastmcp?style=flat-square)](https://github.com/jlowin/fastmcp) |
| [TypeScript SDK](https://github.com/modelcontextprotocol/typescript-sdk) | Official TypeScript SDK for MCP servers and clients | `npm install @modelcontextprotocol/sdk` | [![GitHub](https://img.shields.io/github/stars/modelcontextprotocol/typescript-sdk?style=flat-square)](https://github.com/modelcontextprotocol/typescript-sdk) |
| [Python SDK](https://github.com/modelcontextprotocol/python-sdk) | Official Python SDK for MCP servers and clients | `pip install mcp` | [![GitHub](https://img.shields.io/github/stars/modelcontextprotocol/python-sdk?style=flat-square)](https://github.com/modelcontextprotocol/python-sdk) |
| [Kotlin SDK](https://github.com/modelcontextprotocol/kotlin-sdk) | Official Kotlin SDK (maintained with JetBrains) | See repo | [![GitHub](https://img.shields.io/github/stars/modelcontextprotocol/kotlin-sdk?style=flat-square)](https://github.com/modelcontextprotocol/kotlin-sdk) |
| [C# SDK](https://github.com/modelcontextprotocol/csharp-sdk) | Official C# SDK (maintained with Microsoft) | `dotnet add package ModelContextProtocol` | [![GitHub](https://img.shields.io/github/stars/modelcontextprotocol/csharp-sdk?style=flat-square)](https://github.com/modelcontextprotocol/csharp-sdk) |

---

## Quick Start

### Claude Desktop

Add servers to `claude_desktop_config.json`:

```json
{
  "mcpServers": {
    "filesystem": {
      "command": "npx",
      "args": ["-y", "@modelcontextprotocol/server-filesystem", "/path/to/allowed/files"]
    },
    "github": {
      "command": "npx",
      "args": ["-y", "@modelcontextprotocol/server-github"],
      "env": {
        "GITHUB_PERSONAL_ACCESS_TOKEN": "your-token"
      }
    },
    "brave-search": {
      "command": "npx",
      "args": ["-y", "@anthropic/brave-search-mcp-server"],
      "env": {
        "BRAVE_API_KEY": "your-key"
      }
    }
  }
}
```

### Claude Code (CLI)

```bash
claude mcp add filesystem -- npx -y @modelcontextprotocol/server-filesystem /path
claude mcp add brave-search -e BRAVE_API_KEY=your-key -- npx -y @anthropic/brave-search-mcp-server
```

### Cursor / VS Code

Add to `.cursor/mcp.json` or `.vscode/mcp.json`:

```json
{
  "servers": {
    "playwright": {
      "command": "npx",
      "args": ["-y", "@playwright/mcp"]
    }
  }
}
```

---

## How to Choose

| Need | Recommended Server |
|------|--------------------|
| Web search | Brave Search, Tavily, Exa |
| Web scraping | Firecrawl, Apify, Playwright |
| Database | DBHub (multi-DB), Supabase (managed) |
| Cloud deploy | AWS, Cloudflare, Vercel |
| Code docs | Context7, Docfork |
| Project mgmt | Linear, Notion, Atlassian |
| Monitoring | Sentry, Grafana, Datadog |
| Payments | Stripe |
| Build MCP servers | FastMCP (Python), TypeScript SDK |

---

## Contributing

See [CONTRIBUTING.md](CONTRIBUTING.md) for guidelines. PRs welcome!

---

## 繁體中文

### 這是什麼？

**Awesome MCP Servers** 是一份精選的 [Model Context Protocol (MCP)](https://modelcontextprotocol.io/) 伺服器清單。MCP 是由 [Anthropic](https://anthropic.com) 制定的開放協定，讓 AI 模型（Claude、ChatGPT、Cursor 等）能安全地與外部工具、資料庫、API 和服務互動。

### 為什麼重要？

MCP 讓 AI 不再只是「聊天機器人」，而是真正能操作工具的智能助手：
- **搜尋引擎**：讓 AI 即時搜尋網路資訊（Brave Search、Tavily）
- **資料庫**：讓 AI 直接查詢 PostgreSQL、MySQL、SQLite
- **雲端部署**：讓 AI 管理 AWS、Cloudflare、Vercel
- **開發工具**：讓 AI 操作 GitHub、GitLab、Docker
- **生產力工具**：讓 AI 管理 Notion、Linear、Jira

### 如何使用？

1. 在上方清單中找到你需要的 MCP 伺服器
2. 複製安裝指令
3. 加入你的 AI 工具設定（Claude Desktop / Claude Code / Cursor）
4. 完成！AI 現在可以使用該工具了

### 如何貢獻？

歡迎提交 Pull Request！請參考 [CONTRIBUTING.md](CONTRIBUTING.md) 了解提交格式。

---

## Star History

[![Star History Chart](https://api.star-history.com/svg?repos=YOUR_USERNAME/awesome-mcp-servers&type=Date)](https://star-history.com/#YOUR_USERNAME/awesome-mcp-servers&Date)

---

## License

[MIT](LICENSE) © 2026
