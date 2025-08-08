![](https://europe-west1-atp-views-tracker.cloudfunctions.net/working-analytics?notebook=tutorials--agent-with-brightdata--README)

# Build Powerful Web Scraping Agents with LangGraph & Bright Data 🕷️


## Overview

This comprehensive tutorial series is designed for Python developers who want to build intelligent web scraping agents that can search, extract, and analyze data from any website. These agents combine the power of LangGraph's ReAct framework with Bright Data's industry-leading web scraping capabilities, enabling you to create production-ready systems for data collection, market research, competitive analysis, and automated content monitoring.

Whether you're building a market intelligence platform, conducting academic research, or creating content aggregation systems, these tutorials will give you the tools to handle complex web scraping tasks with AI-powered decision making.

## What You'll Learn

By completing this tutorial series, you'll master:

- **ReAct Agent Architecture** - Understanding how reasoning and acting agents work
- **Intelligent Web Search** - Building agents that choose optimal search strategies
- **Structured Data Extraction** - Extracting data from major platforms (Amazon, LinkedIn, social media)
- **Universal Web Scraping** - Handling any website with advanced bot detection bypass
- **Multi-Step Research** - Creating agents that conduct comprehensive research workflows
- **Production Optimization** - Error handling, rate limiting, and performance tuning

## Tutorial Series

This tutorial series offers two complementary approaches to building web scraping agents:

### 🔧 **Guide 1: MCP Integration Approach**
**[Build with Bright Data MCP Server](./web_scraping_agent.ipynb)**

Learn to build sophisticated web scraping agents using Bright Data's Model Context Protocol (MCP) server, which provides access to 60+ specialized tools including browser automation, platform-specific extractors, and advanced scraping capabilities.

**Key Features:**
- Complete MCP server integration
- 60+ specialized scraping tools
- Browser automation workflows
- Platform-specific extractors (Amazon, LinkedIn, Instagram, etc.)

**Best For:** Developers who need maximum flexibility and access to all Bright Data capabilities.

### ⚡ **Guide 2: LangChain Tools Approach**
**[Build with Bright Data LangChain Tools](./langgraph_integration.ipynb)**

Create streamlined web scraping agents using Bright Data's native LangChain tools for rapid development and easy integration with existing LangChain workflows.

**Key Features:**
- Native LangChain integration
- Simplified setup and configuration
- SERP (Search Engine Results Page) tools
- Multi-language and multi-region support
- Production-ready patterns

**Best For:** Developers who want quick setup and seamless LangChain ecosystem integration.

## Directory Structure

```
📁 bright-data-web-scraping-agents/
├── 📓 web-research-agent-mcp.ipynb.ipynb          # MCP approach tutorial
├── 📓 langchain-integration-guide.ipynb    # LangChain tools approach tutorial
├── 📁 assets/                              # Diagrams and screenshots
│   ├── 🖼️ signup.png                      # Bright Data signup process
│   ├── 🖼️ settings.png                    # API key location
├── 📄 requirements.txt                     # Python dependencies
└── 📄 README.md                            # This file
```

## Quick Start

### Prerequisites

- Python 3.8+ installed on your system
- Basic knowledge of Python and APIs
- Jupyter Notebook environment (Anaconda, Google Colab, or local setup)

### Setup Steps

1. **Sign up for Bright Data**
   - Visit [Bright Data](https://brightdata.com/?hs_signup=1&utm_source=brand&utm_campaign=brnd-mkt_github_nirdiamant_logo)
   - Get 5k free requests monthly (Applied ONLY for MCP users)
   - Copy your API key from account settings

2. **Get LLM API Access**
   - **For MCP Guide**: Sign up at [OpenRouter](https://openrouter.ai) for Gemini access
   - **For LangChain Guide**: Get Google API key from [AI Studio](https://aistudio.google.com)


3. **Choose Your Path**
   - Start with **LangChain Guide** for quick setup
   - Use **MCP Guide** for advanced capabilities (and a free tier!)
