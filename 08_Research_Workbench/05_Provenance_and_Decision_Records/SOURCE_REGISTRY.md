---
title: Source Registry
layer: research
status: stable
version: 0.1.6
updated: 2026-08-12
---

# Source Registry

Source ID 是稳定、无语义的项目内部标识。它不编码作者、日期、文件名或可信度，也不等同于内容哈希。未在导入时取得哈希的材料统一记录为 `not-recorded`，不得事后虚构。

本表只保存公开项目内足以完成路由和来源审计的信息，不复制私人对话全文、诊断、家庭信息或本机绝对路径。来源是否由用户提供、文本是否由用户独立写成、作者是否确认当前改写、事实是否核查，是互相独立的维度。

## 当前项目对话来源

| Source ID | 来源类别 | 最小描述 | 保留位置 | 内容哈希 | 使用边界 |
|---|---|---|---|---|---|
| `SRC-2F8C4A71` | project-conversation | 用户提出本轮六步依赖链：四项结构决定、一项开放专题及发布后置步骤 | [`PROJECT_DECISION_CONFIRMATIONS.md`](PROJECT_DECISION_CONFIRMATIONS.md) | `not-recorded` | 只证明本轮项目方向来源，不代表现实公共授权 |
| `SRC-9B1D6E30` | project-confirmation | 用户以“好的，那就按照这个修改吧”确认按上述六步修改项目 | [`PROJECT_DECISION_CONFIRMATIONS.md`](PROJECT_DECISION_CONFIRMATIONS.md) | `not-recorded` | 只确认记录所列范围；不等于逐句确认未来新增文字 |
| `SRC-D8C4F2A6` | project-direction-and-confirmation | 用户在本轮消息中直接确认基本保障、有限互惠公共责任、正当理由与互惠性公共运行权益的分层边界，并要求据此更新项目 | [`PROJECT_DECISION_CONFIRMATIONS.md`](PROJECT_DECISION_CONFIRMATIONS.md) | `not-recorded` | 同一消息兼具方向陈述与项目修改确认；只约束 `PCR-5E7A91` 所列项目范围，不代表现实公共授权 |

## 既有来源提取映射

以下 Source ID 对应 `04_Source_Extractions/` 中现有十二份提取或低证据审计。ID 标识的是被审计的来源单元，不表示原始文件已复制进项目，也不提高其证据等级。

| Source ID | 项目内提取记录 | 来源状态 | 内容哈希 |
|---|---|---|---|
| `SRC-7F2A9C10` | [`提高文章可读性_项目起源提取笔记.md`](../04_Source_Extractions/提高文章可读性_项目起源提取笔记.md) | mixed dialogue; original retained outside package | `not-recorded` |
| `SRC-3D8E1B64` | [`理解思考方式的客观描述_提取笔记.md`](../04_Source_Extractions/理解思考方式的客观描述_提取笔记.md) | mixed dialogue; authorship requires paragraph-level review | `not-recorded` |
| `SRC-91C4F7A2` | [`尼采奴隶道德的批判_提取笔记.md`](../04_Source_Extractions/尼采奴隶道德的批判_提取笔记.md) | mixed dialogue; philosophical claims unverified | `not-recorded` |
| `SRC-5B2D8E73` | [`大脑与意义感丧失_提取笔记.md`](../04_Source_Extractions/大脑与意义感丧失_提取笔记.md) | AI-heavy mixed dialogue; private material not copied | `not-recorded` |
| `SRC-A6F3C109` | [`劳动与经济制度设计_来源结构提取笔记.md`](../04_Source_Extractions/劳动与经济制度设计_来源结构提取笔记.md) | AI-heavy mixed dialogue; incomplete attachment chain | `not-recorded` |
| `SRC-2E9B4D85` | [`采集社会的分裂和融合_提取笔记.md`](../04_Source_Extractions/采集社会的分裂和融合_提取笔记.md) | unlabelled dialogue conversion; attribution limited | `not-recorded` |
| `SRC-C7A1E536` | [`教育制度讨论_提取笔记.md`](../04_Source_Extractions/教育制度讨论_提取笔记.md) | mixed blocks and missing attachment context | `not-recorded` |
| `SRC-8D4F2B90` | [`道德与不公的悖论_提取笔记.md`](../04_Source_Extractions/道德与不公的悖论_提取笔记.md) | mixed dialogue; user direction relatively traceable | `not-recorded` |
| `SRC-F1C6A743` | [`去中心化与多中心化_提取笔记.md`](../04_Source_Extractions/去中心化与多中心化_提取笔记.md) | mixed dialogue and pasted external material | `not-recorded` |
| `SRC-4A8D0E62` | [`时间主权_个人时间自主权_提取笔记.md`](../04_Source_Extractions/时间主权_个人时间自主权_提取笔记.md) | AI-heavy dialogue and public discussion material | `not-recorded` |
| `SRC-B3E7C195` | [`我可以为了你死_但你不能让我为了你死_低证据来源审计.md`](../04_Source_Extractions/我可以为了你死_但你不能让我为了你死_低证据来源审计.md) | user blocks missing; only title problem auditable | `not-recorded` |
| `SRC-6C0A9F28` | [`奴隶通过劳动与自我意识_低证据来源审计.md`](../04_Source_Extractions/奴隶通过劳动与自我意识_低证据来源审计.md) | user blocks missing; AI search responses only | `not-recorded` |

## 维护规则

1. 一个来源单元只分配一个 Source ID；移动或改名不改变 ID。
2. 内容实质不同的版本不得共用同一 ID，应另建 ID 并记录关系。
3. Source ID 只解决身份，不解决作者、事实、许可或项目接受状态。
4. 引入来源时先登记 ID，再开始重构；不能等发布后凭记忆补登记。
5. 若未来取得可验证哈希，可追加算法与值，并记录在 `CHANGELOG.md`；不得覆盖原先的 `not-recorded` 而不说明取得方式。
