# Outcome Engineering

AI-assisted development produces code fast — but without structure, that code drifts from requirements, violates decisions, and accumulates rework. Outcome Engineering fixes this with a **Spec Tree**: a git-native product structure where every node co-locates a spec, its tests, and evidence that they match.

The Spec Tree is a **durable map** of your product. Nothing moves because work is "done" — specs are permanent truth. Status is derived from tests, not labels. Context is deterministic: the tree path defines exactly what an agent sees.

![Bootstrapping a spec tree — Claude interviews you about your product's scope](https://raw.githubusercontent.com/outcomeeng/claude/main/assets/tutorial/bootstrap/60-boostrap-02-questionnaire-02.png)

## Get started

```bash
# Install the spx CLI
npm install -g @outcomeeng/spx

# Add the plugin marketplace to Claude Code
claude plugin marketplace add outcomeeng/claude

# Install the Spec Tree plugin
claude plugin install spec-tree@outcomeeng

# Bootstrap your first spec tree
> /bootstrap
```

## Repositories

### CLI

| Repository | Purpose | Install |
| ---------- | ------- | ------- |
| [spx](https://github.com/outcomeeng/spx) | Developer tool for spec-driven development | `npm install -g @outcomeeng/spx` |

### Claude Code

| Repository | Purpose | Install |
| ---------- | ------- | ------- |
| [claude](https://github.com/outcomeeng/claude) | Plugin marketplace — all plugins below | `claude plugin marketplace add outcomeeng/claude` |

Individual plugins: `claude plugin install spec-tree@outcomeeng`, `python@outcomeeng`, `typescript@outcomeeng`, `prose@outcomeeng`, `claude@outcomeeng`

### Other AI agents

Skills distributed as standalone repositories, compatible with any agent that supports the [Agent Skills](https://vercel.com/docs/agent-resources/skills) open standard.

| Repository | Purpose | Install |
| ---------- | ------- | ------- |
| [spec-tree](https://github.com/outcomeeng/spec-tree) | Spec-tree skills for spec-driven development | `npx skills add outcomeeng/spec-tree` |
| [python](https://github.com/outcomeeng/python) | Python engineering skills | `npx skills add outcomeeng/python` |
| [typescript](https://github.com/outcomeeng/typescript) | TypeScript engineering skills | `npx skills add outcomeeng/typescript` |
| [foundation](https://github.com/outcomeeng/foundation) | Foundation skills (prose, plugin development, frontend) | `npx skills add outcomeeng/foundation` |

## Links

- [outcome.engineering](https://outcome.engineering) — methodology and documentation
- [docs.prompts.ag/guidelines](https://docs.prompts.ag/guidelines) — prompting guidelines
