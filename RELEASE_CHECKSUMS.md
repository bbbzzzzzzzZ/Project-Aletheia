---
title: Release Checksums
layer: project-governance
status: stable
version: 0.1.6
updated: 2026-08-12
---

# Release Checksums

本文件记录 `Project_Aletheia_v0.1.6.zip` 的最终发布验证口径与结果。压缩包自身的 SHA-256 保存在同目录 sidecar `Project_Aletheia_v0.1.6.zip.sha256`；不把最终哈希嵌回压缩包，以避免“修改记录又改变压缩包哈希”的自指问题。

## 发布包

- 包名：`Project_Aletheia_v0.1.6.zip`
- 项目版本：`0.1.6`
- 文件数：`145`
- Markdown 数：`145`
- 本地 Markdown 链接：`638`，全部有效
- 非 `archive` Markdown 导航：`passed`，无孤立文档
- ZIP UTF-8 文件名标志：`passed`，所有非 ASCII 路径均设置 UTF-8 标志
- ZIP CRC 与逐字节内容比对：`passed`，压缩包成员与发布目录逐文件一致
- 跨工具列目录与解压：`passed`，使用 Python `zipfile`、macOS `bsdtar` 与 `ditto` 复核；Info-ZIP `unzip -t` 完成 CRC 检查
- 禁止内容检查：`passed`，无 `.DS_Store`、`__MACOSX`、符号链接或本机绝对路径
- SHA-256：见同目录 `Project_Aletheia_v0.1.6.zip.sha256`

## 验证边界

- 校验和证明当前压缩包字节未变化，不证明研究命题已经得到经验验证。
- `archive` 文件继续作为思想演化材料保留，不构成现行定义或实施规则。
- 本轮在一个 macOS 环境内使用多种独立解压工具复核，不等同于已经在 Windows、Linux 实机完成兼容测试；UTF-8 标志和标准 ZIP 结构已通过机器检查。
