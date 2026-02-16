# Constellize Marketplace

Official Constellize methodology plugins for Claude Code.

## Overview

This marketplace provides the complete Constellize methodology as Claude Code plugins:
- **69 Skills** - Prompts become slash commands (`/establish-memory-bank`)
- **12 Agents** - Personas become expert consultants (`@system-architect`)

## Installation

Add this marketplace to Claude Code:

```bash
/plugin marketplace add constellize/marketplace
```

Then install individual plugins:

```bash
/plugin install constellize-memory-bank
/plugin install constellize-architecture
```

## Available Plugins

| Plugin | Description | Skills | Agents |
|--------|-------------|--------|--------|
| constellize-planning | Planning and requirements skills and agents for software projects | ✓ | ✓ |
| constellize-architecture | Architecture and design skills and agents | ✓ | ✓ |
| constellize-quality | Quality gates, testing, and health check skills and agents | ✓ | ✓ |
| constellize-deployment | Deployment and operations skills and agents | ✓ | ✓ |
| constellize-development | Software development agents | ✓ | ✓ |
| constellize-excellence | Continuous excellence and maintenance skills | ✓ | ✓ |
| constellize-ai-workflow | AI-assisted development and review skills | ✓ | ✓ |
| constellize-memory-bank | Memory bank establishment, maintenance, and recovery skills | ✓ | ✓ |
| constellize-operations | Operational knowledge and incident management skills | ✓ | ✓ |
| constellize-organization | Organizational knowledge discovery and management skills | ✓ | ✓ |
| constellize-learning | Team and personal learning skills | ✓ | ✓ |
| constellize-evolution | System evolution and health tracking skills | ✓ | ✓ |
| constellize-adoption | Team onboarding and adoption skills | ✓ | ✓ |

## Usage

### Skills (Prompts)

Skills are invoked with slash commands:

```
/establish-memory-bank "My Project"
/constellation-map
/write-unit-tests
```

### Agents (Personas)

Agents are invoked with @ mentions:

```
@system-architect review this architecture
@qa-engineer what test cases am I missing?
@devops-engineer how should I deploy this?
```

### Combined Usage

Combine skills with agents for expert-guided execution:

```
@system-architect /constellation-map
```

## Source

This marketplace is generated from [prompt-factory](https://github.com/constellize/prompt-factory), which serves as the single source of truth for all Constellize prompts and personas.

## License

MIT
