# Claude Config

A reusable Claude configuration toolkit that provides standardized commands and settings across all your projects. This repository contains battle-tested Claude configurations that enhance productivity and maintain consistency.

> [!WARNING]
> This repository is designed for my personal projects and reflects my specific preferences and workflows. It's recommended to fork or copy this repository and customize the commands and rules based on your own needs.

## Setup

We use Git subtrees to share configuration across repositories. Subtrees merge the configuration directly into your project with no complex workflows.

### Initial Setup

Add this configuration to any existing project:

```bash
# Add the claude-config as a subtree in your project
git subtree add --prefix=claude-config https://github.com/jpetitcolas/claude-config.git main --squash

# Create a symbolic link from claude-config to .claude for Claude Code to recognize it
ln -s claude-config .claude

# Commit both the subtree addition and the symbolic link
git add .claude
git commit -m "Add Claude configuration via subtree"
```

### Updating Configuration

When this repository gets updates, sync them to your project:

```bash
# Pull latest changes from claude-config
git subtree pull --prefix=claude-config https://github.com/jpetitcolas/claude-config.git main --squash
```

### Why Subtrees?

Git subtrees provide several benefits:
- No extra configuration files cluttering your repo
- Configuration is immediately available after clone
- No special commands for team members to learn
- Maintains unified project history

## Commands

| Command | Description |
|---------|-------------|
| `/retrospective` | Analyzes recent work and suggests improvements for CLAUDE.md guidelines |

