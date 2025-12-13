# Conduit UI Marketplace

Official Claude Code plugins marketplace for the Conduit UI ecosystem.

## Installation

Add a plugin from this marketplace:

```bash
/plugins install <plugin-name>@conduit-ui-marketplace
```

## Available Plugins

| Plugin | Description | Install |
|--------|-------------|---------|
| **review** | Expert PR review system with architecture assessment, pattern learning, and production-readiness validation | `/plugins install review@conduit-ui-marketplace` |

## Plugin Details

### review

Comprehensive parallel PR review system featuring:

- **Architecture Review** - SOLID compliance, design patterns, Laravel conventions
- **Pattern Learning** - Builds codebase-specific knowledge over time
- **Production Readiness** - Security, performance, test coverage checks
- **Parallel Execution** - Multiple specialized agents review simultaneously

[View documentation](https://github.com/conduit-ui/review)

## Adding New Plugins

To add a plugin to this marketplace:

1. Create a repo with `.claude-plugin/plugin.json`
2. Add agents in `agents/` directory
3. Add commands in `commands/` directory (optional)
4. Submit PR to add entry to `marketplace.json`

## Related

- [Conduit UI](https://github.com/conduit-ui/conduit-ui) - Main CLI tool
- [Conduit Core](https://github.com/conduit-ui/core) - Shared functionality

## License

MIT
