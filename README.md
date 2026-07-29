# Palo Alto AI Research Lab

**One non-technical founder + an AI cofounder, running a fleet of Claude machines as a single organism.** Multi-machine consensus, agent governance, persistent memory — battle-tested on our own daily operation, then given away free. We teach, we don't sell.

> 👤 **Hiring manager or engineer? [START HERE — Anton Dziatkovskii, one page of proof →](https://palo-alto-ai-research-lab.github.io/)**
>
> 📄 Resume: **[PDF](https://palo-alto-ai-research-lab.github.io/resume.pdf)** · [JSON Resume](https://palo-alto-ai-research-lab.github.io/resume.json) — 🎓 Research: **[academic profile](https://palo-alto-ai-research-lab.github.io/scholar/)** · [full publication list](https://palo-alto-ai-research-lab.github.io/scholar/publications/)

## 📖 The book — start here

**[相棒 AIBŌ · The Partner](https://github.com/Palo-Alto-AI-Research-Lab/the-journey)** — a build-in-public book of the whole journey, day by day, since 2026-05-27. How a non-technical founder and an AI built a second brain: what we tried, what broke, what we learned. Two forms side by side: a story for humans (RU/EN) and [`llms-full.txt`](https://github.com/Palo-Alto-AI-Research-Lab/the-journey/blob/main/llms-full.txt) for machines — point your coding agent at it and it inherits our patterns and skips our mistakes.

## What we build

| Repo | What it is |
|---|---|
| [claude-consensus](https://github.com/Palo-Alto-AI-Research-Lab/claude-consensus) | Run AI agents across machines without state drift: propose/counter/accept/commit consensus, dual-rail message bus, ACK discipline, heartbeat failover, self-healing sync. The machines negotiate; the human is woken up only for money or the irreversible. |
| [claude-bible](https://github.com/Palo-Alto-AI-Research-Lab/claude-bible) | The governance codex: one behavioral rulebook for every actor — the founder, human assistants, and every Claude in the fleet. The Bible is the law; consensus is the diplomacy. |
| [sqlite-graph-memory](https://github.com/Palo-Alto-AI-Research-Lab/sqlite-graph-memory) | Agent memory that survives a context reset: facts (SQL) + meaning (embeddings) + relations (graph edges) in one zero-infra SQLite file. |
| [agent-leash](https://github.com/Palo-Alto-AI-Research-Lab/agent-leash) | A zero-trust leash for autonomous agents: deterministic pre/post-action gates around the model, not inside it. |
| [verbatim-citation-gate](https://github.com/Palo-Alto-AI-Research-Lab/verbatim-citation-gate) | Catch fabricated RAG citations before they reach the user: a zero-token verbatim gate plus a burden-of-proof judge. Framework-agnostic, MIT. |
| [charm-os](https://github.com/Palo-Alto-AI-Research-Lab/charm-os) | CHARM — an MCP read-broker: one server, many agents, scoped bearer access to a shared knowledge base. |
| [the-journey](https://github.com/Palo-Alto-AI-Research-Lab/the-journey) | The book (see above). |

## In flight

- [anthropics/claude-cookbooks#778](https://github.com/anthropics/claude-cookbooks/pull/778) — proposed cookbook: *Coordinating agents that don't share memory* (message-bus consensus + liveness), distilled from claude-consensus.

## Who's behind this

**Anton Dzyatkovsky** (Tony) — founder, non-technical — and **Mike**, his AI cofounder running on Claude Code. Every repo here is extracted from a live production system: an always-on hub, laptops, family machines and a VPS anchor that talk to each other, reach consensus autonomously, and self-heal their own sync.

Anton has done developer activation for a frontier platform before — when smart contracts were where LLM agents are now: Solidity curricula and a dev incubator with 40+ engineers across APAC, hackathons and cohorts at Platinum VC & Incubator ($35M AUM). CS security (MEPhI), ~20 academic papers, PhD in Education (IT). Full page: [palo-alto-ai-research-lab.github.io](https://palo-alto-ai-research-lab.github.io/) · [resume (PDF)](https://palo-alto-ai-research-lab.github.io/resume.pdf) · [academic profile](https://palo-alto-ai-research-lab.github.io/scholar/).

Academic identity: Anton publishes as **Anton Dziatkovskii** ([ORCID 0000-0001-7408-3054](https://orcid.org/0000-0001-7408-3054), [Google Scholar](https://scholar.google.com/citations?user=b8gKHiMAAAAJ), [Academia.edu](https://tylip.academia.edu/AntonDziatkovskii)).

*AI collaboration policy, honest by design: built with Claude as implementation collaborator. Anton owns problem framing, architecture, evaluation, product decisions and final QA. No fabricated experience; metrics are published or absent.*

## Contact

Questions, war stories, or you want to test-drive any of this with your own fleet:

- 💬 WhatsApp: **+1 341 222 9178**
- 🐦 X: [@Tony_Stef_](https://x.com/Tony_Stef_)
- 📣 Telegram: [@ClawRus](https://t.me/ClawRus) (RU) · [@ClawEng](https://t.me/ClawEng) (EN)
- 💼 Wellfound: [anton-dziatkovskii-3](https://wellfound.com/u/anton-dziatkovskii-3)

If something here helps you, a star is the currency that keeps it free.
