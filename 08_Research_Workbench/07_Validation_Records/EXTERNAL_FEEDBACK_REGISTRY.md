---
title: External Feedback Registry
layer: research
status: stable
version: 0.2.9
updated: 2026-08-21
---

# External Feedback Registry

## 记录规则

1. 一条可独立判断的反馈分配一个 `FB-YYYY-NNN`；同一评论含多个命题时拆分。
2. 保留公开链接、日期、平台和公开署名；不复制私人身份、未公开通信或无关个人信息。
3. 分类只描述反馈作用：`support`、`counterexample`、`boundary`、`implementation-cost`、`source-lead`、`misunderstanding`。
4. “采纳”必须写出影响的文件和具体改动；“不采纳”必须保留理由，不能删除不利反馈。
5. 点赞、浏览量和简单赞同只作传播数据，不作为命题验证。
6. 项目发起者确认、AI 评价和普通公众反馈不能替代 `participant-blocked` 项所需的受影响者或实践者复核。

## 发布登记

| 发布 ID | 稿件 | 稿件版本 | 状态 | 平台 | 公开链接 | 发布日期 | 对应验证单元 |
|---|---|---|---|---|---|---|---|
| `PUB-2026-001` | [《一个公共事项，为什么要分成三步？》](../../07_Writing/External_Discussion/公共决定之后还缺哪三步.md) | 0.2.9 | `prepared-not-published` | 待项目发起者指定 | — | — | 探索性公众讨论；三模型交叉一致性 |

稿件已于 2026-08-21 根据公共需求责任修正和专业能力讨论重新整理，但仍为同一未发布候选稿。发布前必须完成作者审阅；没有公开链接和正文快照时不得把本次内部改稿登记为外部验证。

## 反馈登记

当前尚无外部反馈。文章实际发布后，从 `FB-2026-001` 开始逐条追加，禁止预填或把内部讨论冒充外部反馈。

| 反馈 ID | 发布 ID | 来源与日期 | 类型 | 可复核命题或案例 | 适用范围 | 项目处理 | 影响文件 |
|---|---|---|---|---|---|---|---|
| — | — | — | — | — | — | — | — |

## 状态变更门槛

- `prepared-not-published` → `published`：取得可访问的公开链接并核对正文版本；
- `ready-for-validation` → `in-validation`：取得至少一条具有可判断内容的外部反馈并完成登记；
- `in-validation` → `partially-validated`：反馈包含可追溯证据或明确反例，且已触发项目复核或修订；
- 任何状态都不得仅因正面反馈数量上升而进入 `validated`。
