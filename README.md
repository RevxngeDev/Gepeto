# Gepeto

A personal AI assistant built on **Hermes Agent** (Nous Research, MIT), configured,
versioned and deployed by its single owner. You talk to it over Telegram; it remembers
you across sessions, runs scheduled tasks unprompted, and delegates coding work to
Claude Code / OpenCode.

> Claude Code works **on a repository**. Gepeto works **for me**.

## Where the project state lives

`docs/ai-context/` is the single source of project state. Start there:

- **[PROJECT_CONTEXT](docs/ai-context/PROJECT_CONTEXT.md)** — what it is and what for.
- **[CURRENT_STATE](docs/ai-context/CURRENT_STATE.md)** — where we are right now *(authoritative)*.
- **[ARCHITECTURE](docs/ai-context/ARCHITECTURE.md)** — how it's built.
- **[DECISIONS](docs/ai-context/DECISIONS.md)** — why we decided what we decided *(authoritative)*.
- **[COMMANDS](docs/ai-context/COMMANDS.md)** — how to run / test / deploy.
- **[ROADMAP](docs/ai-context/ROADMAP.md)** — the gated phases.
- **[SESSION_LOG](docs/ai-context/SESSION_LOG.md)** — session history + next step.

`CURRENT_STATE` and `DECISIONS` win over everything else if they disagree.

## Working on Gepeto

Read **[CLAUDE.md](CLAUDE.md)** / **[AGENTS.md](AGENTS.md)** (identical) — the operating
manual: source-of-truth rule, session loop, gated phases, project rules, and the
guided/manual working mode.

## Status

**Phase 0 — repository and context.** Hermes is not installed yet; nothing is deployed.
See [CURRENT_STATE](docs/ai-context/CURRENT_STATE.md).
