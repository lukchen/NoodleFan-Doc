# NoodleFan 粉面王 — Project Context

This file provides Claude with full context about the NoodleFan business and project. Read this before starting any task.

---

## Business Overview

**NoodleFan 粉面王** is a Chinese noodle/rice noodle (粉面) takeout restaurant being launched in the US, focused on delivery platforms.

**Current status:** Pre-opening. Menu is largely finalized. Profit calculator built. No physical operations yet.

---

## Ownership & Team

Four partners across two families — all decisions are made together; no one acts unilaterally.

| Name | Family | Role |
|------|--------|------|
| Eli (me) | Family A (Eli & Betsy) | Operations & Day-to-Day |
| Betsy | Family A | Company Registration & Legal; Family A representative |
| Henry | Family B (Henry & Miki) | Menu & Food |
| Miki | Family B | Finance & Bookkeeping; Family B representative |

**Capital & profit split:** 50/50 between the two families. Representatives are Betsy and Miki.

**Culture:** Two families who are also friends and business partners. Tone should be collaborative and friendly, not overly formal or legalistic.

---

## Functional Division (职能分工)

Roles define the primary executor, not exclusive ownership. Everyone has the right to be informed, discuss, and oversee. No unilateral decisions.

| Area | Primary |
|------|---------|
| 运营与日常管理 | Eli |
| 菜单与出餐质量 | Henry |
| 财务与记账 | Miki |
| 公司注册及运营 | Betsy |
| 外卖平台管理 | Eli |
| 社交媒体运营 | 待定 |
| 全员参与 | Marketing, major decisions |

---

## Delivery Platforms

- DoorDash
- Uber Eats
- Fantuan (番茄外卖) — important for the Chinese community

---

## Notion Workspace

All business docs live in Notion under **NoodleFan粉面王运营**.

- **Root page:** https://app.notion.com/p/NoodleFan-150e1e412f7080458fb1e9851e1d565c
  - Page ID: `150e1e41-2f70-8045-8fb1-e9851e1d565c`

| Sub-page | Page ID | Notes |
|----------|---------|-------|
| 职能分工 | `386e1e41-2f70-818a-9186-d5d93ba7b944` | Duty distribution table; callout note on role flexibility |
| 盈利计算器 | `386e1e41-2f70-8182-93b9-f2663b427fb6` | Links out to Google Sheets profit simulator |
| 开业路线图 | `386e1e41-2f70-8193-8f30-d783a3508716` | Pre-opening roadmap, Phases 1–5 |
| 账本 | `386e1e41-2f70-819c-8efe-f9fc238b4e04` | Simple ledger; note to upgrade to QuickBooks/Wave post-opening |
| 菜单制作 (TBD) | `386e1e41-2f70-80ab-8cab-d7e0f13da8cb` | Menu production, in progress |

**Notion integration token:** stored in Claude Desktop MCP config (`claude_desktop_config.json`). Use `mcp__notion__*` tools to read/write Notion directly.

---

## Opening Roadmap (开业路线图)

- **Phase 1** — 公司与平台注册
- **Phase 2** — 厨房准备与试运营
- **Phase 3** — 外卖平台上线
- **Phase 4** — 软开业（试运营收集反馈）
- **Phase 5** — 市场推广与正式开业（社交媒体、预热内容、开业优惠、持续运营、追踪数据）

---

## Profit Simulator

A local web app for modeling revenue, costs, and net profit across delivery platforms.

- **Location:** `C:\NoodleFan\ProfitSimulator\` (not tracked in this repo)
- **Stack:** Vanilla HTML/CSS/JS + Chart.js, with i18n (bilingual CN/EN)
- **Also linked in Notion** under the 盈利计算器 sub-page
- Models platform fees (DoorDash, Uber Eats, Fantuan), food cost %, and projected net profit

---

## Website Project

**Goal:** Build an official NoodleFan website that combines:
1. Brand/marketing presence
2. Online ordering (or redirect to delivery platforms)

This is a planned sub-project. Stack and scope TBD.

---

## Key Preferences & Notes

- **Language:** User communicates in Chinese (Simplified); respond in Chinese unless technical context calls for English.
- **Tone:** Friendly, practical, not overly formal.
- **Decisions:** Always frame major choices as options to discuss, not unilateral recommendations.
- **Accounting:** Current ledger is temporary. Plan to adopt proper business accounting software (QuickBooks or Wave) after opening.
- **MCP tools available:** Notion, GitHub, filesystem, memory.
