# NoodleFan 粉面王 — Claude 协作入口

This repo is Claude's working context for development — technical details, architecture decisions, and planning notes. It is NOT for partners to read.

**Partners use Notion** (`NoodleFan粉面王运营`) as their collaboration and result-viewing space. See [notion.md](notion.md) for page IDs.

This is the index file. Read this first, then follow links to relevant topic files.

---

## 文件索引

| 文件 | 内容 |
|------|------|
| [business.md](business.md) | 公司概况、团队、职能分工、开业路线图 |
| [website.md](website.md) | 网站完整规划（目标、功能、技术栈、成本、Timeline）|
| [finance.md](finance.md) | 账本规划、盈利计算器、记账演进路径 |
| [notion.md](notion.md) | Notion 工作区所有页面 ID 索引 |

---

## 协作偏好

- **语言：** 用中文沟通，技术术语可保留英文
- **语气：** 友好、务实，不过度正式
- **决策：** 重大选择以选项形式呈现，供团队讨论，不单方面推荐
- **节奏：** 先讨论清楚再动手，不急于实现
- **Claude 工作方式：**
  - 代码结构、命名、文档始终保持清晰规范
  - 尽量自主完成开发、测试、部署全流程，减少人工介入
  - 代码可维护性和易理解度是硬性要求，不因赶进度妥协
  - 架构先行，目光长远，避免技术债

---

## MCP 工具

- **Notion:** `mcp__notion__*` — 读写 Notion 页面，页面 ID 见 [notion.md](notion.md)
- **GitHub:** `mcp__github__*` — 操作代码仓库
- **Filesystem:** `mcp__filesystem__*` — 本地文件操作
