# composio

Welcome to the **composio** project!

composio is an agent orchestration system designed to help you coordinate and manage worker agent sessions for software engineering tasks. It provides a seamless workflow for spawning, monitoring, and communicating with AI-powered worker agents that can handle everything from implementing features to addressing code reviews.

## What composio Does

- **Automates development workflows** — spawn agents to tackle GitHub/Linear issues, implement features, and submit pull requests
- **Manages multi-agent sessions** — coordinate multiple workers in parallel, each with its own isolated git worktree and branch
- **Monitors CI and reviews** — automatically forwards CI failures and review comments back to the responsible agent
- **Provides real-time visibility** — a live web dashboard and CLI give you an at-a-glance view of all active sessions and their status

## Getting Started

```bash
# Check the status of all active sessions
ao status

# Spawn a worker session for an issue
ao spawn INT-1234

# Or spawn a freeform session with a custom prompt
ao spawn --prompt "Refactor the auth module to use JWT"

# Open the live dashboard
ao dashboard
```

## Issue Tracking

Tasks for this project are managed in **Linear**. When spawning a worker session for a Linear issue, use the issue ID directly:

```bash
ao spawn ALI-5
```

The agent will fetch the issue title and description from Linear and use them as context for the implementation.

## Learn More

See the full documentation for details on session management, PR workflows, and dashboard features.

John Doe

