# 📋 PRD Generator

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Claude Code Compatible](https://img.shields.io/badge/Claude%20Code-Compatible-blue)](https://code.claude.com)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](CONTRIBUTING.md)

**From one-line idea to professional PRD in seconds.** 🚀

A Claude Code Skill that transforms your product ideas into structured, professional Product Requirement Documents (PRD). Perfect for product managers, founders, and development teams.

[English](#english) | [中文](#中文)

---

## English

### ✨ Features

- **🧠 Intelligent Requirement Clarification** - Automatically identifies missing information and asks the right questions
- **📝 Professional PRD Structure** - Industry-standard format covering all essential sections
- **🎯 Priority-Driven** - MVP-focused with clear P0/P1/P2 prioritization
- **📊 Data-Ready** - Includes data models, tracking plans, and metrics
- **🔄 Industry Adaptation** - Auto-adjusts focus based on product type (B2C, B2B, Platform, AI, Hardware)

### 🚀 Quick Start

#### Installation

```bash
# Clone the skill
git clone https://github.com/le700/prd-generator-skill.git

# Copy to your Claude Code skills directory
cp -r prd-generator-skill ~/.claude/skills/prd-generator
```

#### Usage

In Claude Code, simply call:

```
/prd-generator [Product Name] [Core Feature Description]
```

**Examples:**
```
/prd-generator SmartExpense Auto-categorize expenses with AI
/prd-generator AIResumeOptimizer Tailor resumes to job descriptions
/prd-generator TeamCollab Cross-department project management
```

### 📁 Project Structure

```
prd-generator/
├── SKILL.md                    # Main skill definition
├── README.md                   # This file
├── LICENSE                     # MIT License
├── CONTRIBUTING.md             # Contribution guidelines
├── templates/
│   └── prd-template.md         # Complete PRD template
└── examples/
    └── sample-prd.md           # Example: Smart Expense Tracker
```

### 📋 PRD Output Structure

| Section | Description |
|---------|-------------|
| Executive Summary | Vision, core metrics |
| Product Overview | Positioning, target users, business model |
| Functional Requirements | Feature list, user stories, acceptance criteria |
| Non-Functional Requirements | Performance, security, compatibility |
| Data Requirements | Data models, tracking plan |
| Interaction Design | Information architecture, key flows |
| Release Plan | Milestones, rollout strategy |
| Risk Management | Risk register, dependencies |

### 🎯 Quality Checklist

Every generated PRD includes a built-in quality check:
- [ ] Clear product positioning?
- [ ] Specific, reachable target users?
- [ ] Complete feature list with priorities?
- [ ] Well-formed user stories?
- [ ] Testable acceptance criteria?
- [ ] Quantified non-functional requirements?
- [ ] Identified risks with mitigation?

---

## 中文

### ✨ 功能特点

- **🧠 智能需求澄清** — 自动识别缺失信息，提出关键问题
- **📝 专业PRD结构** — 行业标准格式，覆盖所有核心章节
- **🎯 优先级驱动** — MVP优先，清晰的P0/P1/P2分级
- **📊 数据就绪** — 包含数据模型、埋点方案、核心指标
- **🔄 行业适配** — 根据产品类型自动调整侧重点（C端/B端/平台/AI/硬件）

### 🚀 快速开始

#### 安装

```bash
# 克隆技能
git clone https://github.com/le700/prd-generator-skill.git

# 复制到 Claude Code 技能目录
cp -r prd-generator-skill ~/.claude/skills/prd-generator
```

#### 使用方法

在 Claude Code 中调用：

```
/prd-generator [产品名称] [核心功能简述]
```

**示例：**
```
/prd-generator 智能记账App 自动识别消费记录并分类
/prd-generator AI简历优化工具 根据JD自动优化简历内容
/prd-generator 企业协作平台 跨部门项目管理和即时通讯
```

### 📋 PRD 输出结构

| 章节 | 内容 |
|------|------|
| 执行摘要 | 产品愿景、核心指标 |
| 产品概述 | 定位、目标用户、商业模式 |
| 功能需求 | 功能列表、用户故事、验收标准 |
| 非功能需求 | 性能、安全、兼容性 |
| 数据需求 | 数据模型、埋点方案 |
| 交互设计 | 信息架构、关键流程 |
| 发布计划 | 里程碑、灰度策略 |
| 风险管理 | 风险登记、外部依赖 |

### 🎯 质量检查清单

每个生成的PRD都包含内置质量检查：
- [ ] 产品定位是否清晰明确？
- [ ] 目标用户是否具体可触达？
- [ ] 功能列表是否完整且有优先级？
- [ ] 用户故事是否符合规范格式？
- [ ] 验收标准是否可测试？
- [ ] 非功能需求是否量化？
- [ ] 风险是否被识别和评估？

---

## 🤝 Contributing

We welcome contributions! See [CONTRIBUTING.md](CONTRIBUTING.md) for guidelines.

### Ways to Contribute
- 🐛 Report bugs or suggest features
- 📝 Improve documentation
- 🔧 Add new templates or examples
- 🌐 Help with translations

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- Inspired by best practices from top tech companies
- Built for the [Claude Code](https://code.claude.com) ecosystem
- Follows the [Agent Skills Open Standard](https://agentskills.io/)

---

**Made with ❤️ for product managers and founders**
