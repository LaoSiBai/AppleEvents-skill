<!-- language-selector:start -->
[English](./README.md) | **中文**
<!-- language-selector:end -->

# 🍎 Apple Events Skill

将您平淡无奇的产品发布文案，转化为极具电影感和感染力的“苹果发布会”风格讲稿。

[![License](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)
[![Skill](https://img.shields.io/badge/Agent-Skill-purple.svg)]()

## 关于 (About)

普通的 AI 生成文案总是听起来像机器人，且充满陈词滥调。这个 Skill 会强制 Agent 使用真实的苹果高管节奏、词汇和转场方式进行创作。它完美解决了产品发布文案枯燥乏味的问题，将苹果传奇的“展示，而非告知 (Show, Don't Tell)”哲学和对情绪共鸣的掌控力直接注入你的 AI 工作流。

## 核心特性 (Features)

- **7 条苹果核心叙事哲学**：内置了苹果演讲的终极秘籍，包括“短平快”的断句、“永远正向叙事”以及“全局协同 (Holistic Synergy)”法则。
- **语料库强制溯源**：基于精心整理的 2020-2026 年真实苹果发布会原声语料进行创作。
- **多元化高管 Persona**：可指定 Agent 模仿特定高管的风格。不要只局限于默认组合，尝试更丰富的角色：
  - **Tim Cook**：沉稳的大局观和充满人文关怀的开场。
  - **Craig Federighi**：充满活力的极客幽默，丝滑的软件演示。
  - **Johny Srouji**：硬核、极客，专注于底层芯片架构和极致性能突破。
  - **Sumbul Ahmad Desai**：专业且富有同理心，主讲健康与科学背书。
  - **John Ternus**：充满激情的硬件工程与精密的制造工艺。
  - **Greg "Joz" Joswiak**：极致的旗舰营销词汇与行业霸主气场。
- **多发言人接力编排**：自动生成极其丝滑的舞台交接词和清晰的 Markdown 标记。

## 安装指南 (Installation)

本 Skill 适用于支持标准 `.gemini/skills` 或 `.agents/skills` 目录结构的 Agent。

```bash
git clone https://github.com/YOUR_USERNAME/apple-events-skill.git ~/.agents/skills/apple-events-skill
```

### 环境要求 (Requirements)

- 兼容的 Agentic CLI 或 IDE（例如 antigravity-cli, opencode）。

## 使用说明 (Usage)

安装完成后，直接与您的 Agent 对话即可。提供一份草稿或大纲并触发该技能：

```markdown
这是我们全新 SaaS 平台更新的讲稿草稿。请使用 **apple-events-skill** 帮我重写。让开场听起来像 Tim Cook，功能介绍部分听起来像 Craig Federighi。
```

### 更多示例 (More Examples)

```markdown
请用 **apple-events-skill** 帮我写一份智能咖啡机的新品发布讲稿。重点突出‘全局协同’和‘永远正向叙事’。
```

## 参与贡献 (Contributing)

欢迎任何形式的贡献！如果您想添加新的高管 Persona、使用最新的发布会更新语料库，或者完善 7 条核心哲学，请随时提交 Pull Request。

### 开发设置 (Development Setup)

在本地测试更改：
1. 将仓库克隆到您的本地工作区。
2. 确保 `resources/` 语料库目录完整。
3. 提交 PR 前，请在本地与您的 Agent 进行充分的提示词测试。

## 致谢 (Acknowledgments)

- 演讲语料数据源于 2020-2026 年历届真实的 Apple Events。
- 灵感源自 Steve Jobs, Tim Cook 及苹果高管团队极具魅力的演讲风格。

## 开源协议 (License)

Apple Events Skill 采用 MIT 开源协议。
