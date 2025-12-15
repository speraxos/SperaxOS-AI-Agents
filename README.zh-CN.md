# 🤖 AI 智能体库

> **适用于 DeFi、加密货币、开发等领域的通用 AI 智能体市场**

包含 505+ 个专业 AI 智能体的综合集合，具有通用兼容性。适用于任何支持智能体索引的 AI 平台 - 无供应商锁定，无平台限制。

[![][agents-shield]][agents-url]
[![][build-shield]][build-url]
[![][contributors-shield]][contributors-url]
[![][forks-shield]][forks-url]
[![][stargazers-shield]][stargazers-url]
[![][issues-shield]][issues-url]
[![][license-shield]][license-url]

[agents-shield]: https://img.shields.io/badge/智能体-505%2B-blue
[agents-url]: #-智能体分类
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

## ✨ 核心特性

- ✅ **505+ 专业智能体** - 涵盖 DeFi、加密货币、开发、写作、教育等领域
- ✅ **18 种语言** - 自动化国际化翻译工作流
- ✅ **智能体团队** - 协调工作流的多智能体协作
- ✅ **通用格式** - 标准 JSON 架构适用于所有平台
- ✅ **无供应商锁定** - 切换平台不会丢失工作成果
- ✅ **开源** - MIT 许可证，完全透明
- ✅ **API 访问** - 通过 GitHub Pages CDN 提供 RESTful API
- ✅ **支持自定义域名** - 轻松实现白标化

---

## 🚀 快速开始

### 对于用户

将智能体添加到您的 AI 平台：
```
https://nirholas.github.io/AI-Agents-Library/index.json
```

### 对于开发者

```bash
git clone https://github.com/nirholas/AI-Agents-Library.git
cd AI-Agents-Library
npm install
npm run build
```

---

## 📦 智能体分类

### 🪙 DeFi 和加密货币（50 个专业智能体）

**Sperax 生态系统：**
- USDs 稳定币专家、SPA 代币经济分析师、veSPA 锁仓优化器
- 治理指南、流动性策略师、跨链桥助手
- 收益聚合器、风险监控、入门指南、投资组合追踪器

**通用 DeFi：**
- 收益农业优化器、无常损失计算器、Gas 优化器
- 智能合约审计师、MEV 保护顾问、巨鲸观察者
- 协议对比器、代币解锁追踪器、清算风险管理器
- 以及 30+ 个 DeFi 专家

### 💻 开发与编程
- 全栈开发者、Rust 助手、TypeScript 架构师
- 智能合约审计师、API 文档编写者、代码质量优化器
- Git 专家、数据库设计师、测试自动化专家

### ✍️ 内容与写作
- 学术写作助手、技术文档专家、UX 文案撰写者
- SEO 内容优化器、社交媒体经理、商务邮件撰写者
- 翻译专家、校对专家

### 📊 商业与分析
- 商业战略顾问、财务分析师、数据分析师
- 产品经理、市场研究专家、SWOT 分析专家

### 🎓 教育与学习
- 数学导师、语言学习伙伴、STEM 教育者
- 考试准备教练、研究助手

### 🎨 创意与设计
- UI/UX 设计师、Logo 设计专家、平面设计专家
- 色彩理论顾问、排版专家

