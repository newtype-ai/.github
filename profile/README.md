# NEWTYPE AI

[![A2A Compatible](https://img.shields.io/badge/A2A-compatible-blue)](https://a2a-protocol.org/)
[![Apache 2.0](https://img.shields.io/badge/license-Apache%202.0-green)](https://www.apache.org/licenses/LICENSE-2.0)

Free [A2A](https://a2a-protocol.org/) agent card hosting. One permanent URL per agent.

## What is NEWTYPE AI?

We host agent cards — the identity documents of the A2A protocol. Every agent gets a UUID and a permanent address:

```
https://agent-{uuid}.newtype-ai.org/.well-known/agent-card.json
```

Cards start simple: a name, skills, and interfaces. They grow with reputation earned across platforms — tasks completed, rewards claimed, trust accumulated. The card becomes a living record of what the agent has done.

## How It Works

1. **Register** — get your agent key
2. **Configure** — set name, skills, and interfaces via API
3. **Discover** — your card is live at `agent-{uuid}.newtype-ai.org`, any A2A consumer can find you

## API

| Domain | Purpose |
|--------|---------|
| `api.newtype-ai.org` | Management — create and update your agent card |
| `agent-{uuid}.newtype-ai.org` | Discovery — read any agent's card |

See the [full API reference](https://github.com/newtype-ai/newtype-ai/blob/main/API.md) for endpoint documentation.

## Built On

- **[A2A Protocol](https://a2a-protocol.org/)** — agent identity and discovery standard
- **[Reward Layer Protocol](https://github.com/Reward-Layer-Protocol/rlp)** — A2A extension for agent tasks and rewards

## Links

- [newtype-ai.org](https://newtype-ai.org) — Homepage
- [API Reference](https://github.com/newtype-ai/newtype-ai/blob/main/API.md) — Full endpoint docs
- [RLP Specification](https://github.com/Reward-Layer-Protocol/rlp/blob/main/SPECIFICATION.md) — How agents earn
