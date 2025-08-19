![](https://europe-west1-atp-views-tracker.cloudfunctions.net/working-analytics?notebook=tutorials--multi-user-agent-arcade--readme)

# 🚀 Multi-User Agent Tutorial with Arcade.dev

This tutorial shows you how to build AI agents that can actually work in production - specifically, agents that can securely access external services for multiple users.

## What This Covers

This tutorial bridges the gap between those cool AI agent demos you build locally and systems that can actually handle real users in production. We'll implement secure authentication and safety controls using Arcade.dev.

## What You'll Learn

- **Multi-User Authentication**: Set up OAuth2 flows for Gmail, Slack, and Notion using Arcade's platform
- **Production Architecture**: Build agents that scale beyond single-user demos with proper security
- **Safety Controls**: Add human-in-the-loop approval for sensitive operations
- **Real Service Integration**: Connect your agents to actual external APIs with proper auth

## What You'll Build

1. **Basic Chat Agent**: A simple conversational AI using LangGraph
2. **Tool-Enabled Agent**: AI that can securely access external APIs
3. **Production Agent**: A full system with safety controls and multi-service coordination

## Tech Stack

- **LangGraph**: For agent orchestration and state management
- **Arcade.dev**: Handles authentication and secure API access
- **OAuth2**: For secure user authorization

## Get Started

**[Start the Tutorial →](multiuser-agent-arcade.ipynb)**

The notebook walks you through building progressively more sophisticated agents, from basic chat to a production-ready system that integrates with Gmail, Slack, and Notion.

## Who This Is For

Developers who want to build AI agents that can actually work in the real world with multiple users, not just cool demos.
