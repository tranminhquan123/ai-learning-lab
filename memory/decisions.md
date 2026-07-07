# Decisions

This file records important decisions so Claude does not ask the same setup questions again.

## Repo Organization

Decision:

Use one main GitHub repository named `ai-learning-lab`.

Reason:

Avoid cluttering GitHub with too many forked repositories. External repositories should be starred on GitHub or cloned locally for reading and practice.

## Python Roadmap

Decision:

Do not include the basic Python roadmap in this repository.

Reason:

The basic Python roadmap already exists separately. This repository focuses on AI, Claude workflow, finance, Chinese, DaVinci Resolve, and projects after Python basics.

## Repository Installation Strategy

Decision:

Do not fork every useful repository.

Rules:

- Tool/package repositories: install with package managers or plugin commands.
- Course/documentation repositories: clone locally for reading and practice.
- Personal learning work: save in `ai-learning-lab`.
- Fork only when modifying a repository or contributing pull requests.

## Priority Repository Group

Decision:

Focus first on the Group A repositories:

1. `anthropics/claude-code`
2. `anthropics/skills`
3. `anthropics/courses`
4. `anthropics/claude-cookbooks`
5. `anthropics/anthropic-sdk-python`
6. `modelcontextprotocol/servers`
7. `github/github-mcp-server`
8. `mem0ai/mem0`
9. `crewAIInc/crewAI`
10. `m98/fluent`

## Current Workflow Decision

Decision:

Set up the repository first before installing all tools.

Reason:

Claude will work better when `CLAUDE.md`, `memory/`, `prompts/`, `skills/`, and `resources/` are already organized.
