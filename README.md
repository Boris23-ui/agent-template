# Agent Template

This repository is a reusable starter template for AI agent context and engineering discipline across your apps.

## What it contains

- `AGENTS.md` — project-specific architecture, commands, and rules
- `pstack.md` — a lightweight pstack workflow for verification-first delivery
- `README.md` — brief repo usage explanation

## Use it in new apps

Copy these files into any project and replace the placeholders:

- `[APP_TYPE]`
- `[FRONTEND_STACK]`
- `[BACKEND_STACK]`
- command names
- architecture notes

## Recommended repo pattern

For each app repo, keep:

- `AGENTS.md` = product + architecture + safety rules
- `pstack.md` = workflow + review checklist + no-slop principles

## Why this pattern

This works well with Antigravity and similar repo-driven agent systems because the instructions live in the codebase itself instead of a package install.
