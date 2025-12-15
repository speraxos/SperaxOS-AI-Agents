# 🤖 AI Agents Library

> **Universal AI agent library, index, and marketplace for DeFi, crypto, development, metaverse, MCP, and beyond**

A comprehensive collection of specialized AI agents with universal compatibility. Works with any AI platform that supports agent indexes - no vendor lock-in, no platform restrictions.

[![][agents-shield]][agents-url]
[![][build-shield]][build-url]
[![][contributors-shield]][contributors-url]
[![][forks-shield]][forks-url]
[![][stargazers-shield]][stargazers-url]
[![][issues-shield]][issues-url]
[![][license-shield]][license-url]

[agents-shield]: https://img.shields.io/badge/agents-505%2B-blue
[agents-url]: #-agent-categories
[build-shield]: https://github.com/nirholas/AI-Agents-Library/workflows/Release/badge.svg
[build-url]: https://github.com/nirholas/AI-Agents-Library/actions
[contributors-shield]: https://img.shields.io/github/contributors/nirholas/AI-Agents-Library.svg
[contributors-url]: https://github.com/nirholas/AI-Agents-Library/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/nirholas/AI-Agents-Library.svg
[forks-url]: https://github.com/nirholas/AI-Agents-Library/network/members
[stargazers-shield]: https://img.shields.io/github/stars/nirholas/AI-Agents-Library.svg
[stargazers-url]: https://github.com/nirholas/AI-Agents-Library/stargazers
[issues-shield]: https://img.shields.io/github/issues/nirholas/AI-Agents-Library.svg
[issues-url]: https://github.com/nirholas/AI-Agents-Library/issues
[license-shield]: https://img.shields.io/github/license/nirholas/AI-Agents-Library.svg
[license-url]: https://github.com/nirholas/AI-Agents-Library/blob/main/LICENSE

---

## ✨ Key Features

- ✅ **505+ Specialized Agents** - DeFi, crypto, development, writing, education, and more
- ✅ **18 Languages** - Automated i18n translation workflow
- ✅ **Agent Teams** - Multi-agent collaboration with coordinated workflows
- ✅ **Universal Format** - Standard JSON schema works everywhere
- ✅ **No Vendor Lock-in** - Switch platforms without losing work
- ✅ **Open Source** - MIT licensed, fully transparent
- ✅ **API Access** - RESTful API via GitHub Pages CDN
- ✅ **Custom Domain Ready** - Easy white-labeling

---

## 🚀 Quick Start

### For Users

Add agents to your AI platform:
```
https://nirholas.github.io/AI-Agents-Library/index.json
```

### For Developers

```bash
git clone https://github.com/nirholas/AI-Agents-Library.git
cd AI-Agents-Library
npm install
npm run build
```

---

## 📦 Agent Categories

### 🪙 DeFi & Crypto (50 Specialized Agents)

**Sperax Ecosystem:**
- USDs Stablecoin Expert, SPA Tokenomics Analyst, veSPA Lock Optimizer
- Governance Guide, Liquidity Strategist, Bridge Assistant
- Yield Aggregator, Risk Monitor, Onboarding Guide, Portfolio Tracker

**General DeFi:**
- Yield Farming Optimizer, Impermanent Loss Calculator, Gas Optimizer
- Smart Contract Auditor, MEV Protection Advisor, Whale Watcher
- Protocol Comparator, Token Unlock Tracker, Liquidation Risk Manager
- And 30+ more DeFi specialists

### 💻 Development & Programming
- Full-Stack Developer, Rust Assistant, TypeScript Architect
- Smart Contract Auditor, API Documentation Writer, Code Quality Optimizer
- Git Expert, Database Designer, Test Automation Specialist

### ✍️ Content & Writing
- Academic Writing Assistant, Technical Documentation Expert, UX Copywriter
- SEO Content Optimizer, Social Media Manager, Business Email Writer
- Translation Specialist, Proofreading Expert

### 📊 Business & Analysis
- Business Strategy Consultant, Financial Analyst, Data Analyst
- Product Manager, Market Research Specialist, SWOT Analysis Expert

### 🎓 Education & Learning
- Math Tutor, Language Learning Partner, STEM Educator
- Exam Preparation Coach, Research Assistant

### 🎨 Creative & Design
- UI/UX Designer, Logo Design Expert, Graphic Design Specialist
- Color Theory Advisor, Typography Expert

