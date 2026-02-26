# heurema

> Craft, not conjuring.

Open-source tools that make AI agent workflows auditable, bounded, and trustworthy.

## Vision

AI agents act at machine speed. The discipline to govern them must be built in, not bolted on. heurema builds infrastructure for teams that delegate aggressively and verify everything.

## Principles

1. **Discovery before automation.** Find better work, not just faster work.
2. **Accountability is not delegatable.** Agents execute. Humans own outcomes.
3. **Context is a product.** Bad context produces confident wrong output.
4. **Tests are contracts.** If a machine cannot enforce it, it is a suggestion.
5. **Silent autonomy is a defect.** No audit trail means no work.
6. **Failure is never silent.** It surfaces immediately and names an owner.
7. **Open source is a constraint.** If it cannot be reviewed, it does not ship.

## Tools

| Tool | What it does |
|------|-------------|
| [sigil](https://github.com/heurema/sigil) | Risk-adaptive development pipeline with adversarial consensus code review |
| [herald](https://github.com/heurema/herald) | Daily curated news digest — zero API keys, fully local |
| [proofpack](https://github.com/heurema/proofpack) | Proof-carrying CI gate for AI agent changes |
| [codex-partner](https://github.com/heurema/codex-partner) | Codex CLI as independent verification alongside Claude Code |
| [teams-field-guide](https://github.com/heurema/teams-field-guide) | Comprehensive guide to Claude Code multi-agent teams |
| [emporium](https://github.com/heurema/emporium) | Plugin marketplace — install any tool with one command |

## Install

```bash
claude plugin marketplace add heurema/emporium
claude plugin install sigil@emporium
```

---

*The measure of a heurema tool: when something goes wrong, you know exactly where, and exactly whose call it was.*
