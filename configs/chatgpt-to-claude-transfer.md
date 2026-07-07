# ChatGPT to Claude Transfer Guide

This guide explains how to move useful context from ChatGPT conversations into Claude Web.

## Main Principle

Do not transfer every raw chat.

Instead, transfer compressed context:

1. Current goal
2. Decisions already made
3. Important constraints
4. Progress so far
5. Mistakes and weak points
6. Next steps

## Best Files to Give Claude First

Always start with:

1. `CLAUDE.md`
2. `memory/learning-state.md`
3. `memory/decisions.md`
4. `memory/projects-log.md`

Then add one conversation summary if the task depends on an old ChatGPT conversation.

## How to Convert One ChatGPT Conversation

Open the old ChatGPT conversation and ask ChatGPT:

```text
Summarize this conversation for Claude. Focus only on durable context: goals, decisions, constraints, current progress, mistakes, unresolved questions, and next actions. Remove unnecessary back-and-forth.
```

Save the result as a Markdown file.

Recommended path:

`context-packs/chatgpt-summaries/YYYY-MM-DD-topic.md`

## How to Use in Claude Web

Upload or paste:

1. The four core files
2. The relevant summary file
3. The task you want Claude to do now

## What Not to Transfer

Do not transfer:

- repeated small talk
- full raw conversations unless necessary
- API keys
- passwords
- private personal information not needed for the task
- large unrelated chat history

## Recommended Claude Web Opening Prompt

```text
I am moving context from ChatGPT to Claude Web. I will provide my core repo files and one summarized ChatGPT conversation. Read them first, then continue from the current state. Do not assume access to files I have not uploaded or pasted.
```