[View Full Agent List →](https://nirholas.github.io/AI-Agents-Library/)

---

## 🤝 Agent Teams

Create collaborative teams of specialized agents that work together on complex tasks.

**Example Team - DeFi Strategy:**
```
- Yield Optimizer (finds opportunities)
- Risk Assessment Agent (evaluates safety)
- Portfolio Tracker (monitors performance)
- Gas Optimizer (minimizes costs)
```

The host agent coordinates discussion, ensuring each specialist contributes their expertise while building toward a comprehensive solution.

[Read Teams Guide →](./docs/TEAMS.md)

---

## 🌍 Multi-Language Support

All agents automatically available in 18 languages:

🇺🇸 English • 🇨🇳 简体中文 • 🇹🇼 繁體中文 • 🇯🇵 日本語 • 🇰🇷 한국어 • 🇩🇪 Deutsch • 🇫🇷 Français • 🇪🇸 Español • 🇷🇺 Русский • 🇸🇦 العربية • 🇵🇹 Português • 🇮🇹 Italiano • 🇳🇱 Nederlands • 🇵🇱 Polski • 🇻🇳 Tiếng Việt • 🇹🇷 Türkçe • 🇸🇪 Svenska • 🇮🇩 Bahasa Indonesia

---

## 🛠️ API Reference

### Endpoints

```bash
# Main index (all agents)
GET https://nirholas.github.io/AI-Agents-Library/index.json

# Individual agent (English)
GET https://nirholas.github.io/AI-Agents-Library/{agent-id}.json

# Localized agent
GET https://nirholas.github.io/AI-Agents-Library/{agent-id}.zh-CN.json

# Language-specific index
GET https://nirholas.github.io/AI-Agents-Library/index.zh-CN.json
```

### Quick Integration

```javascript
// Load all agents
const response = await fetch('https://nirholas.github.io/AI-Agents-Library/index.json');
const { agents } = await response.json();

// Load specific agent
const agent = await fetch(`https://nirholas.github.io/AI-Agents-Library/defi-yield-optimizer.json`);
const agentConfig = await agent.json();
```

[Full API Documentation →](./docs/API.md)

---

## 🤖 Contributing an Agent

We welcome contributions! Submit your agent to expand the library.

### Quick Submit

1. **Fork this repository**
2. **Create your agent** in `src/your-agent-name.json`

```json
{
  "author": "your-github-username",
  "identifier": "your-agent-name",
  "meta": {
    "title": "Agent Title",
    "description": "Clear, concise description",
    "avatar": "🤖",
    "tags": ["category", "functionality", "domain"]
  },
  "schemaVersion": 1,
  "config": {
    "systemRole": "You are a [role] with expertise in [domain]..."
  }
}
```

3. **Submit a Pull Request**

Our automated workflow will translate your agent to 18 languages and deploy it globally.

### Quality Guidelines

✅ Clear purpose - solves a specific problem  
✅ Well-structured prompts - comprehensive but focused  
✅ Appropriate tags - aids discovery  
✅ Tested - verified functionality  

[Full Contributing Guide →](./docs/CONTRIBUTING.md)

---

## 📖 Documentation

### For Users
- [Agent Teams Guide](./docs/TEAMS.md) - Multi-agent collaboration
- [FAQ](./docs/FAQ.md) - Common questions
- [Examples](./docs/EXAMPLES.md) - Real-world use cases

### For Developers
- [API Reference](./docs/API.md) - Complete API documentation
- [Agent Creation Guide](./docs/AGENT_GUIDE.md) - Design effective agents
- [Prompt Engineering](./docs/PROMPTS.md) - Writing better prompts
- [Model Parameters](./docs/MODELS.md) - Temperature, top_p explained
- [Troubleshooting](./docs/TROUBLESHOOTING.md) - Common issues

---

## 🚀 Deployment

### GitHub Pages (Automatic)

1. Enable GitHub Pages in repository settings
2. Set source branch to `gh-pages`
3. Push to main - GitHub Actions handles deployment

Agents live at: `https://[username].github.io/[repository]/index.json`

### Custom Domain

1. Add `CNAME` file with your domain
2. Configure DNS: `CNAME` → `[username].github.io`
3. Enable HTTPS in repository settings

[Full Deployment Guide →](./docs/DEPLOYMENT.md)

---

## 🔧 Development Tools

### Split Agent Batches
```bash
node split-agents.cjs
```
Converts batch JSON into individual agent files.

### Emoji Converter
```bash
node emoji-converter.cjs
```
Converts emoji URLs to native Unicode.



---

## 🌐 Integration Examples

### Custom Application
```javascript
// Fetch agents
const agents = await fetch('https://nirholas.github.io/AI-Agents-Library/index.json')
  .then(r => r.json());

// Use with your AI model
const systemPrompt = agents.agents[0].config.systemRole;
```

### Python
```python
import requests

# Load agents
response = requests.get('https://nirholas.github.io/AI-Agents-Library/index.json')
agents = response.json()['agents']

# Filter by tag
defi_agents = [a for a in agents if 'defi' in a['meta']['tags']]
```

---

## 🔐 Security & Privacy

- **No data collection** - Static JSON index, zero tracking
- **Agents run locally** - Execute in your AI platform's environment
- **Open source** - Full transparency, audit every line
- **No external calls** - Pure JSON configuration files

---

## 📊 Stats

- **505+ Agents** - Comprehensive coverage
- **18 Languages** - Global accessibility
- **50 DeFi Specialists** - Blockchain-focused
- **~200 KB Index** - Fast loading (gzipped: ~45 KB)
- **80-120ms** - Global CDN delivery
- **0 Vendor Lock-in** - True interoperability

---

## 🔗 Projects Building with AI Agents Library 🤍

- **SperaxOS** - [Application Branch](https://github.com/nirholas/AI-Agents-Library/tree/speraxos)
---

## 📜 License

MIT License - see [LICENSE](LICENSE) file for details.

**Open Source • Open Format • Open Future**

---

## 🙏 


---

<div align="center">

**[View Agents →](https://nirholas.github.io/AI-Agents-Library/) | [Submit Agent →](https://github.com/nirholas/AI-Agents-Library/issues/new) | [Read Docs →](./docs/)**

</div>