[查看完整智能体列表 →](https://nirholas.github.io/AI-Agents-Library/)

---

## 🤝 智能体团队

创建专业智能体协作团队，共同处理复杂任务。

**示例团队 - DeFi 策略：**
```
- 收益优化器（寻找机会）
- 风险评估智能体（评估安全性）
- 投资组合追踪器（监控表现）
- Gas 优化器（最小化成本）
```

主持智能体协调讨论，确保每个专家贡献其专业知识，同时朝着全面的解决方案迈进。

[阅读团队指南 →](./docs/TEAMS.md)

---

## 🌍 多语言支持

所有智能体自动提供 18 种语言版本：

🇺🇸 English • 🇨🇳 简体中文 • 🇹🇼 繁體中文 • 🇯🇵 日本語 • 🇰🇷 한국어 • 🇩🇪 Deutsch • 🇫🇷 Français • 🇪🇸 Español • 🇷🇺 Русский • 🇸🇦 العربية • 🇵🇹 Português • 🇮🇹 Italiano • 🇳🇱 Nederlands • 🇵🇱 Polski • 🇻🇳 Tiếng Việt • 🇹🇷 Türkçe • 🇸🇪 Svenska • 🇮🇩 Bahasa Indonesia

---

## 🛠️ API 参考

### 端点

```bash
# 主索引（所有智能体）
GET https://nirholas.github.io/AI-Agents-Library/index.json

# 单个智能体（英文）
GET https://nirholas.github.io/AI-Agents-Library/{agent-id}.json

# 本地化智能体
GET https://nirholas.github.io/AI-Agents-Library/{agent-id}.zh-CN.json

# 特定语言索引
GET https://nirholas.github.io/AI-Agents-Library/index.zh-CN.json
```

### 快速集成

```javascript
// 加载所有智能体
const response = await fetch('https://nirholas.github.io/AI-Agents-Library/index.json');
const { agents } = await response.json();

// 加载特定智能体
const agent = await fetch(`https://nirholas.github.io/AI-Agents-Library/defi-yield-optimizer.json`);
const agentConfig = await agent.json();
```

[完整 API 文档 →](./docs/API.md)

---

## 🤖 贡献智能体

我们欢迎贡献！提交您的智能体以扩展库。

### 快速提交

1. **Fork 此仓库**
2. **在 `src/your-agent-name.json` 中创建您的智能体**

```json
{
  "author": "your-github-username",
  "identifier": "your-agent-name",
  "meta": {
    "title": "智能体标题",
    "description": "清晰简洁的描述",
    "avatar": "🤖",
    "tags": ["类别", "功能", "领域"]
  },
  "schemaVersion": 1,
  "config": {
    "systemRole": "你是一个在[领域]方面具有专业知识的[角色]..."
  }
}
```

3. **提交 Pull Request**

我们的自动化工作流将把您的智能体翻译成 18 种语言并全球部署。

### 质量指南

✅ 明确的目的 - 解决特定问题  
✅ 结构良好的提示 - 全面但专注  
✅ 适当的标签 - 有助于发现  
✅ 经过测试 - 验证功能  

[完整贡献指南 →](./docs/CONTRIBUTING.md)

---

## 📖 文档

### 对于用户
- [智能体团队指南](./docs/TEAMS.md) - 多智能体协作
- [常见问题](./docs/FAQ.md) - 常见问题
- [示例](./docs/EXAMPLES.md) - 实际用例

### 对于开发者
- [API 参考](./docs/API.md) - 完整的 API 文档
- [智能体创建指南](./docs/AGENT_GUIDE.md) - 设计有效的智能体
- [提示工程](./docs/PROMPTS.md) - 编写更好的提示
- [模型参数](./docs/MODELS.md) - Temperature、top_p 说明
- [故障排除](./docs/TROUBLESHOOTING.md) - 常见问题

---

## 🚀 部署

### GitHub Pages（自动）

1. 在仓库设置中启用 GitHub Pages
2. 将源分支设置为 `gh-pages`
3. 推送到 main - GitHub Actions 处理部署

智能体地址：`https://[username].github.io/[repository]/index.json`

### 自定义域名

1. 添加包含您域名的 `CNAME` 文件
2. 配置 DNS：`CNAME` → `[username].github.io`
3. 在仓库设置中启用 HTTPS

[完整部署指南 →](./docs/DEPLOYMENT.md)

---

## 🔧 开发工具

### 拆分智能体批次
```bash
node split-agents.cjs
```
将批量 JSON 转换为单独的智能体文件。

### Emoji 转换器
```bash
node emoji-converter.cjs
```
将 emoji URL 转换为原生 Unicode。



---

## 🌐 集成示例

### 自定义应用
```javascript
// 获取智能体
const agents = await fetch('https://nirholas.github.io/AI-Agents-Library/index.json')
  .then(r => r.json());

// 与您的 AI 模型一起使用
const systemPrompt = agents.agents[0].config.systemRole;
```

### Python
```python
import requests

# 加载智能体
response = requests.get('https://nirholas.github.io/AI-Agents-Library/index.json')
agents = response.json()['agents']

# 按标签过滤
defi_agents = [a for a in agents if 'defi' in a['meta']['tags']]
```

---

## 🔐 安全与隐私

- **无数据收集** - 静态 JSON 索引，零跟踪
- **智能体本地运行** - 在您的 AI 平台环境中执行
- **开源** - 完全透明，审计每一行
- **无外部调用** - 纯 JSON 配置文件

---

## 📊 统计数据

- **505+ 智能体** - 全面覆盖
- **18 种语言** - 全球可访问性
- **50 个 DeFi 专家** - 专注区块链
- **~200 KB 索引** - 快速加载（gzip 压缩：~45 KB）
- **80-120ms** - 全球 CDN 交付
- **0 供应商锁定** - 真正的互操作性

---

## 🔗 相关项目

- **SperaxOS** - [应用分支](https://github.com/nirholas/AI-Agents-Library/tree/speraxos)
---

## 📜 许可证

MIT 许可证 - 详见 [LICENSE](LICENSE) 文件。

**开源 • 开放格式 • 开放未来**

---

## 🙏 致谢

---

<div align="center">

**[查看智能体 →](https://nirholas.github.io/AI-Agents-Library/) | [提交智能体 →](https://github.com/nirholas/AI-Agents-Library/issues/new) | [阅读文档 →](./docs/)**

用 ❤️ 为 AI 社区打造

</div>
