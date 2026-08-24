---
title: Contributing
layer: project-governance
status: stable
version: 0.3.0
updated: 2026-08-24
---

# Contributing

本项目首先是一项概念与制度研究。贡献的目标不是快速填满目录，而是让命题更清楚、更可反驳、更容易追溯。

## 新建或修改文档

每份实质文档应包含 YAML 元数据：

```yaml
---
title: 文档标题
layer: project-governance | core-question | philosophy | human-model | framework | institution | case | criticism | publication | research | archive
status: stable | confirmed | draft | question | template | archive
version: 0.1.0
updated: YYYY-MM-DD
---
```

`confirmed` 仅用于冻结的项目发起者确认记录；普通理论、机制、案例和写作文件不得以此替代 `stable`、`draft`、`question` 或验证状态。

正文至少回答：

- 本文处理什么问题；
- 当前主张是什么；
- 哪些只是工作假设；
- 边界和最强反例是什么；
- 与哪些上游原则、下游机制相关；
- 下一步需要什么证据或决定。

frontmatter 中的 `version` 表示该文件最后一次发生实质内容变更时的项目版本，不要求包内所有未修改文件机械改成同一版本。

## 成熟度与验证进度分离

frontmatter 的 `status` 只说明文档是否已有命题及其当前引用资格，不说明命题是否经过现实验证。需要历史案例、外部证据、受影响者复核、专业评估、原型或试验的事项，在 [`DOCUMENT_STATUS.md`](DOCUMENT_STATUS.md) 另行登记验证状态。

验证状态不得机械写入全部文件，也不得由 `draft`、`question` 或 `stable` 自动推导。登记时至少记录：验证对象、当前验证状态、仍缺的不可替代输入、当前阻断原因和下一步可执行动作。项目内部一致性检查、AI 审阅和项目发起者确认均不能冒充受影响者参与、历史证据或现实制度效果。

## 根治理文件的权威分工

四类入口各自回答不同问题，发生不一致时不得用一句“研究框架维护定义”模糊处理：

| 入口 | 唯一职责 |
|---|---|
| `DECISION_LOG.md` | 项目接受、拒绝或替换了什么方向决定，以及由谁确认 |
| `GLOSSARY.md` | 当前术语在项目中的工作定义和概念边界 |
| `DOCUMENT_STATUS.md` | 每份文件是否可作为当前引用入口及其成熟度 |
| `03_Aletheia_Framework/` | 理论命题、理由、证据、竞争解释、反例与修订条件 |

四者应同步但不能互相代替。应用稿和公众稿发现问题时，先提出变更，再由决定、术语、状态和理论各自更新其负责部分。

## 写作纪律

1. 区分规范主张、经验事实、机制假设和实施参数。
2. 哲学家、历史案例和科学研究是论证资源，不是项目权威。
3. 事实性主张必须能够追溯；未核实内容标记 `待核查`。
4. 需求的存在、需求的解释、满足方案和公共正当性必须分开。
5. 使用“权力”时先说明它属于基本权利、事实权力还是授权权限；仅在授权权限内部再区分目标决定、专业判断、执行、监督、裁决和命令救济等角色。“请求救济”属于基本程序资格，不等于裁决或命令救济的权限。
6. 不把“有文件”写成“有定论”；不把目录完整度当作理论成熟度。
7. 不在框架层写固定工时、比例、金额、算法或完整法条。

## 作者语言与来源纪律

1. 用户直接表述、用户粘贴的既有内容、AI 回答和后续重构必须分别记录，不能统一写成“作者认为”。
2. “继续写”“好的”或对工作方向的同意，只授权继续整理，不表示作者逐句确认了 AI 随后生成的理论和第一人称段落。
3. 先保存作者能够核对和复述的日常表述，再在研究稿中补术语、学术关联和反例。若一句话“意思好像接近，但作者自己看不懂”，就不能作为已完成转写。
4. AI 可以提出结构、术语、反例和候选解释；这些新增内容必须标明为重构或建议，并经作者确认后才能升级为项目主张。
5. 第一人称公众稿在作者逐段确认前保持 `draft`；轻度编辑只说明本轮编辑幅度，不自动证明源稿作者和思想归属。
6. 哲学、历史、科学和现实案例即使符合直觉，也须完成事实核查，不能用可读性要求取消证据要求。

## Source ID 与决定确认

