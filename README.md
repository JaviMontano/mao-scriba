# Prolipa — Editorial Plugins

Private repository for Prolipa-specific Claude Code plugins.

## Plugins

| Plugin | Description | Status |
|--------|-------------|--------|
| **Scriba** | K-12 editorial content pipeline — curriculum alignment, comprehensibility validation, DUA, teacher guides | Active |

## Structure

```
Prolipa/
└── scriba/          # Editorial content generation plugin
    ├── agents/      # 14 specialized editorial agents
    ├── commands/    # 38 editorial commands
    ├── skills/      # 24 editorial skills
    ├── references/  # Curriculum standards, style guides
    └── hooks/       # Session automation
```

## Usage

Register as a local marketplace in Claude Code:
```bash
claude plugins add-marketplace /Users/deonto/clientes/Prolipa
claude plugins install scriba
```

---
*Confidential — Prolipa client engagement.*
