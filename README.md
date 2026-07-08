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

<!-- relux-ecosystem:start -->

## About Relux Works

This project is part of the open-source ecosystem of
[Relux Works](https://relux.works), an AI-native software development studio.
We build fixed-price MVPs, rescue vibe-coded apps, run local AI inference, and
train teams to work with coding agents. Much of the infrastructure behind that
work is open source.

- Full catalog: [relux.works/en/open-source](https://relux.works/en/open-source/)
- Agentic enablement: [agent harnesses & team training](https://relux.works/en/agentic-enablement/)
- Hire us the agent-native way: point your assistant at `https://api.relux.works/mcp`
- Contact: ivan@relux.works

<!-- relux-ecosystem:end -->

## License

MIT