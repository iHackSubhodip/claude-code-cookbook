# 📦 Claude Code Installation

> **Intent**: Get Claude Code installed and running in under 5 minutes with minimal commands

## Prerequisites
```bash
node --version  # Need 18+ (this is like the engine Claude Code runs on)
# Should show: v18.x.x or v20.x.x ✓
```

## Install
```bash
npm install -g @anthropic-ai/claude-code
# This downloads and installs Claude Code globally
# The -g means you can use 'claude' command anywhere
```

## Verify Installation Worked
```bash
claude --version
# Should show: claude-code v1.x.x ✓

claude doctor  
# Should show: All systems operational ✓
```

## First Run
```bash
# Go to any folder with code (or create a new one)
cd my-calculator-app
# OR create new folder: mkdir hello-world && cd hello-world

claude
# This starts Claude Code in your current folder
# A browser will open asking you to log in
# Choose "Claude Pro/Max" if you have a subscription
```

## Common Issues

**Permission error?**
```bash
npm config set prefix ~/.npm-global
export PATH=~/.npm-global/bin:$PATH
```

**Node.js too old?**
```bash
nvm install --lts
nvm use --lts
```

**Windows?**
```bash
# Use WSL
wsl --install
```

## Installation Flow

![Claude Code Installation Flow](2-claude_installation.png)

---

**Next:** → [Configuration Prerequisites](../02-claude-configuration/0-prerequisites.md)
