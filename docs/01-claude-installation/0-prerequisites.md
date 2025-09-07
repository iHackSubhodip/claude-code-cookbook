# 📋 Prerequisites

> **Intent**: Quick system check - ensure you have what's needed before installing Claude Code

## System Requirements
- **Node.js 18+**
- **Internet connection**
- **macOS 10.15+ | Ubuntu 20.04+ | Windows 10+ (WSL)**

## Quick Check
```bash
node --version  # Should show 18+
npm --version   # Should work
curl -I https://api.anthropic.com  # Should return 200
```

## Install Node.js (if needed)
```bash
# macOS
brew install node

# Ubuntu/Debian  
curl -fsSL https://deb.nodesource.com/setup_lts.x | sudo -E bash -
sudo apt-get install -y nodejs

# Windows
# Download from nodejs.org or use WSL
```

---

**Ready?** → [Install Claude Code](1-README.md)