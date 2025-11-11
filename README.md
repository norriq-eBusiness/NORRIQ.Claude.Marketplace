# NORRIQ Claude Marketplace

Official Claude Code plugin marketplace for NORRIQ.

## Available Plugins

### norriq-commerce-agents (v0.2.0)
Commerce department code review agents (Bouncer, Sherlock, Karen)

**Repository:** https://github.com/norriq-eBusiness/NORRIQ.Commerce.Agents

## Installation

Add this marketplace to Claude Code:

```bash
/plugin marketplace add norriq-eBusiness/NORRIQ.Claude.Marketplace
```

Then browse and install plugins:

```bash
/plugin install norriq-commerce-agents@norriq-claude-marketplace
```

## For Maintainers

### Adding New Plugins

1. Add plugin entry to `.claude-plugin/marketplace.json`
2. Update this README
3. Commit and push

### Marketplace Structure

```json
{
  "name": "plugin-name",
  "source": {
    "type": "git",
    "url": "plugin-git-repo-url"
  },
  "description": "Plugin description",
  "version": "x.x.x",
  "author": {
    "name": "Author Name"
  }
}
```
