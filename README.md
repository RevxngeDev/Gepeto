# Gepeto

A personal AI assistant built on **Hermes Agent** (Nous Research, MIT), configured,
versioned and deployed by its single owner. You talk to it over Telegram; it remembers
you across sessions, runs scheduled tasks unprompted, and delegates coding work to
Claude Code / OpenCode.

> Claude Code works **on a repository**. Gepeto works **for me**.

## Repository layout

- `config/` — Hermes configuration and Gepeto's identity.
- `skills/` — Gepeto's skills.
- `cron/` — scheduled-task definitions.
- `deploy/` — deployment (Docker + systemd).
- `.env.example` — required environment variables. Copy to `.env` (untracked) and fill in; no real values are committed.

## Status

**Phase 0 — repository and context.** Hermes is not installed yet; nothing is deployed.
