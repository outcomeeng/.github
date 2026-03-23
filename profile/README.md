# Outcome Engineering

AI-assisted development produces code fast — but without structure, that code drifts from requirements, violates decisions, and accumulates rework. Outcome Engineering fixes this with a **Spec Tree**: a git-native product structure where every node co-locates a spec, its tests, and evidence that they match.

The Spec Tree is a **durable map** of your product. Nothing moves because work is "done" — specs are permanent truth. Status is derived from tests, not labels. Context is deterministic: the tree path defines exactly what an agent sees.

![Bootstrapping a spec tree — Claude interviews you about your product's scope](https://raw.githubusercontent.com/outcomeeng/claude/main/assets/tutorial/bootstrap/60-boostrap-02-questionnaire-02.png)

## Get started

```bash
# Add the plugin marketplace to Claude Code
claude plugin marketplace add outcomeeng/claude

# Install the Spec Tree plugin
claude plugin install spec-tree@outcomeeng

# Bootstrap your first spec tree
> /bootstrap
```

## Repositories

| Repository | Purpose |
| ---------- | ------- |
| [claude](https://github.com/outcomeeng/claude) | Plugin marketplace — spec-tree skills, language plugins, prose, testing |
| [spec-tree](https://github.com/outcomeeng/spec-tree) | Distributed spec-tree skills (auto-synced from marketplace) |
| [python](https://github.com/outcomeeng/python) | Distributed Python engineering skills |
| [typescript](https://github.com/outcomeeng/typescript) | Distributed TypeScript engineering skills |
| [foundation](https://github.com/outcomeeng/foundation) | Distributed foundation skills (prose, plugin development, frontend) |

## Links

- [outcome.engineering](https://outcome.engineering) — methodology and documentation
- [docs.prompts.ag/guidelines](https://docs.prompts.ag/guidelines) — prompting guidelines
