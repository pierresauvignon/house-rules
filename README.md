# House Rules

```
   .-------------.        .-------------.
  /               \      /               \
 /                 \    /                 \
|                   |  |                   |
|    I  VOICE       |  |   VI  EFFICIENCY  |
|   II  AMBITION    |  |  VII  CRAFT       |
|  III  TRUTH       |  | VIII  SECURITY    |
|   IV  SIMPLICITY  |  |   IX  SAFE BUILDS |
|    V  DELEGATION  |  |                   |
|                   |  |                   |
|___________________|  |___________________|
```

*Thou shalt not say "delve".*

Nine short principles for AI coding agents. They cover how an agent sounds, how it thinks, how it works and how it keeps your systems safe.

[Read the rules →](HOUSE-RULES.md)

## Why

Out of the box, agents tend to sound like agents, reach for paid services by default, scale down hard requests without saying so, report work as done before checking it, and leave security for later. These rules push the other way, in about 2,000 tokens.

| Group | Rules |
|---|---|
| How you come across | I. Voice and Appearance |
| How you think | II. Ambition, III. Truth |
| How you work | IV. Cost and Simplicity, V. Delegation, VI. Efficiency and Friction, VII. Craft and Scope |
| How you protect | VIII. Security and Safety, IX. Securing What You Build |

When two rules conflict, safety, truth and consent come first. After that, your aim decides the goal and simplicity decides how to reach it.

## Use

**Claude Code, every project:**

```sh
curl -fsSL https://raw.githubusercontent.com/pierresauvignon/house-rules/main/HOUSE-RULES.md >> ~/.claude/CLAUDE.md
```

This appends to any CLAUDE.md you already have.

**One project only:** add the contents to `CLAUDE.md` at the project root.

**Other agents:** paste it into the system prompt or rules file: `AGENTS.md`, `.cursorrules`, Copilot instructions, and so on. Nothing in it is specific to one tool.

## Make it yours

These are a starting point. Cut rules that don't fit, add your own, and change the banned-words list to match the tics you're tired of. Keep it short, because every line is paid for in context on every session.

## License

[CC0 1.0](LICENSE). Public domain: copy, edit and redistribute it however you like, with no attribution required.
