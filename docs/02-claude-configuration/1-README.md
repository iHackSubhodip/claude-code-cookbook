# ⚙️ Claude Code Configuration

> **Intent**: Configure authentication and project context in 3 steps

## First Time Setup
```bash
cd your-project
claude
# Follow prompts to choose login method
```

## Authentication Options
**Option 1: Claude Pro/Max** (Recommended)
- Choose option 1
- Browser opens for login

**Option 2: Anthropic Console**
- Choose option 2  
- Enter API key when prompted

## Trust Project Files
```bash
# When prompted "Do you trust the files in this folder?"
# Choose: 1. Yes, proceed
```

## Create Project Context (Optional)
```bash
# Create CLAUDE.md for better context
echo "## Project Overview
[Brief description]

## Tech Stack  
- Language: [your language]
- Framework: [your framework]" > CLAUDE.md
```

## Configuration Flow

![Claude Code Configuration Flow](2-claude_setup.png)

---

**Next:** → [Bootstrap Prerequisites](../03-bootstrap-project/0-prerequisites.md)