# AI 技能系统配置文档

> 本文档定义了 AI 助手的完整技能配置，包括 MCP 服务器和 Skills 技能库。
> 更新日期: 2026-02-19

---

## 一、技能清单

### 1. MCP 服务器

#### 已安装
| 名称 | 功能描述 | 安装命令 |
|------|---------|---------|
| context7 | 代码理解与分析 | npx -y @upstash/context7-mcp@latest |
| Exa | AI专用搜索引擎 | npx -y exa-mcp-server |
| GitHub | GitHub仓库管理 | npx -y @modelcontextprotocol/server-github |
| 印象笔记 | 笔记保存和搜索 | npx yxbj-mcp |
| 股票查询 | A股实时行情 | 内置服务 |

#### 推荐安装
| 名称 | 功能描述 | 效率提升 |
|------|---------|---------|
| Playwright | 浏览器自动化 | 网页操作自动化 |
| Sequential-Thinking | 结构化思考 | 复杂问题分解 |
| Memory | 持久化记忆 | 跨会话记忆 |
| Filesystem | 文件系统操作 | 文件管理自动化 |
| Puppeteer | 网页自动化 | 数据抓取 |
| Slack | 团队消息 | 自动通知 |
| Google-Calendar | 日程管理 | 会议安排 |
| PostgreSQL | 数据库操作 | 数据分析 |
| SQLite | 本地数据库 | 轻量级数据管理 |
| Docker | 容器管理 | 环境隔离 |

### 2. Skills 技能库

#### 核心技能
- skill-creator: 创建自定义技能
- find-skills: 查找和安装技能

#### 开发流程技能 (superpowers)
- brainstorming: 苏格拉底式设计精炼
- writing-plans: 编写详细实施计划
- test-driven-development: 测试驱动开发
- systematic-debugging: 系统性调试
- verification-before-completion: 完成前验证
- requesting-code-review: 请求代码审查

#### 文档处理技能
- docx: Word文档处理
- pptx: PowerPoint处理
- xlsx: Excel处理
- pdf: PDF表单与处理

---

## 二、使用场景

### 信息获取 → MCP 工具
- 最新技术信息 → Exa MCP
- GitHub操作 → GitHub MCP
- 代码库分析 → context7 MCP
- 笔记管理 → 印象笔记 MCP

### 开发任务 → Skills 流程
- 新功能设计 → brainstorming
- 任务规划 → writing-plans
- 代码实现 → test-driven-development
- Bug调试 → systematic-debugging

---

## 三、进化路径

### 当前阶段: 阶段 2 - 稳定运行

### 目标阶段: 阶段 4 - 智能自适应

```
阶段 2 (当前)
    ↓
阶段 3: 优化增强
├── 添加持久化记忆
├── 增强并行处理能力
├── 优化上下文管理
└── 自动错误恢复
    ↓
阶段 4: 智能自适应
├── 自动选择最优工具
├── 智能任务分解
├── 主动优化建议
└── 自我学习改进
```

---

*本文档由 AI 自动生成并同步更新*