# Prompts

> [!WARNING]
> This repository is archived. All prompts have been migrated to
> [nikitabarskov/dotfiles/.agents/skills](https://github.com/nikitabarskov/dotfiles/tree/main/.agents/skills).

This repository originally held system prompts used with the [Zed AI assistant](https://zed.dev/docs/assistant/assistant),
organized by role:

- **writer/review** — technical editor prompt for critiquing accuracy, clarity, and practical value
- **review/architecture** — principal engineer prompt for critiquing software architecture across scalability, reliability, security, and cost dimensions
- **review/golang** — Go-focused code review prompt covering concurrency, performance, and idiomatic style
- **git/commit** — commit message generator following trunk-based development practices
- **assist/meta** — prompt engineer meta-prompt for generating structured, token-efficient prompts

As AI tooling matured from editor-specific assistants toward general-purpose agents, these prompts
outgrew the "paste into a chat" model. They are now maintained as reusable agent skills in the
dotfiles repository, where they can be loaded automatically by agents that support the skill format.
