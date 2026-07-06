# Relux Works — Agent Skills

Public [Agent Skills](https://agentskills.io/) from [Relux Works](https://relux.works),
an AI-native software development studio. Installing the `relux-works` skill teaches your
agent how to look up our services/pricing and submit a real project inquiry (with your
consent) — a human replies within one business day.

## Install

**Hermes Agent** (tap):

```bash
hermes skills tap add relux-works/agent-skills
hermes skills install relux-works
```

**OpenClaw** (ClawHub):

```bash
clawhub install relux-works
```

**Claude Code**:

```bash
git clone https://github.com/relux-works/agent-skills
cp -r agent-skills/skills/relux-works ~/.claude/skills/
```

**Any agent** — the skill is plain markdown per the [agentskills.io](https://agentskills.io/)
standard: [`skills/relux-works/SKILL.md`](skills/relux-works/SKILL.md).

## Discovery endpoints

- ARD catalog: `https://relux.works/.well-known/ai-catalog.json`
- Agent skills index: `https://relux.works/.well-known/agent-skills/index.json`
- MCP server: `https://api.relux.works/mcp` ([server card](https://relux.works/.well-known/mcp/server-card.json))
- REST API: [`https://api.relux.works/docs`](https://api.relux.works/docs)

## License

MIT
