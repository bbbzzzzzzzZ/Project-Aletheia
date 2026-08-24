---
title: External Feedback Registry
layer: research
status: stable
version: 0.3.0
updated: 2026-08-25
source_ids: SRC-91E4C7A2, SRC-A6F2D8B9, SRC-5C7E1A84, SRC-8D6B4E21, SRC-2A9C7F40, SRC-C4E8173B, SRC-73F2A690
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
| `PUB-2026-001` | 《公共决定之后，还缺什么？》；[当前反馈后修订稿](../../07_Writing/External_Discussion/公共决定之后还缺哪三步.md)另作公开对应关系待核的草案 | [用户提供正文快照](Publication_Snapshots/PUB-2026-001_公共决定之后还缺什么_用户提供快照.md)，原文件哈希 `19d29995…` | `published-snapshot-pending` | 知乎 | [公开问题页](https://www.zhihu.com/question/2074134261079327262) | 精确发布日期与最早可核反馈时间待绑定 | 探索性公众讨论；三模型交叉一致性 |
| `PUB-2026-002` | 《为什么需要责任型社会制度：从意义、承认到劳动与价格》 | [用户提供正文快照](Publication_Snapshots/PUB-2026-002_为什么需要责任型社会制度_用户提供快照.md)，原文件哈希 `1927410d…` | `published-snapshot-pending` | 知乎 | [公开问题页](https://www.zhihu.com/question/2073918477526738781) | 精确发布日期与最早可核反馈时间待绑定 | 项目研究问题、术语消歧、制度工程与既有方案比较 |
| `PUB-2026-003` | [《一个公共事项，为什么要分成三步？》](../../07_Writing/External_Discussion/公共决定之后还缺哪三步.md)反馈后探索稿 | GitHub `v0.3.0` 研究快照；正文 SHA-256 见 v0.3.0 发布校验记录 | `published-version-frozen` | GitHub | [v0.3.0 快照正文](https://github.com/bbbzzzzzzzZ/Project-Aletheia/blob/v0.3.0/07_Writing/External_Discussion/%E5%85%AC%E5%85%B1%E5%86%B3%E5%AE%9A%E4%B9%8B%E5%90%8E%E8%BF%98%E7%BC%BA%E5%93%AA%E4%B8%89%E6%AD%A5.md) | 2026-08-25 | 探索性公众讨论；不改变现有验证状态 |

`PUB-2026-001` 的用户提供外发正文已经归档。当前仓库稿吸收了后续反馈，但公开问题页疑似存在编辑，尚未完成逐段比对；项目目前不判断当前稿是否已同步公开。只有能够证明形成新的独立发布版本时，才另建 PUB 记录。

`PUB-2026-002` 的标题、问题页与用户提供外发正文已经建立映射。两项快照都已归档，但平台编辑历史、精确发布日期、发布者个人入口和部分评论 permalink 仍待独立核验；项目目前不能证明每条评论所见的准确时点版本，因此保持 `published-snapshot-pending`。

`PUB-2026-003` 只冻结 GitHub `v0.3.0` 中的反馈后稿。它与旧知乎稿分开登记；GitHub 公开不等于知乎页面已编辑，也不把 `author_review: pending`、`fact_check: pending` 或探索性公众讨论的 `in-validation` 自动升级。

“稿件”列采用用户提供正文的题名，不等于知乎问题页当前显示标题；页面标题和正文均可能编辑。公开链接只证明入口映射，不能单独冻结评论时版本。

## 反馈登记

| 反馈 ID | 发布 ID | 来源与日期 | 类型 | 可复核命题或案例 | 适用范围 | 项目处理 | 影响文件 |
|---|---|---|---|---|---|---|---|
| `FB-2026-001` | `PUB-2026-002` | 知乎公开署名“老矿工”；项目于 2026-08-24 取得用户转贴；[个人主页](https://www.zhihu.com/people/Dr.Ge)，原反馈发布日期与 permalink 待补 | `boundary`、`source-lead` | 应先列明项目要解决的具体问题，以及能够检索到的前人方案 | 项目研究入口与原创性边界 | 采纳为研究比较任务；不接受 AI 代写的新核心问题 | [`研究问题与既有方案地图`](../01_Source_and_Priority_Maps/Project_Aletheia_研究问题与既有方案地图.md) |
| `FB-2026-002` | `PUB-2026-002` | 同上；用户提供公开反馈转贴 | `boundary`、`source-lead` | “需求”、责任、权力与权利具有跨学科歧义；公开稿须说明项目工作定义 | 术语与陌生读者入口 | 部分采纳：补市场需求边界；其余沿用现行责任与权力模型，不按评论重建三分法 | [`需求模型`](../../03_Aletheia_Framework/需求模型.md)、[`GLOSSARY.md`](../../GLOSSARY.md) |
| `FB-2026-003` | `PUB-2026-002` | 知乎公开截图，署名“shimly”，发布于 2026-08-23 22:50；反馈 permalink 待补 | `source-lead` | 传统思想或既有体系可能已经系统处理相关问题，项目须防止重复发明 | 思想史与既有方案 | 保留为核查线索；“已经解决”未获证据支持，不升级为结论 | [`原典核查优先级`](../../01_Philosophy/原典核查优先级.md)、[`研究问题与既有方案地图`](../01_Source_and_Priority_Maps/Project_Aletheia_研究问题与既有方案地图.md) |
| `FB-2026-004` | `PUB-2026-001` | 知乎公开截图，署名“农村户口”，2026-08-23；反馈 permalink 待补 | `boundary` | 三步可能只是重述现有行政流程；还应看制度承诺与实际表达、事实约束是否一致 | 三步模型的新增作用与事实权力 | 部分采纳：澄清三步是个人约束的依据与记录审查，不宣称新建行政流程；实际结果继续进入反馈审计 | [当前修订稿](../../07_Writing/External_Discussion/公共决定之后还缺哪三步.md)、[`反馈修正机制`](../../03_Aletheia_Framework/反馈修正机制.md) |
| `FB-2026-005` | `PUB-2026-001` | 知乎“维拉”；项目于 2026-08-24 取得[公开回答](https://www.zhihu.com/question/2074134261079327262/answer/2075129489638662741)，原回答发布日期待核 | `counterexample`、`boundary` | 大家认为一件事重要，不等于已经同意投入资源或承担代价；公共决定可能尚未形成 | 公共必要性、资源承诺与夜间急救 | 采纳为前置边界：未合理识别可发现的实质受影响群体并提供相称参与机会，或未记录资源、替代、机会成本与复核条件时，不能进入个人派工；这不要求全体一致 | [当前修订稿](../../07_Writing/External_Discussion/公共决定之后还缺哪三步.md)、[`五机制交叉表`](../../04_Institution_Design/Project_Aletheia_五机制交叉表.md) |
| `FB-2026-006` | `PUB-2026-001` | 同上 | `implementation-cost`、`boundary` | 教育、参与、审计、储备和急救会争夺有限资源；多方立场、妥协边界与渐进转型影响方案能否落地 | 决定形成、机构承接和连续性 | 采纳为资源比较、可接受降级、冲突记录和可逆试行问题；不预设全体共识 | [`夜间急救走查`](../../06_Criticism_and_Failure/Mechanism_Walkthroughs/夜间急救_五机制内部走查.md)、[`Open Problems`](../../03_Aletheia_Framework/Open_Problems_List.md) |
| `FB-2026-007` | `PUB-2026-001` | 同上所列儿科关停、法国养老与养老改革罢工、韩国医生罢工链接 | `source-lead` | 现实服务短缺、劳动冲突与改革成本可能为机制提供不利案例 | 特定国家、时期、行业和事件 | 只作来源线索；未核验报道、因果和适用范围前不登记为案例验证 | [`研究问题与既有方案地图`](../01_Source_and_Priority_Maps/Project_Aletheia_研究问题与既有方案地图.md) |
| `FB-2026-008` | `PUB-2026-001` | 知乎“恒予大叔”；项目于 2026-08-24 取得[公开回答](https://www.zhihu.com/question/2074134261079327262/answer/2074823183241328599)，原回答发布日期待核 | `boundary` | 公共决定所用的群体信息与分类，是否得到个体确认或能够被本人纠正 | 受影响者识别、代表与责任分配 | 部分采纳：要求方法可查询、可纠正、可质疑代表关系；不要求每个人逐项同意公共事实或共同决定 | [`Open Problems`](../../03_Aletheia_Framework/Open_Problems_List.md)、[`需求模型`](../../03_Aletheia_Framework/需求模型.md) |
| `FB-2026-009` | `PUB-2026-001` | 同上 | `boundary`、`source-lead` | 成本意识教育和观察者视角可以提高个人理解选择与风险的能力 | 参与条件与制度责任的竞争解释 | 保留为参与支持问题；不采纳“教育个人适应系统可替代制度降低不合理成本和公平分配” | [`研究问题与既有方案地图`](../01_Source_and_Priority_Maps/Project_Aletheia_研究问题与既有方案地图.md) |
| `FB-2026-010` | `PUB-2026-001` | 知乎公开截图，署名“恒予大叔”，日期及短评 permalink 待补 | `implementation-cost`、`boundary` | 个人意愿会变化且受健康、家庭与基本生活约束；公共岗位又要求连续占位 | 承担、储备、恢复和退出 | 现行机制已部分覆盖；提高动机变化、生活刚性、替代和服务连续性的验证优先级，不从兴趣或技能推出持续承诺 | [`五机制交叉表`](../../04_Institution_Design/Project_Aletheia_五机制交叉表.md)、[`Open Problems`](../../03_Aletheia_Framework/Open_Problems_List.md) |
| `FB-2026-011` | `PUB-2026-001` | 知乎公开截图，署名“维拉”，日期及短评 permalink 待补 | `counterexample`、`implementation-cost` | 公共收益可能伴随成本转嫁、搭便车、信息失灵、寻租和监管成本；任务系统也可能把人降成数字与流程 | 五机制及反馈闭环 | 采纳为成本分布、利益冲突、外部监督和人的处境停止线；不从搭便车风险推出全民自动义务 | [`五机制交叉表`](../../04_Institution_Design/Project_Aletheia_五机制交叉表.md)、[`反馈修正机制`](../../03_Aletheia_Framework/反馈修正机制.md) |
| `FB-2026-012` | `PUB-2026-002`（暂关联） | 知乎新增评论截图，公开名称“维拉”；项目于 2026-08-24 取得，界面显示“2 小时前”；所属页面、精确时间与 permalink 待核 | `boundary` | 价值框架或个人研究与可以进入社会实验的制度方案，需要不同程度的结构、承压与证据 | 白皮书、机制草案与实施研究的层级边界 | 采纳为层级说明：当前项目已有候选机制，但不宣称已经形成现实运行方案 | [`制度白皮书`](../../04_Institution_Design/Project_Aletheia_制度白皮书.md)、[`机制层总览`](../../04_Institution_Design/Project_Aletheia_机制层总览草案.md) |
| `FB-2026-013` | `PUB-2026-002`（暂关联） | 同一截图；来源边界同上 | `implementation-cost`、`boundary` | 新方案须说明解决旧制度什么问题、相对优劣、必要性、代价、所需成本和资源 | 候选机制的现实基线与竞争方案 | 采纳为“制度工程比较卡”，并由项目进一步检查成本由谁承担；禁止用理想候选对比现制最坏个案 | [`制度压力测试协议`](../../06_Criticism_and_Failure/制度压力测试协议.md)、[`五机制交叉表`](../../04_Institution_Design/Project_Aletheia_五机制交叉表.md) |
| `FB-2026-014` | `PUB-2026-002`（暂关联） | 同一截图；来源边界同上 | `implementation-cost`、`boundary` | 分阶段实施、风险控制、应急、缓冲、纠错、嵌入现行体系、支撑制度与试点须作为相互依赖的链条审查 | 现实干预前置、停止、回滚与服务接续 | 采纳为验证门槛；不采纳另一段 AI 对话提出的固定章节、阶段数、行业或实施时间表 | [`制度压力测试协议`](../../06_Criticism_and_Failure/制度压力测试协议.md)、[`ROADMAP.md`](../../ROADMAP.md) |

前一批反馈的原文身份与 AI 延伸见 [`2026-08-24_两篇外发文章新增反馈与整合边界.md`](../06_Current_Round_Source_Notes/2026-08-24_两篇外发文章新增反馈与整合边界.md)；本轮正文快照、截图评论和另一段 AI 建议的边界见 [`2026-08-24_两篇外发正文快照与制度工程评论整合边界.md`](../06_Current_Round_Source_Notes/2026-08-24_两篇外发正文快照与制度工程评论整合边界.md)。登记表只保留判断所需的短命题，不复制公开回答全文或图片。

`FB-2026-012`—`014` 是同一张截图拆出的三个判断单元，在来源独立性、样本数量和支持强度上只能计作一条评论。

## 状态变更门槛

- `prepared-not-published` → `published-link-pending`：项目发起者说明和混合导出能够共同支持外发事实及反馈存在，但文章或发布者入口尚未取得；
- `published-link-pending` → `published-snapshot-pending`：已补到可访问的文章、发布者入口或可核对的公开讨论入口，但尚未核对评论发生时的正文；
- `published-snapshot-pending` → `published-version-frozen`：取得可访问的发布者入口并保存或核对评论者当时看到的正文版本；
- `ready-for-validation` → `in-validation`：取得至少一条具有可判断内容的外部反馈并完成登记；
- `in-validation` → `partially-validated`：能够核对反馈所针对的正文版本，反馈包含可追溯证据或明确反例，且已触发范围清楚的项目复核或修订；
- 任何状态都不得仅因正面反馈数量上升而进入 `validated`。

本轮归档了两份用户提供外发正文，并把可追溯反馈与具体修订对应；但评论时点与正文版本尚不能逐条核对，因此“探索性公众讨论”继续保持 `in-validation`。它只表示外部批评确实进入登记并触发了读者入口、资源承诺、成本分布与制度工程修订；不表示任何哲学事实、机制效果或整套制度得到验证。

普通公众评论不能替代患者、一线人员、照护对象、机构或实践者复核。白皮书、五机制、机制总览和三份内部走查的状态均不随之改变；截图评论的 permalink 与平台编辑历史仍须补齐。