1. 来源进入提取、重构或决定流程前，先在 [`08_Research_Workbench/05_Provenance_and_Decision_Records/SOURCE_REGISTRY.md`](08_Research_Workbench/05_Provenance_and_Decision_Records/SOURCE_REGISTRY.md) 取得不携带语义的 Source ID。
2. Source ID 只标识来源单元，不证明作者、真实性、事实准确、许可或项目已经接受。
3. 没有在导入时取得内容哈希时记录 `not-recorded`；不得把文件名、时间或估算值伪装成哈希。
4. 新的 Accepted 决定必须在同一轮建立决定确认记录，并填写 `decision_owner`、`confirmed_by`、`confirmation_source`、`confirmation_scope`、`source_ids`、`supersedes`、`affected_documents` 与 `unresolved_questions`。
5. “好的”“继续”等简短表达只有在明确指向一个已经列明的决定集合时，才可作为该集合的范围确认；它不确认未来扩写、实施参数或未展示文字。
6. Project Aletheia 的确认记录只约束思想归属与项目版本，不能冒充受影响者同意、现实公共决定或实施授权。

公众派生稿建议使用以下来源字段，并保持维度分离：

```yaml
source_type: rtf-derived | dialogue-derived | framework-derived
source_received_from: user | archive | collaborator
source_authorship: user-confirmed | mixed-unverified | unknown-unverified
current_editing: light | structural | substantive
author_review: pending | partial | approved
fact_check: pending | complete
```

“由用户提供文件”只说明接收来源，不证明文本由用户独立写成；只有 `author_review: approved` 才表示作者已经确认当前第一人称和思想归属。

## 三条成果轨道的审查门槛

- **研究框架**：检查命题来源、概念状态、竞争解释、证据、反例和修订条件；
- **公众思想书**：检查作者语言确认、与当前框架的一致性、可读性和事实来源；
- **制度白皮书**：检查上游原则、责任与权限拆分、受影响者参与、失败条件、申诉和退出。

三条轨道可以并行写作，但当前概念和状态仍只由根治理文件与 `03_Aletheia_Framework/` 维护。

## 修改当前基线

修改 `stable` 定义时：

1. 在 `CHANGELOG.md` 说明变更理由；
2. 更新 `GLOSSARY.md`；
3. 更新 `DOCUMENT_STATUS.md`；
4. 检查所有相关内部链接和下游模型；
5. 将被替换的关键表述记录进 `99_Archive/`，不得静默删除思想演化。

## 语义冻结、结构冻结与发布

发布不是一次事后补记录。顺序应为：

```text
来源登记与 Source ID
→ 命题和决定起草
→ 确认记录与 Accepted 状态
→ 同步术语、理论、文档状态和 CHANGELOG 的 Unreleased 条目
→ 语义冻结
→ 导航、命名、链接、状态和版本引用的一致性整理
→ 结构冻结
→ 确定发布版本、完成发布段落
→ 生成压缩包、校验 UTF-8 文件名、内容完整性与哈希
```

- **语义冻结**：不再加入新主张、改变定义或扩大确认范围；之后只做不改变含义的结构整理和错误修复。
- **结构冻结**：目录、文件名、导航、链接和状态入口不再变化；之后才生成发布包。
- Source ID、决定确认与语义变更理由必须前置；最终版本号、压缩包和校验和可以后置。
- 若冻结后发现必须改变含义，解除冻结并重新走同步与审查流程，不能以“仅修订文字”为名静默修改。

## 文件与链接

- 根目录、编号层和需要工具稳定识别的系统目录优先使用 ASCII 英文名。
- `07_Writing/` 的公众渠道目录与 `99_Archive/` 的人类可读归档目录可以保留中文名称；已有清晰名称不为追求形式统一而批量改名。
- 其他目录若使用中文，应说明读者价值或迁移理由；改名必须同步导航、迁移表和内部链接，不能只做表面整齐化。
- 文件编码为 UTF-8，避免空格和特殊字符。
- 内部导航使用相对文件链接，避免依赖中文标题锚点。
- 当前工作文档不提交本机绝对路径、临时文件、缓存、`.DS_Store` 或外部符号链接。历史导入件可以在正文代码中保留来源路径，但不得把它作为当前导航入口。

## 发布边界

`07_Writing/` 中的稿件是派生表达，不是理论真源。对外稿发现概念问题时，应回到上游框架修改。项目许可证尚未选择，在明确授权前不得擅自添加开放许可。
