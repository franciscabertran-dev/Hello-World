# AGENTS.md

## Repository Overview

This is a minimal "Hello World" repository used for Git/GitHub workflow practice. There is no application code, build system, test suite, or package management.

## Facts

- **No build/test/lint tooling** — nothing to run beyond `git` commands.
- **No dependencies or lockfiles** — plain Markdown only.
- **No CI/CD configuration** — PR checks are not configured.
- **Content**: `README.md` with simple Spanish text.

## Workflow

- Default branch: `main`
- No special branch or release conventions are configured.
- Edit `README.md` directly; no build step required before commit.

## Project-specific Commands

- **ping** (`.opencode/commands/ping.md`) - responds with pong. Trigger: `/ping`
When the user types `/ping`, the content of `ping.md` is sent as a prompt to the AI assistant.
