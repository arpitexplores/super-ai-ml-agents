# Super AI/ML Agents

<!-- super-series-intro -->
> AI agent architecture skill for tools, memory, orchestration, multi-agent patterns, autonomy, and guardrails.

[View the full SUPER Skills catalogue](https://github.com/arpitexplores/skills-super).
<!-- /super-series-intro -->

Design reliable agent systems with explicit scope, tools, memory, orchestration, and human approval boundaries.

## Install

Copy this folder into your agent's skills directory, then restart or reload the agent.

```bash
cp -R super-ai-ml-agents ~/.your-agent/skills/
```

Use it by name:

```text
Use $super-ai-ml-agents to help with this request.
```

## Best For

- agent architecture
- multi-agent patterns
- memory design
- tooling and permissions
- validation scenarios

## Outputs

- agent behaviour contract
- tooling plan
- memory architecture
- orchestration pattern
- validation plan

## Modules

| Module | Purpose |
| --- | --- |
| `agent-memory-systems.md` | Short-term, long-term, retrieval, and bounded memory design for agents |
| `ai-agents-architect.md` | Agent scope, tools, permissions, orchestration, and production architecture |
| `multi-agent-patterns.md` | Supervisor, specialist, handoff, critique, and parallel multi-agent patterns |

## Example Prompts

- `Use $super-ai-ml-agents to design a support agent with tool access.`
- `Use $super-ai-ml-agents to review this multi-agent architecture.`
- `Use $super-ai-ml-agents to define memory and guardrails for an autonomous workflow.`

## Package Contents

- `SKILL.md` is the installable skill entry point.
- `references/modules/` contains detailed workflows loaded only when needed.
- `agents/` contains optional agent metadata where supported.
- `scripts/` and `assets/` are optional helpers when bundled.

## Compatibility

This skill is plain Markdown and is intended to be agent-agnostic. If a bundled helper mentions a specific tool path, translate that instruction to the equivalent path for your environment.

## SUPER Skills Series

This repository is part of the **SUPER Skills** series: standalone, installable agent skills that can be used independently or together.

### Published Series Repositories

| Repository | Purpose |
| --- | --- |
| [skills-super](https://github.com/arpitexplores/skills-super) | Master catalogue for the full SUPER Skills collection. |
| [super-seo-growth](https://github.com/arpitexplores/super-seo-growth) | SEO growth, AI/GEO visibility, content optimisation, and programmatic SEO. |
| [super-seo-foundation](https://github.com/arpitexplores/super-seo-foundation) | Technical SEO audits, schema, indexing, sitemaps, hreflang, and tooling. |
| [super-marketing-execution](https://github.com/arpitexplores/super-marketing-execution) | Campaign orchestration, copywriting, CRO, analytics, email, social, and paid ads. |
| [super-design-core](https://github.com/arpitexplores/super-design-core) | UI/UX, product design, IA, flows, visual systems, and UI patterns. |
| [super-ai-ml-agents](https://github.com/arpitexplores/super-ai-ml-agents) | Agent architecture, tools, memory, orchestration, and multi-agent patterns. |

Start with the skill that matches the task. Use the catalogue when you want to browse the full collection or install multiple skills.

## Version

See `VERSION` and `CHANGELOG.md`.

## Licence

MIT. See the root repository `LICENSE`.
