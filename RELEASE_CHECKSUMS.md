---
title: Release Checksums
layer: project-governance
status: stable
version: 0.3.0
updated: 2026-08-25
---

# Release Checksums

## v0.3.0 GitHub 公共研究快照检查

本节对应 2026-08-25 的 `v0.3.0` 公共研究快照。发布范围以项目 Markdown 白名单为准；文件可见不等于作者逐句批准、事实核查、现实验证或实施授权。

- Markdown 文件：232 个。
- 已检查 1,181 个项目内相对链接，无断链或越出项目根目录的链接。
- 70 个 Source ID 均有唯一主登记；所有正文引用的 Source ID 均可回到 [`SOURCE_REGISTRY.md`](08_Research_Workbench/05_Provenance_and_Decision_Records/SOURCE_REGISTRY.md)。
- 所有 Markdown 均可按 UTF-8 读取，front matter 必填字段完整，状态值合法，代码围栏闭合，并以换行结束。
- 成熟度分布：`draft` 109、`question` 23、`template` 16、`stable` 30、`archive` 51、仅供冻结确认记录使用的 `confirmed` 3。
- 第一原则只冻结十一公理与禁区的规范语义；司法解释、候选机制、人生周期、公众稿及验证方案继续保留各自草案与验证状态。
- 反馈后三步稿以 `PUB-2026-003` 作为 GitHub 研究快照公开；其 `author_review: pending` 与 `fact_check: pending` 不因公开而改变，GitHub 收录也不表示知乎页面已同步。
- 发布范围由 `D-032`、`PCR-C47D91`、`SRC-8F6C3A21` 与 [`PROJECT_INITIATOR_CONFIRMATION_v0.3.0.md`](08_Research_Workbench/05_Provenance_and_Decision_Records/PROJECT_INITIATOR_CONFIRMATION_v0.3.0.md) 互相约束。
- 发布树排除 7 个 `.DS_Store`，不包含外部附件全文、ZIP、AppleDouble `._*`、脚本、可执行文件、符号链接或本机杂项。
- `main` 与 `v0.3.0` 快照分支在发布后核对为同一提交；准确提交 SHA 和最终 ZIP SHA-256 由 GitHub 历史及交付消息保存，避免自引用造成循环变化。

最终 ZIP 只从上述 232 份 Markdown 生成；非 ASCII 路径须带 UTF-8 标记，并在交付前再次执行 CRC、逐文件内容和 sidecar 校验。

## v0.2.9 发布包检查（冻结记录）

以下数量只对应 2026-08-16 生成的 v0.2.9 发布包，不等于 v0.3.0。后续版本不得直接复用本节数字。

- Markdown 文件：194 个。
- 所有 Markdown 均可按 UTF-8 读取并包含 front matter、`version`、`updated` 与合法 `status` 字段。
- 已检查 814 个项目内相对 Markdown 链接，无断链或越出项目根目录的本地链接。
- v0.2.9 的方向确认由 `D-027`、`PCR-9F3A72`、`SRC-9F3A72C4`、单独确认记录和 Source Registry 互相链接。
- 两份案例均明确地域、时期、群体、机制、证据限制、竞争解释、反驳条件和不可复制条件；宽泛时代入口没有被改成历史总论。
- 案例外部来源分配独立 Source ID，并区分学术研究、危机后研究与组织自我报告；未取得本地文件时保持 `not-recorded`，没有补造哈希。
- 探索稿、发布登记和反馈登记已经分离；发布状态保持 `prepared-not-published`，没有虚构平台、公开链接或外部反馈。
- 历史案例层只升级为有限样本的 `in-validation`；探索性公众讨论仍是 `ready-for-validation`，哲学原典核查仍是 `not-ready`。
- 原典核查按与第一原则的直接性、当前文本暴露和下游影响分批；没有用哲学家权威替第一原则论证。
- 原始外部聊天、Markdown 和 RTF 只登记最小来源标识与既有哈希，不进入项目 ZIP。
- ZIP 不包含 `.DS_Store`、AppleDouble `._*`、旧版 ZIP 或原始外部聊天/RTF。
- 所有非 ASCII ZIP 路径使用 UTF-8 标记。
- ZIP CRC 与解压后逐文件内容在发布时复核。

最终 ZIP 的 SHA-256 在交付消息中提供，避免压缩包把自身哈希写入内部文件造成循环变化。
