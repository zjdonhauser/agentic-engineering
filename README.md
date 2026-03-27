# Agentic Engineering

Patterns for building production AI systems — not just using Claude Code day-to-day, but the engineering principles that make agentic workflows reliable.

**[View the presentation →](https://zjdonhauser.github.io/agentic-engineering/)**

## Concepts Covered

1. **The Agentic Loop** — `stop_reason` is the contract. `tool_use` = keep looping, `end_turn` = done.
2. **Context Engineering** — Front-load cheap data before the first Claude call. DB queries cost milliseconds and zero tokens.
3. **Tool Descriptions Drive Selection** — When the model picks the wrong tool, fix the description. Not few-shot examples, not a routing layer.
4. **Programmatic Enforcement** — Schema enforcement via `output_config.format` is deterministic. Prompt instructions are probabilistic.
5. **Match Cost to Complexity** — Opus for first investigation, Haiku for repeat triage. 87% cost savings over naive all-Opus.
6. **The Autonomy ↔ Constraint Tradeoff** — You earn autonomy by proving your constraints are tight enough.
7. **Rules, Commands, and Team Patterns** — `.claude/rules/` for path-scoped context, `.claude/commands/` for reusable team workflows shared via git.

## Running Locally

Open `index.html` in a browser. Arrow keys to navigate. No dependencies.
