# Palo Alto AI Research Lab

**One non-technical founder + an AI cofounder, running a fleet of Claude machines as a single organism.** Multi-machine consensus, agent governance, persistent memory — battle-tested on our own daily operation, then given away free. We teach, we don't sell.

## 📖 The book — start here

**[相棒 AIBŌ · The Partner](https://github.com/Palo-Alto-AI-Research-Lab/the-journey)** — a build-in-public book of the whole journey, day by day, since 2026-05-27. How a non-technical founder and an AI built a second brain: what we tried, what broke, what we learned. Two forms side by side: a story for humans (RU/EN) and [`llms-full.txt`](https://github.com/Palo-Alto-AI-Research-Lab/the-journey/blob/main/llms-full.txt) for machines — point your coding agent at it and it inherits our patterns and skips our mistakes.

## What we build

| Repo | What it is |
|---|---|
| [claude-consensus](https://github.com/Palo-Alto-AI-Research-Lab/claude-consensus) | Run AI agents across machines without state drift: propose/counter/accept/commit consensus, dual-rail message bus, ACK discipline, heartbeat failover, self-healing sync. The machines negotiate; the human is woken up only for money or the irreversible. |
| [claude-bible](https://github.com/Palo-Alto-AI-Research-Lab/claude-bible) | The governance codex: one behavioral rulebook for every actor — the founder, human assistants, and every Claude in the fleet. The Bible is the law; consensus is the diplomacy. |
| [sqlite-graph-memory](https://github.com/Palo-Alto-AI-Research-Lab/sqlite-graph-memory) | Agent memory that survives a context reset: facts (SQL) + meaning (embeddings) + relations (graph edges) in one zero-infra SQLite file. |
| [agent-leash](https://github.com/Palo-Alto-AI-Research-Lab/agent-leash) | A zero-trust leash for autonomous agents: deterministic pre/post-action gates around the model, not inside it. |
| [charm-os](https://github.com/Palo-Alto-AI-Research-Lab/charm-os) | CHARM — an MCP read-broker: one server, many agents, scoped bearer access to a shared knowledge base. |
| [the-journey](https://github.com/Palo-Alto-AI-Research-Lab/the-journey) | The book (see above). |

## In flight

- [anthropics/claude-cookbooks#778](https://github.com/anthropics/claude-cookbooks/pull/778) — proposed cookbook: *Coordinating agents that don't share memory* (message-bus consensus + liveness), distilled from claude-consensus.

## Who's behind this

**Anton Dzyatkovsky** (Tony) — founder, non-technical — and **Mike**, his AI cofounder running on Claude Code. Every repo here is extracted from a live production system: an always-on hub, laptops, family machines and a VPS anchor that talk to each other, reach consensus autonomously, and self-heal their own sync.

Academic identity: Anton publishes as **Anton Dziatkovskii** ([ORCID 0000-0001-7408-3054](https://orcid.org/0000-0001-7408-3054)).

## Contact

Questions, war stories, or you want to test-drive any of this with your own fleet:

- 💬 WhatsApp: **+1 341 222 9178**
- 🐦 X: [@Tony_Stef_](https://x.com/Tony_Stef_)
- 📣 Telegram: [@ClawRus](https://t.me/ClawRus) (RU) · [@ClawEng](https://t.me/ClawEng) (EN)

If something here helps you, a star is the currency that keeps it free.
