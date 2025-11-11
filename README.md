# NORRIQ Commerce Plugins Marketplace

Official plugin marketplace for the NORRIQ Commerce department.

## Available Plugins

### norriq-commerce-agents (v0.1.0)
Commerce department code review agents (Bouncer & Sherlock)

**Repository:** https://norriq.visualstudio.com/Team%20Ecommerce/_git/NORRIQ.Commerce.Agents

## Installation

Add this marketplace to Claude Code:

```bash
/plugin marketplace add git+https://norriq.visualstudio.com/Team%20Ecommerce/_git/NORRIQ.Claude.Marketplace
```

Then browse and install plugins:

```bash
/plugin install norriq-commerce-agents@norriq-commerce-marketplace
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
