---
title: Document Status
layer: project-governance
status: stable
version: 0.3.0
updated: 2026-08-25
---

# Document Status

更新时间：`2026-08-25`

## 状态口径

- `stable`：该文件在其负责范围内是当前项目基线；表示当前引用入口，不表示哲学或经验上已经最终证明。
- `confirmed`：只用于冻结的项目发起者确认记录，表示确认范围已经留痕；不表示被确认内容已完成事实核查、现实验证或公共授权。
- `draft`：已有命题，仍需论证、反例或机制补全。
- `question`：文件的主要答案仍开放；可以明确重述已经接受的上游边界，但其中新增的经验命题、取舍和机制方案不代表项目立场。
- `template`：结构已建，内容待研究。
- `archive`：历史材料，不得作为现行定义引用。

## 第二维度：验证状态

文档成熟度回答“当前写到什么程度、能否作为引用入口”；验证状态回答“某项命题或机制已被什么外部材料、人员或场景检验到什么程度”。两者正交：`stable` 不等于已经现实验证，`draft` 也可能已经准备好接受验证。

| 验证状态 | 判定条件 | 不表示什么 |
|---|---|---|
| `not-required` | 纯导航、来源身份、历史确认范围或项目维护记录，不提出需要现实检验的独立命题 | 不表示该文件不可审计或永不修订 |
| `not-ready` | 验证对象、竞争方案、证据问题、参与对象、测试步骤或停止条件仍不清楚 | 不表示只要继续扩写文字就一定能解决 |
| `ready-for-validation` | 已能说明验证对象、所需材料或参与者、方法、失败条件和记录方式 | 不表示验证已经开始 |
| `participant-blocked` | 已有可执行验证方案，但缺少不可由作者或 AI 替代的受影响者、实践者或其他参与者 | 不表示问题永久无法推进；仍可做招募、材料准备和风险审查 |
| `in-validation` | 已开始取得案例、访谈、专业复核、公开反例、模拟或试验记录 | 不表示样本充分或结论稳定 |
| `partially-validated` | 验证对象或被评价版本已经固定，至少一组可追溯外部材料或参与结果已与具体修改逐条对应，适用范围、反例和复核边界均有记录 | 不得外推到未检验群体、时期或制度环境 |
| `needs-replication` | 当前范围已有支持或反驳结果，需要换场景、群体或方法复核稳健性 | 不表示第一次结果无效 |
| `validated-for-current-scope` | 预定范围、失败条件和参与要求已完成，且结果、反例与局限均已记录 | 只对明示范围成立，不是最终真理或现实授权 |

验证状态以“具体命题、机制或测试单元”为对象，集中登记在本文件；不要求为全部导航、归档和模板文件机械加标签。状态变化必须附证据入口或阻断原因，不能只改标签。

## 当前验证登记

| 验证单元 | 相关入口 | 文档成熟度 | 验证状态 | 当前阻断或缺口 | 下一步 |
|---|---|---|---|---|---|
| 权力—责任—决策接口 | [`03_Aletheia_Framework/权力_责任_决策交叉一致性表.md`](03_Aletheia_Framework/权力_责任_决策交叉一致性表.md) | draft | `ready-for-validation` | 已完成文本内交叉审计，尚无现实项目或机构流程复测 | 选取一个公共项目和一个紧急事项逐阶段映射 |
| 谁代表共同需求 | `决策模型.md`、`Political_System/代表机制.md` | question | `not-ready` | 代表范围、事项适配程序和参与方案仍未收束，不能把“缺参与者”当作唯一问题 | 先形成两个可比较代表方案及失败条件，再邀请受影响者复核 |
| 开放主体人类模型 | `02_Human_Nature/开放主体模型.md` | draft | `ready-for-validation` | 缺生命周期、跨文化、残障与能力变化的证据和参与记录 | 制定证据综述问题表，并招募不同生命阶段参与者评议 |
| 需求归属、个人需求责任与非等级互助 | [`03_Aletheia_Framework/需求归属与公共需求责任.md`](03_Aletheia_Framework/需求归属与公共需求责任.md)、`责任模型.md`、`公共责任制度.md` | draft | `not-ready` | 已补入公众第一责任，但无障碍摘要、场景题、参与保护、退出和反馈回写规则尚未齐备，也尚缺患者、残障者、照护者、维权者和一线服务者复核 | 先准备无障碍摘要和医疗、无障碍、照护、组织缺口、私人高成本偏好场景题及参与保护协议，再邀请小组评议 |
| 项目级制度白皮书 | [`04_Institution_Design/Project_Aletheia_制度白皮书.md`](04_Institution_Design/Project_Aletheia_制度白皮书.md) | draft | `not-ready` | 七条公众命题已获作者方向确认，并补入现实比较入口；其他措辞、事实核查、现实基线比较、模块实践者审阅和跨场景失败测试尚未完成 | 先完成其余段落作者审阅，再用一份具体场景比较卡检查现制功能、候选收益、转换成本、停止和回滚 |
| 项目级机制层总览 | [`04_Institution_Design/Project_Aletheia_机制层总览草案.md`](04_Institution_Design/Project_Aletheia_机制层总览草案.md)、[`五机制交叉表`](04_Institution_Design/Project_Aletheia_五机制交叉表.md) | draft | `not-ready` | 已完成现有专题、竞争方案、停止线、制度工程比较字段和三次内部假设走查；但全文尚待作者复核，方案尚未选择，且没有现实基线、实践者、受影响者或现场证据 | 先复核交叉表和比较协议，再选择一个真实场景形成现行基线、竞争方案、参与保护、记录方法和失败条件齐备的验证包 |
| 五机制三场景内部走查 | [`06_Criticism_and_Failure/Mechanism_Walkthroughs/README.md`](06_Criticism_and_Failure/Mechanism_Walkthroughs/README.md) | draft | `not-ready` | 三份走查全部是假设输入，只检查纸面接口与返回路径；临床、照护、能源、法律、公平和参与事实均未核验 | 先完成作者与专题复核、参与保护和记录协议，达到 `ready-for-validation` 后，再邀请患者或服务对象、一线承担者、机构、专业人员、维权者和其他受影响者参与并留痕 |
| Aletheia 第一原则 v1.0 语义冻结 | [`03_Aletheia_Framework/第一原则_v1.0_语义冻结.md`](03_Aletheia_Framework/第一原则_v1.0_语义冻结.md) | stable | `not-required` | 本单元只记录十一公理与禁区的规范语义版本，不提出独立经验结论 | 维持变更纪律；事实支撑、反例、推论和机制效果分别进入相应验证单元 |
| 司法解释体系 | [`04_Institution_Design/Constitutional_and_Legal_System/司法解释体系.md`](04_Institution_Design/Constitutional_and_Legal_System/司法解释体系.md) | draft | `not-ready` | 四种方法与贯穿式主体接口已形成草案，但比较法、案件样本、主体参与、代理冲突和记录格式尚未复核 | 先以匿名案件卡比较解释理由和失败停止线，再邀请法律实践者与受影响者审阅 |
| 四阶段人生周期内部走查 | [`06_Criticism_and_Failure/Lifecycle_Walkthroughs/README.md`](06_Criticism_and_Failure/Lifecycle_Walkthroughs/README.md) | draft | `not-ready` | 四份材料均为假设输入，作者审阅、事实核查和外部参与尚未完成；出生与亲职明确禁止现实制度试验 | 依次复核 40 岁转行、18 岁转衔、80 岁照护、出生与亲职；生育只做法律、伦理和匿名情境评审 |
| 公共责任缺席与后果 | [`04_Institution_Design/Labor_System/Mechanisms/公共责任缺席与后果_候选机制.md`](04_Institution_Design/Labor_System/Mechanisms/公共责任缺席与后果_候选机制.md) | draft | `not-ready` | 已分无责任突发、轻微过失和恶意逃避，但证据规则、竞争方案、后果白名单、恢复与申诉尚未完成 | 先比较仅重排、任务内修复与同机制非基本权益限期调整三类方案；基本保障、综合信用和自动派工保持停止 |
| 40 岁转行首次外部验证 | [`08_Research_Workbench/07_Validation_Records/External_Validation_Plans/40岁转行_首次外部验证方案.md`](08_Research_Workbench/07_Validation_Records/External_Validation_Plans/40岁转行_首次外部验证方案.md) | draft | `not-ready` | 国家级现制资料与三套方案已建；尚未选定具体地域和就业类型，访谈材料、同意、存储规则和联系人未完成，邀请尚未发出 | 选定一个地域和就业类型，冻结当地基线，完成参与保护及统一问题表后，再向五组复核者发出邀请 |
| 儿童公共照护与成长自主 | `Education_System/儿童公共照护与成长自主.md` | question | `not-ready` | 仍缺具体候选机制、年龄与支持性决定边界；儿童参与也需独立伦理和保护方案 | 先完成参与保护协议和两个候选照护模型 |
| 有限互惠公共责任任务 | `Labor_System/Mechanisms/有限互惠公共责任机制.md` | draft | `ready-for-validation` | 缺医疗、照护、消防、能源等不同连续性场景数据 | 对每类服务分别建立最低覆盖、能力、负担、豁免和中断测试 |
| 责任积分与领域专业评价 | `Incentive_System/责任积分、贡献积分与领域专业评价.md` | draft | `ready-for-validation` | 缺跨行业任务样本、质量证据、刷分与定价权俘获测试 | 选择医疗、照护、工程、清洁各一组任务试算，不先确定统一参数 |
| 十环节权力集中控制 | `Political_System/十环节权力集中控制矩阵.md` | draft | `ready-for-validation` | 三环、四环触发线尚未适配组织规模、风险和连续性 | 用医院、公共工程和小型社区项目绘制真实控制图 |
| 公共权力失效纠错 | `Political_System/公共权力失效纠错机制.md` | draft | `ready-for-validation` | 缺证据删除、监督俘获、无力赔偿和关联获利的完整案例演练 | 按四种失败链分别演练触发、保全、调查、先行修复与追偿 |
| 历史案例层 | [`05_Case_Studies/README.md`](05_Case_Studies/README.md) | draft | `in-validation` | 已完成多贝 Ju/’hoansi 与法戈尔危机两个有限样本；仍缺被较少记录主体、独立复核与差异案例复现 | 补非成员、女性、照护者和地方社区材料，并用第三个差异案例复现 |
| 探索性公众讨论 | [`公共决定之后还缺哪三步.md`](07_Writing/External_Discussion/公共决定之后还缺哪三步.md)、[`外部反馈登记`](08_Research_Workbench/07_Validation_Records/EXTERNAL_FEEDBACK_REGISTRY.md)、[`发布快照`](08_Research_Workbench/07_Validation_Records/Publication_Snapshots/README.md) | draft | `in-validation` | 两份知乎历史快照、公开问题页和反馈已经登记，反馈后稿也以 `PUB-2026-003` 随 GitHub v0.3.0 冻结公开；但评论时点版本、平台编辑历史、部分 permalink、当前稿逐段作者确认、事实核查及受影响者和实践者复核仍缺 | 逐条核对评论 permalink、时间与所见正文版本，补齐知乎发布者入口；完成当前稿审阅和事实核查，再邀请患者或服务对象、一线人员及相关实践者复核 |
| 哲学原典核查 | [`原典核查优先级.md`](01_Philosophy/原典核查优先级.md) | draft | `not-ready` | 已完成排序，但尚缺第一批具体版本、段落、解释分歧和逐条对照 | 先完成黑格尔、儒家与尼采三项，不机械补齐目录 |

`participant-blocked` 只用于方案已经足够让参与者判断、且下一步确实无法由作者、AI 或继续查资料替代的情形。仍缺候选方案或验证协议时保持 `not-ready`，避免把写作和研究缺口误报为外部参与阻断。

## 权威分工

- `DECISION_LOG.md` 是项目方向决定及其确认范围的入口；
- `GLOSSARY.md` 是工作术语定义和概念边界的入口；
- `DOCUMENT_STATUS.md` 是文件引用资格与成熟度的入口；
- `03_Aletheia_Framework/` 保存理论命题、理由、证据、竞争解释、反例和修订条件。

四者共同约束当前基线，但不存在一个文件可以替代另外三者。来源身份与项目内部决定确认见 `08_Research_Workbench/05_Provenance_and_Decision_Records/`；这些记录不构成现实公共授权。

## 核心文档状态

### v0.3.0 新增与修订文档

| 文档 | 状态 | 当前用途 | 升级条件 |
|---|---|---|---|
| `04_Institution_Design/Project_Aletheia_制度白皮书.md` | draft | 当前跨模块制度白皮书总论；七条公众命题已获作者方向确认，其余内容仍为部分审阅 | 完成其余段落作者确认、事实核查、模块实践者审阅和场景压力测试 |
| `04_Institution_Design/Project_Aletheia_机制层总览草案.md` | draft | 连接五个候选机制；有限公共责任个案已确认继续保留为候选，不等于已采用 | 结合交叉表完成其余措辞确认、竞争方案取舍和外部验证协议 |
| `04_Institution_Design/Project_Aletheia_五机制交叉表.md` | draft | 路由五个候选机制、现有专题、竞争方案与停止线，不取代定义源 | 完成作者与专题维护者逐项复核，解决重复定义并确定仍保留的竞争方案 |
| `06_Criticism_and_Failure/Mechanism_Walkthroughs/` | draft | 保存夜间急救、长期照护和能源连续性三份内部假设走查；不属于现实验证记录 | 补现实材料、参与保护与记录协议，由实践者和受影响者复核后另建外部验证记录 |
| `03_Aletheia_Framework/第一原则_v1.0_语义冻结.md` | stable | 界定十一公理与禁区的语义冻结范围、排除项和变更纪律；不复制权威正文 | 只有实质改变公理或禁区时建立新决定并更新原则版本 |
| `04_Institution_Design/Constitutional_and_Legal_System/司法解释体系.md` | draft | 四种解释方法与贯穿式主体接口的内部制度草案；不构成现实法律意见 | 完成作者审阅、比较法、匿名案件卡、法律实践者及受影响者复核 |
| `06_Criticism_and_Failure/Lifecycle_Walkthroughs/` | draft | 按 40 岁转行、18 岁转衔、80 岁照护、出生与亲职保存四份内部假设走查 | 逐份完成作者审阅、事实核查和对应的外部材料；出生与亲职不得进入现实试验 |
| `04_Institution_Design/Labor_System/Mechanisms/公共责任缺席与后果_候选机制.md` | draft | 研究已经正当成立的任务缺席后怎样区分原因、修复与候选后果；不进入第一原则 | 完成竞争方案、证据、后果白名单、独立复核、申诉、恢复与停止线后再评估验证准备度 |
| `08_Research_Workbench/07_Validation_Records/External_Validation_Plans/40岁转行_首次外部验证方案.md` | draft | 保存固定基线与三方案、五类复核者和不干预边界；当前为 `proposed-unstarted` | 选定地域和就业类型，完成本地事实、邀请、同意、提问与记录协议后再启动 |
| `08_Research_Workbench/06_Current_Round_Source_Notes/2026-08-25_第一原则司法解释人生周期与验证范围确认.md` | archive | 记录本轮指令、采用范围、排除项和现实试验边界 | 永不直接升级；后续变化通过新决定、来源或验证记录追加 |
| `08_Research_Workbench/01_Source_and_Priority_Maps/Project_Aletheia_研究问题与既有方案地图.md` | question | 把公众追问转成“具体问题—既有研究方向—项目暂定增量—竞争解释—证据缺口”比较骨架 | 用原典、综述、现实案例和最强竞争解释逐项填充；未完成前不作原创性声明 |
| `08_Research_Workbench/06_Current_Round_Source_Notes/2026-08-24_两篇外发文章新增反馈与整合边界.md` | archive | 区分项目发起者话语、外部评论、AI 分析与本轮采用边界，并记录两个附件的哈希及表征关系 | 永不直接升级；后续变化以新反馈、事实核查或明确决定追加 |
| `07_Writing/Thought_Book/为什么“为你好”之前不先问我.md`、`为什么工资会像一个人的价格.md` | draft | 两篇中心问题已获作者确认；现有段落、第一人称、事实和混合来源归属仍未逐段批准 | 完成作者逐段确认、事实核查和现行框架一致性审阅 |
| `08_Research_Workbench/06_Current_Round_Source_Notes/2026-08-23_十一份材料提取与整合边界.md` | archive | 登记十一份材料的身份、哈希、相互关系、采用和排除边界 | 永不直接升级；后续变更以新来源、明确确认或新研究记录追加 |
| `08_Research_Workbench/06_Current_Round_Source_Notes/2026-08-21_三份对话与制度白皮书整合边界.md` | archive | 区分三份对话中的用户方向、用户粘贴材料、文内指令、AI 扩写、采用项和排除项 | 永不直接升级；后续变更以新来源或明确决定追加 |
| `03_Aletheia_Framework/需求归属与公共需求责任.md` | draft | 定义需求归属、第一责任与公众第一责任，并连接既有公共责任层级 | 用医疗、照护、无障碍、组织需求与私人偏好复核分类、公共最低范围和个人交互责任 |
| `08_Research_Workbench/06_Current_Round_Source_Notes/2026-08-20_需求归属与公共需求责任来源确认.md` | archive | 分离共享对话中的用户方向、AI 延伸与本轮采用边界 | 永不直接升级；后续变更以新来源和新决定追加 |
| `08_Research_Workbench/05_Provenance_and_Decision_Records/PROJECT_DECISION_CONFIRMATIONS.md` 中 `PCR-A18D8A` | stable | 记录 `D-028` 的确认范围和未确认的 AI 扩写 | 作为历史确认记录保留，不倒改确认范围 |
| `08_Research_Workbench/05_Provenance_and_Decision_Records/PROJECT_DECISION_CONFIRMATIONS.md` 中 `PCR-B60C2F` | stable | 记录七条公众命题、五篇中心问题与候选机制保留的确认范围 | 保持范围限定；不得据此升级全文批准、事实核查或现实验证状态 |
| `07_Writing/External_Discussion/公共决定之后还缺哪三步.md` | draft | 反馈后探索稿；已作为 `PUB-2026-003` 随 GitHub v0.3.0 公开，旧知乎正文另有历史快照 | 完成逐段作者审阅与事实核查；若同步到知乎或其他平台，继续保存平台、时间、正文版本和反馈对应关系 |
| `08_Research_Workbench/07_Validation_Records/EXTERNAL_FEEDBACK_REGISTRY.md` | stable | 记录三个外发事项、十四个反馈判断单元及版本关系；GitHub 公开不等于知乎重发 | 补齐知乎平台编辑历史、精确日期、发布者入口和缺失 permalink；继续逐条保留不利反馈与处理理由 |
| `08_Research_Workbench/05_Provenance_and_Decision_Records/PROJECT_INITIATOR_CONFIRMATION_v0.3.0.md` | confirmed | 记录 v0.3.0 公共研究快照和反馈后三步稿的发布范围 | 作为发布确认记录保留；不得据此升级全文批准、事实核查、验证状态或现实授权 |

### v0.2.9 新增与修订文档

| 文档 | 状态 | 当前用途 | 升级条件 |
|---|---|---|---|
| `05_Case_Studies/多贝朱霍安西_互惠网络与非正式权力.md` | draft | 用有限民族志案例检验互惠、评价、事实权力和退出条件 | 补较少记录主体并以差异案例复现 |
| `05_Case_Studies/蒙德拉贡法戈尔危机_合作所有权与成本分配.md` | draft | 用合作社危机检验成员边界、实际控制和修复分布 | 补非成员材料、决策时间线和独立结果复核 |
| `08_Research_Workbench/07_Validation_Records/EXTERNAL_FEEDBACK_REGISTRY.md`（v0.2.9 初始状态） | stable | 当时只建立外部发布与反馈登记结构，未预填发布链接或反馈 | 后续发布史见 v0.3.0 区段；本历史说明不倒改当时状态 |
| `01_Philosophy/原典核查优先级.md` | draft | 规定分批核查次序和完成标准 | 完成第一批原典、解释分歧和第一原则关系表 |
| `08_Research_Workbench/05_Provenance_and_Decision_Records/PROJECT_INITIATOR_CONFIRMATION_v0.2.9.md` | stable | `D-027` 与 `PCR-9F3A72` 的确认边界 | 作为历史确认记录保留，不倒改确认范围 |

### v0.2.8 新增与修订文档

| 文档 | 状态 | 当前用途 | 升级条件 |
|---|---|---|---|
| `03_Aletheia_Framework/权力_责任_决策交叉一致性表.md` | draft | 对照触发、归责、授权、事实控制、监督、退出和修复，不作为平行定义源 | 用普通公共项目、紧急事项和小型组织流程复测并修订 |
| `03_Aletheia_Framework/责任模型.md` | draft | 增加事实权力与实际控制责任接口 | 用正式权限与实际控制分离的案例检验归责边界 |
| `03_Aletheia_Framework/决策模型.md` | question | 明确公共决定、任务责任分配和执行授权三类输出 | 用具体决策流程验证分步条件和记录能否真实执行 |
| `DOCUMENT_STATUS.md` | stable | 同时维护文档成熟度和验证进度的权威入口 | 取得证据、参与或试验记录时逐项更新并保留依据 |
| `08_Research_Workbench/05_Provenance_and_Decision_Records/PROJECT_INITIATOR_CONFIRMATION_v0.2.8.md` | stable | `D-026` 与 `PCR-5E32B8` 的确认边界 | 作为历史确认记录保留，不倒改确认范围 |

### v0.2.7 新增与修订文档

| 文档 | 状态 | 当前用途 | 升级条件 |
|---|---|---|---|
| `04_Institution_Design/Incentive_System/责任积分、贡献积分与领域专业评价.md` | draft | 年度责任清零、领域贡献累计、质量评价和专业参考摘要的现行机制入口 | 用多行业任务验证额度、系数、质量、隐私、反刷分和服务覆盖 |
| `04_Institution_Design/Labor_System/Mechanisms/有限互惠公共责任机制.md` | draft | 把一般互惠责任转换为具体任务义务，并处理机构先行、自愿不足、关系型任务和退出 | 完成照护、医疗、消防、能源等场景的法律、资源和受影响者压力测试 |
| `08_Research_Workbench/05_Provenance_and_Decision_Records/PROJECT_INITIATOR_CONFIRMATION_v0.2.7.md` | stable | `D-025`、`PCR-A2D7F9` 与责任积分四层功能的确认边界 | 作为历史确认记录保留，不倒改确认范围 |
| `08_Research_Workbench/06_Current_Round_Source_Notes/2026-08-16_责任积分与有限互惠公共责任机制整合.md` | archive | 两份外部文件及本轮确认的来源、采用与排除边界 | 永不直接升级；后续修订另建决定 |

### v0.2.6 新增已确认方向文档

| 文档 | 状态 | 当前用途 | 升级条件 |
|---|---|---|---|
| `04_Institution_Design/Incentive_System/责任会计、贡献履历与专业可靠性.md`（v0.2.6 历史名称；现行文件已改名） | draft | v0.2.6 当时分开当期责任结算、贡献可见和领域内专业可靠性 | 后续状态见上方 v0.2.7 现行入口 |
| `08_Research_Workbench/05_Provenance_and_Decision_Records/PROJECT_INITIATOR_CONFIRMATION_v0.2.6.md` | stable | `D-024`、`PCR-6D2A8F` 与取代 `C-13` 的确认边界 | 作为历史确认记录保留，不改写确认范围 |
| `08_Research_Workbench/06_Current_Round_Source_Notes/2026-08-15_责任会计三分结构来源确认.md` | archive | `SRC-6D2A8F31` 的来源、采用和排除边界 | 永不直接升级；后续修订通过新决定追加 |

### v0.2.5 新增已确认方向文档

| 文档 | 状态 | 当前用途 | 升级条件 |
|---|---|---|---|
| `04_Institution_Design/Political_System/十环节权力集中控制矩阵.md` | draft | 识别流程与利益集中，并自动触发回避、复核、审计或权限拆分 | 用不同规模、风险、连续性和机构俘获案例验证阈值及副作用 |
| `08_Research_Workbench/05_Provenance_and_Decision_Records/PROJECT_INITIATOR_CONFIRMATION_v0.2.5.md` | stable | `D-023`、`PCR-9C2F61` 与矩阵确认边界 | 作为历史确认记录保留，不改写确认范围 |

### v0.2.4 新增已确认方向文档

| 文档 | 状态 | 当前用途 | 升级条件 |
|---|---|---|---|
| `04_Institution_Design/Political_System/公共权力失效纠错机制.md` | draft | 外部证据、替代调查、先行修复、追偿和不当利益追缴的候选恢复链 | 完成法律比较、机构俘获、基金偿付与多主体责任压力测试 |
| `04_Institution_Design/Incentive_System/公共合作激励与参与保障.md` | draft | 需求、时间、安全、服务、补偿、有效参与及反报复的合作激励框架 | 完成普通参与、专业任务、高风险任务和连续服务验证 |
| `08_Research_Workbench/05_Provenance_and_Decision_Records/PROJECT_INITIATOR_CONFIRMATION_v0.2.4.md` | stable | G/C 共 34 项按建议状态确认的项目记录 | 作为历史确认记录保留，不改写确认范围 |
| `08_Research_Workbench/06_Current_Round_Source_Notes/2026-08-15_公共权力纠错与合作激励来源确认.md` | archive | 两份 AI-heavy 来源的哈希、采用和排除边界 | 永不直接升级；后续修订通过新决定追加 |

### v0.2.3 已确认上游方向

| 文档 | 状态 | 当前用途 | 升级条件 |
|---|---|---|---|
| `03_Aletheia_Framework/需求模型.md`、`责任模型.md` | draft | 个人需求责任、共同脆弱性与非等级互助的上游研究入口 | 用医疗、维权、残障、养老、长期照护和关系性需要案例完成反例与共同验证 |
| `08_Research_Workbench/06_Current_Round_Source_Notes/2026-08-15_个人需求责任与非等级互助来源确认.md` | archive | `SRC-8D4F2B90`、`SRC-C49CCC9B`、`PCR-C49CCC` 与 `D-021` 的来源、采用和排除边界 | 永不直接升级；后续修订通过新决定追加 |

### v0.2.2 新增已确认方向文档

| 文档 | 状态 | 当前用途 | 升级条件 |
|---|---|---|---|
| `04_Institution_Design/Shared_Mechanisms/职业入口开放、能力分级与任务授权原则.md` | draft | 资格开放、岗位有限及能力—资格—授权分离方向 | 完成职业法规、训练容量、认证和服务对象压力测试 |
| `04_Institution_Design/Constitutional_and_Legal_System/司法资格、岗位与案件授权分离机制.md` | draft | 法院常设、资格开放、岗位有限和案件逐项授权方向 | 完成比较法、司法实践、组织独立及案件连续性验证 |
| `04_Institution_Design/Education_System/生育、婚姻、亲职与儿童保障分离原则.md` | draft | 身体自主、成年人关系、亲职、儿童权利和公共育幼分离方向 | 完成法律、儿童发展、照护实践和受影响者共同验证 |
| `08_Research_Workbench/05_Provenance_and_Decision_Records/PROJECT_INITIATOR_CONFIRMATION_v0.2.2.md` | confirmed | P/J/F/S 共 37 项项目发起者确认记录 | 作为历史确认记录保留，不改写确认范围 |

### v0.2.1 已确认方向文档

| 文档 | 状态 | 当前用途 | 升级条件 |
|---|---|---|---|
| `03_Aletheia_Framework/Aletheia_Architecture_Map.md` | draft | 项目三层结构与四流闭环总览 | 各模块接口完成压力测试 |
| `03_Aletheia_Framework/Module_Dependency_Graph.md` | draft | 上下游依赖和回写规则 | 依赖关系完成全库审计 |
| `03_Aletheia_Framework/Open_Problems_List.md` | question | P0/P1/P2 开放问题入口 | 问题分别路由并取得状态记录 |
| `03_Aletheia_Framework/权力转换审计模型.md` | draft | 检查优势向事实权力和授权权限的转换 | 用多个模块和现实案例验证 |
| `03_Aletheia_Framework/制度接口原则.md` | draft | 五个优先模块接口的共同规则 | 完成接口压力测试与受影响者复核 |
| `04_Institution_Design/Constitutional_and_Legal_System/*` | draft | 宪制骨架、法律形成、司法解释与救济 | 法律研究、公共讨论和案例验证 |
| `04_Institution_Design/Administrative_System/*` | draft | 授权任务型行政框架 | 行政实践、任务退出和监督验证 |
| `04_Institution_Design/Public_Finance/*` | draft | 任务预算与公共资源框架 | 财政资料、分配案例和退出测试 |
| `04_Institution_Design/Information_and_AI_Governance/*` | draft | 已接受的信息宪政和 AI 边界原则；具体实现开放 | 数据、隐私、模型和替代运行验证 |
| `04_Institution_Design/Incentive_System/*` | draft | 已接受的激励反等级原则；具体机制开放 | 激励效果、机会累积和事实权力验证 |
| `08_Research_Workbench/05_Provenance_and_Decision_Records/PROJECT_INITIATOR_CONFIRMATION_v0.2.0.md` | confirmed | 44 项项目发起者逐项确认记录 | 作为历史确认记录保留，不改写原确认范围 |
| `06_Criticism_and_Failure/制度压力测试协议.md` | draft | 跨场景统一检查字段，并新增现行基线、竞争方案、转换成本、可选验证方式、风险门槛、停止与回滚的制度工程比较卡 | 先用一个真实场景完成基线比较卡，再由实践者与受影响者复核字段是否可执行 |
| `08_Research_Workbench/06_Current_Round_Source_Notes/*` | archive | 本轮聊天和 RTF 的来源、采用与排除边界 | 永不直接升级；命题须复制到当前层评审 |

| 文档 | 状态 | 当前用途 | 升级条件 |
|---|---|---|---|
| `README.md` | stable | 项目定位与阅读入口 | 项目定位发生实质变化 |
| `PROJECT_INDEX.md` | stable | 根 README 下沉后的完整阅读与文档索引 | 目录、入口或文档路由变化时同步 |
| `VERSION.md`、`CHANGELOG.md` | stable | 当前工作版本、思想变更与发布状态 | 发布新版本或方向发生变化时更新 |
| `RELEASE_CHECKSUMS.md` | stable | 当前发布包的文件数、链接、UTF-8 路径、CRC 与逐字节完整性结果 | 重新生成发布包或发布新版本时更新 |
| `CONTRIBUTING.md`、`DECISION_LOG.md` | stable | 写作纪律与已接受结构决定 | 治理规则发生变化 |
| `DOCUMENT_STATUS.md` | stable | 各文件成熟度的唯一状态入口 | 任一文件状态变化时同步 |
| `GLOSSARY.md` | stable | 当前工作性术语基线 | 核心定义修订时同步第一原则与模型 |
| `MIGRATION_MAP.md` | stable | 既有材料的新结构路由 | 新增迁移材料或路径变化 |
| `ROADMAP.md` | draft | 当前优先级与工作队列 | 完成依赖审查并按推进结果持续修订 |
| `08_Research_Workbench/05_Provenance_and_Decision_Records/*` | stable | Source ID、来源映射及项目决定确认范围 | 来源或确认关系变化时追加记录，不静默改写历史确认 |
| `00_Core_Question/*` | question | 保持根问题开放 | 不升级为结论；由框架文档回答 |
| `01_Philosophy/从奴隶道德到价值定义权.md` | draft | 从奴隶道德主题对话形成的 Aletheia 重构；处理价值定义、处境性评价、善意代言、适应与计价边界 | 完成原典、思想史、经验材料和最强反例核查 |
| `01_Philosophy/存在与自我.md` | draft | 区分事实解释、个人意义、共享意义与公共正当性，并审查宣称价值与实际激励 | 补充哲学、制度正当性与经验研究，并检验分层在具体争议中的解释力 |
| `01_Philosophy/儒家伦理.md` | draft | 研究关系责任、道德外包、书写与命名权、承担者缺席及制度实践一致性 | 完成原典、解释传统、历史因果和反向污名核查 |
| `01_Philosophy/黑格尔主奴辩证法.md` | draft | 研究多重承认网络、象征认可与实际条件、制度依赖及劳动主体性的边界 | 完成原典、解释史、劳动经验研究及多重网络反例核查 |
| `01_Philosophy/原典核查优先级.md` | draft | 按与第一原则的直接性、当前暴露和下游影响安排核查 | 完成第一批具体版本、段落、分歧解释和逐条关系表 |
| `01_Philosophy/` 其余文件 | template / draft | 思想对话与概念辨析 | 按优先级补充原典、二手研究及 Aletheia 的接受/拒绝理由，不机械平均推进 |
| `02_Human_Nature/演化心理学.md` | template | 研究方法与待检验议题 | 补充可核查证据与反例后转为草案 |
| `02_Human_Nature/开放主体模型.md` | draft | 人在现实限度中仍可终身发展与修订方向的工作模型 | 补充生命周期、跨文化、能力变化证据与反例 |
| `02_Human_Nature/` 其余文件 | draft | 可验证的人类行为假设 | 补充跨文化和行为证据、反例与适用边界 |
| `03_Aletheia_Framework/README.md` | draft | 框架关系与导航 | 各模型接口稳定后复核 |
| `03_Aletheia_Framework/研究与推理方法.md` | draft | 异常记录、命题分层、竞争解释、反例、证据复核与临时停止规则 | 用多个专题完整演练并补充来源审计流程 |
| `03_Aletheia_Framework/世界观.md` | draft | 保存人、关系、社会与制度的当前方向，并明确人的问题可以停留在无需新建共同任务或规则的回应空间 | 完成作者复核，以跨文化、关系和生命阶段材料检验边界 |
| `03_Aletheia_Framework/制度生成语法.md` | draft | 只处理另行越过共同协调入口门槛的事项，区分任务、规则、承担依据、授权与退出 | 用多领域案例检验入口门槛、双循环接口与拒绝制度化的正常路径 |
| `03_Aletheia_Framework/世界观与制度生成语法.md` | archive | 旧合并路径的迁移说明，不保存现行定义 | 只为历史链接保留；不得作为当前框架入口 |
| `03_Aletheia_Framework/第一原则.md` | stable | Aletheia 第一原则 v1.0 的权威正文；稳定范围仅为十一公理与禁区的规范语义 | 按语义冻结记录维护；事实支撑、反例、推论和下游机制继续分别审查 |
| `03_Aletheia_Framework/第一原则_v1.0_语义冻结.md` | stable | 冻结范围、排除项与版本变更纪律的治理入口 | 公理或禁区发生实质变化时另建决定并更新版本 |
| `03_Aletheia_Framework/需求模型.md` | draft | 区分需求表达与公共义务 | 建立代表、冲突和撤回程序 |
| `03_Aletheia_Framework/责任模型.md` | draft | 请求、创设、受益、执行、决策授权与第三方影响的责任分账 | 解决不可预见影响、有限救助与集体责任边界 |
| `03_Aletheia_Framework/权力模型.md` | draft | 有限授权与退出 | 建立紧急状态、监督者监督和救济闭环 |
| `03_Aletheia_Framework/资源模型.md` | question | 资源分类、权利束及救济—预防—能力建设—象征激励的配置问题 | 完成稀缺、机会成本、生态、跨代与最坏受影响者边界 |
| `03_Aletheia_Framework/决策模型.md` | question | 共同需求、跨时间配置与受影响者共同设计 | 完成代表性、少数保护、专家角色、参与支持和不参与保障机制 |
| `03_Aletheia_Framework/反馈修正机制.md` | draft | 纠错与退出原则 | 建立试点、指标、申诉和日落流程 |
| `04_Institution_Design/README.md` | draft | 应用层接口与导航 | 各模块上游依赖和反馈接口稳定 |
| `04_Institution_Design/Project_Aletheia_制度白皮书.md` | draft | 跨模块制度框架总论；连接共同命题、六个模型、九个模块、评价方向与未决问题 | 完成作者确认、事实核查、实践者审阅与多场景失败测试 |
| `04_Institution_Design/Labor_System/公共责任制度.md` | draft | 保存已接受的有限互惠公共责任原则，并研究具体任务形成、正当理由、豁免、延期、替代与申诉 | 用不同能力、健康、照护与关键服务情境验证公平性和边界 |
| `04_Institution_Design/Labor_System/基本保障_有限公共责任_关键服务连续性协调研究.md` | question | 研究已接受原则之间的协调机制、参数与最坏情形 | 完成资料研究、受影响者和实践者共同验证；原则边界已接受不表示协调方案成立 |
| `04_Institution_Design/Labor_System/` 根级其余文件 | draft | 劳动应用框架 | 完成必要任务、时间、能力和退出验证 |
| `04_Institution_Design/Education_System/自我认识教育.md`、`教育制度设计.md` | question | 教育机制开放问题 | 完成儿童表达、稀缺资源与隐私边界 |
| `04_Institution_Design/Education_System/生命周期教育.md` | draft | 未成年探索、逐步自主与成年自定义生活的生命周期接口 | 与不同年龄和处境的参与者共同验证支持、保护与退出边界 |
| `04_Institution_Design/Education_System/儿童公共照护与成长自主.md` | question | 公共支持、家庭责任、稳定关系、儿童逐步自主与反机构化的开放问题 | 与儿童、家庭、照护者和专业人员共同设计可退出、可救济的验证方案 |
| `04_Institution_Design/Education_System/` 其余文件 | draft | 教育目标、个人能力图谱与能力发现方向 | 补充证据、反例和机制接口 |
| `04_Institution_Design/Economic_System/市场经济.md`、`公共资源.md`、`创新激励.md` | question | 资源、交换与激励开放问题 | 建立基本保障、稀缺与市场边界 |
| `04_Institution_Design/Economic_System/README.md`、`知识产权.md` | draft | 经济导航与知识制度方向 | 完成贡献回馈和开放机制验证 |
| `04_Institution_Design/Political_System/README.md`、`民主决策.md`、`代表机制.md` | question | 治理与代表开放问题 | 完成授权、少数保护、规模与撤回机制 |
| `04_Institution_Design/Political_System/多中心治理与技术中枢.md` | question | 区分数据拓扑、权限多中心、真实退出与跨中心协调救济 | 用不同治理与技术场景检验唯一入口、串谋、互操作、回滚和紧急退出 |
| `04_Institution_Design/Political_System/权力来源.md`、`权力限制.md` | draft | 授权与限制方向 | 完成监督、救济、紧急状态和强制边界 |
| `04_Institution_Design/Shared_Mechanisms/主体社区与城市渐进可达机制.md` | draft | 有限资源下“主体社区—可达走廊—城市网络”的跨制度机制 | 完成需求者参与、选址、全城最低底线、资源责任、试点指标与退出救济验证 |
| `04_Institution_Design/Shared_Mechanisms/五张制度机制表_候选稿.md` | archive | 含固定工时、积分和旧“已确定”状态的已被取代机制快照 | 不直接升级；若需复用，复制单项到研究工作区重新评审 |
| `04_Institution_Design/Shared_Mechanisms/README.md` | draft | 当前跨制度机制及旧候选稿导航 | 路由与机制状态稳定后复核 |
| `04_Institution_Design/Labor_System/Mechanisms/README.md` | draft | 当前劳动机制草案与已归档候选稿的导航 | 机制路由与归档边界稳定后复核 |
| `04_Institution_Design/Labor_System/Mechanisms/公共服务连续性与储备机制.md` | draft | 区分任务、关系与系统连续性，研究稳定团队、承诺储备、交接、待命和容量边界 | 用医疗、照护、能源等案例验证分类、真实退出、储备维护、负担与隐私成本 |
| `04_Institution_Design/Labor_System/Mechanisms/公共责任与社会基础保障维护细则_候选稿.md` | archive | 含固定工时、抽签、积分、处罚和非自愿义务的已被取代机制快照 | 不直接升级；若需复用，复制单项到研究工作区重新评审 |
| `04_Institution_Design/Labor_System/Implementation/*` | archive | 根目录重构前的参数与公式实施稿 | 不直接升级；需要从机制层重新评审 |
| `05_Case_Studies/多贝朱霍安西_互惠网络与非正式权力.md` | draft | 检验互惠网络、贡献声望、非正式权力和现实退出条件 | 补女性、照护、冲突与不同网络位置材料，并用其他小规模社会复现 |
| `05_Case_Studies/蒙德拉贡法戈尔危机_合作所有权与成本分配.md` | draft | 检验成员民主、关联控制、非成员成本和危机互助 | 补子公司劳动者、临时工、地方社区与危机决策时间线材料 |
| `05_Case_Studies/` 其余文件 | template | 宽泛历史比较入口 | 选择具体地域、时期、群体和机制后再形成案例，不按时代直接下结论 |
| `06_Criticism_and_Failure/体验过拟合与解释闭合风险.md` | draft | 防止体验吻合、结构类比和 AI 判断被直接升级为普遍理论 | 用实际研究记录测试替代解释、证据状态和暂停条件 |
| `06_Criticism_and_Failure/劳动任务系统压力测试.md` | draft | 以来源标记的失败假设检验能力、任务、认证、连续性、指标与公私边界 | 完成受影响者和实践者复核、证据字段，并至少进行一次可比较、可停止的演练 |
| `06_Criticism_and_Failure/道德外包、定义权与退出成本压力测试.md` | draft | 检验承担者污名、定义权复制、退出成本转嫁、过去自愿被偷换为未来授权及善意代言抹去当事人 | 用真实案例、竞争解释和受影响者复核检验五条失败链 |
| `06_Criticism_and_Failure/基本保障、有限公共责任与关键服务连续性压力测试.md` | draft | 检验保障条件化、责任无限化、伪能力判断、正当理由失效、权益关联扩张、服务中断及负担转嫁 | 用不同服务和成员处境记录通过条件、停止条件、补救责任与复测结果 |
| `06_Criticism_and_Failure/` 其余文件 | draft | 保存最强反驳 | 给出可证伪条件与制度响应 |
| `07_Writing/公众号文章/为什么帮助别人，反而会被看不起.md` | archive | 早期混合来源公众候选稿；已由新的思想书候选正文取代，不再作为当前公众入口 | 不直接升级；如需复用，回到来源和现行框架重新审阅后另建正文 |
| `07_Writing/Thought_Book/序言_如果今天重新设计人类社会.md` | draft | 公众思想书候选序言；源 RTF 的第一人称与事实来源待确认 | 完成作者逐段确认、事实核查与当前框架一致性审阅 |
| `07_Writing/Thought_Book/为什么帮助别人反而会被看低.md`、`为什么一个人学了一种东西就要做一辈子.md`、`谁应该为我的需求负责.md` | draft | 三篇中心问题已获作者确认；现有正文仍是作者语言候选 | 完成作者逐段确认、事实核查及与现行框架的一致性审阅 |
| `07_Writing/Thought_Book/为什么“为你好”之前不先问我.md`、`为什么工资会像一个人的价格.md` | draft | 两篇中心问题已获作者确认；混合来源、现有段落和事实主张仍未逐段批准 | 完成作者逐段确认、事实核查及与现行框架的一致性审阅 |
| `07_Writing/Thought_Book/README.md` | draft | 公众思想书的范围、五篇正文入口、语言和来源边界；五篇中心已确认 | 完成五篇正文的逐段确认与序言审阅，并继续整理章节问题表 |
| `07_Writing/Project_Overview/README.md`、`项目总纲.md` | draft | 七条公众核心命题已确认；其他三部分和具体措辞仍为部分审阅 | 完成其余段落作者确认、事实核查与三轨一致性审阅 |
| `07_Writing/External_Discussion/公共决定之后还缺哪三步.md` | draft | 以夜间急救解释公共需求归属、具体承担与执行授权；反馈后稿已作为 `PUB-2026-003` 随 GitHub v0.3.0 公开，旧知乎版另有冻结快照 | 补知乎编辑历史、发布者入口与评论 permalink，完成当前稿作者审阅和事实核查；在其他平台发布时继续另建版本记录 |
| `07_Writing/` 其余文件 | template / draft | 对外表达模板和既有公众草稿 | 按发布门槛逐项展开，不以公开本身替代验证 |
| `08_Research_Workbench/` 各级 README、`IMPORT_MANIFEST.md` | stable | 非规范研究材料的路由、来源分层、来源身份与导入规则 | 导入范围、Source ID 或权威分工变化时更新 |
| `08_Research_Workbench/07_Validation_Records/*` | stable | 外部发布、反馈和验证状态变化的可追溯登记 | 只登记真实链接与反馈；保留不利反馈和处理理由 |
| `08_Research_Workbench/04_Source_Extractions/提高文章可读性_项目起源提取笔记.md` | archive | 项目起源、用户直接方向、AI 扩写边界与当前路由 | 不直接升级；具体命题须进入当前层重新评审 |
| `08_Research_Workbench/04_Source_Extractions/理解思考方式的客观描述_提取笔记.md`、`尼采奴隶道德的批判_提取笔记.md` | archive | 既有长对话的来源边界、采用内容、排除项与当前路由 | 不直接升级；具体命题须进入当前层重新评审 |
| `08_Research_Workbench/04_Source_Extractions/大脑与意义感丧失_提取笔记.md` | archive | 意义、评价与资源决策问题的混合来源记录 | 不把私人材料、AI 心理解释或未经核查的科学与历史断言升级 |
| `08_Research_Workbench/04_Source_Extractions/劳动与经济制度设计_来源结构提取笔记.md` | archive | 初始劳动制度方向、AI 扩写、反例、旧参数和现行路由的来源审计 | 不直接升级；当前命题只从现行劳动模块和失败分析引用 |
| `08_Research_Workbench/04_Source_Extractions/` 中 v0.1.4 历史聊天提取与低证据审计 | archive | 八份历史聊天材料的用户、混合、AI、当前重构、缺失区块与现行路由记录 | 不直接升级；哲学、人类学、心理、历史和制度效果命题须重新研究与验证 |
| `08_Research_Workbench/03_Revision_Audits/责任型社会制度_架构规格文档_兼容性审计.md` | archive | 根目录重构前架构快照的兼容性与替代关系审计 | 只作演化证据；当前定义与状态从根治理和现行模型引用 |
| `08_Research_Workbench/03_Revision_Audits/劳动与经济制度设计_再核对笔记.md` | archive | 2026-08-09 历史审计，含已经过时的参数与“当前确认”措辞 | 只作演化证据；引用时必须同时显示文首警告和当前替代入口 |
| `08_Research_Workbench/` 其余导入工作文件 | archive | 旧资料、旧状态与修订过程证据 | 不直接升级；复制到当前层重新评审 |
| `99_Archive/*` | archive | 保存迁移摘要与已放弃路线 | 永不直接升级；需要复制到工作区重新评审 |

## 当前已确定的边界

- 人格与基本生存资格不由劳动、收入、能力或贡献决定。
- 需求可以表达，但不自动支配他人。
- 第一责任先随需求归属主体判断，不随表面提出者、当下求助者、需求体验者或执行者自动移动；第一责任不是全部过错、亲自执行或授权。
- 对归属于个人的需求，个人进入满足方案后，在能力、安全和现实条件允许范围内承担合理自助、求助、维权、必要交互、减损与说明责任；这不适用于单纯表达需求，也不把公共需求、组织需求、机构失败或侵害后果重新归给求助者。
- 责任不自动产生永久权力。
- 能力属于个人，认证不等于占有或随时调用。
- 人具有终身继续展开和修订方向的可能，但不负有持续优化、训练或展示潜力的义务。
- 个人能力图谱默认私有；信息授权、联系授权、任务承诺与执行权限必须分步成立。
- 授权权限必须有事项、对象、行为、数据、资源、期限和复核边界，并随任务关闭、任期届满、撤销或制度终止而退出。
- 个人时间默认属于自己。
- AI 只能辅助，不是最终裁决者。
- 知识开放与贡献回报可以并存；具体期限与算法属于机制层待验证内容。
- 研究框架、公众思想书与制度白皮书可以并行；Decision Log、Glossary、Document Status 与 `03` 分别维护决定、术语、引用状态与理论内容。
- 基本权利、事实权力与授权权限相互区分：基本权利包含必要的程序资格且不由任务授权产生，事实权力限于显著或持续的非对称实际控制且不自动正当，授权权限受有限任务或特定公共职能限定、定期复核，并在任务关闭、任期届满、撤销或制度终止时退出。
- 基本保障和基本权利不与有限互惠公共责任履行挂钩，也不因逃避责任而消失。
- 衰老、重病、残障、失能和照护需要属于任何人可能进入的共同脆弱处境，不构成低等人格身份。
- 互助可以跨时间和对象传递；基本照护不作逐人功劳结算，贡献承认不产生人格从属、永久债务、逐人还债或服从义务。
- 具备相应现实能力的成员原则上承担有约束力但有限、公平且可审查的互惠公共责任；正当理由可以支持豁免、延期或替代。
- 经正当确认的公共需求由公众承担需求归属层第一责任；公众不是每个自然人的义务总和，当下受难者或求助者不因公共需求在其身上显现就负责公共系统的存在与维护。
- 公共必要性认定、公共需求归属责任、公共组织与维护责任、有限互惠公共责任和具体公共责任任务义务须分别说明；公共需求一经确认，公众第一责任随归属成立，但不自动生成组织形式、成员分担、具体派工或权限。
- 互惠性公共运行权益可以在严格相关、相称、限期、可申诉并具有恢复程序时与履责相关；具体清单、关联和后果仍是开放问题。
- 任务生命周期和制度形成与修正循环相互反馈，但不能替对方完成授权、审查和退出。
- 世界观与制度生成语法分别保存：人的经验和关系问题不自动进入流程，制度语法只对另行成立的候选共同协调事项开放。

## 已接受结构与待验证实现

以下结构已经由项目接受：世界观边界与独立的制度生成语法、开放主体的规范边界、私人能力图谱与公共能力池分离、三条成果轨道并行、用户表述与 AI 扩写分别追溯、来源案例与制度主张分离，以及权力三分、需求归属先行、公众第一责任、个人需求责任、公共责任五层、有限互惠原则、共同脆弱性、非等级互助、保障与责任解绑、公共权力失效纠错、十环节集中控制、非等级合作激励、双循环与两种留痕分离。

“已接受”不表示具体实现已验证。年龄边界、能力字段、认证标准、授权期限、匹配算法、任务邀请、隐私保护、试验指标和制度效果仍是 `draft` 或 `question`，不得从结构决定直接推出。

## 当前根框架最大缺口

下列问题的标签与承担方式见 [`ROADMAP.md`](ROADMAP.md)：

1. `[V]` 谁能够代表共同需求，以及代表如何被纠正或撤回；
2. `[D]` 需求冲突时的不可让渡底线，以及 `[V]` 的优先程序；
3. `[D]`、`[R]`、`[V]` 如何把有限互惠公共责任转化为具体任务，同时验证相关现实能力、机构先行责任、公平分配、正当理由、豁免、延期、替代、补偿、申诉和负担上限；
4. `[D]`、`[V]` 无人承担必要任务时，自愿、补偿、有约束力分担与紧急强制之间的合法界线；
5. `[V]` 紧急状态的启动、复核、补偿、终止与追责；
6. `[R]` 如何使贡献记录不资本化、等级化或身份化；
7. `[R]`、`[V]` 如何验证开放主体及其他人类模型，而不是把道德愿望当成人性事实；
8. `[V]` 如何验证能力信息授权、邀请、承诺和退出在现实中可理解、可拒绝且不形成监控。
9. `[D]`、`[V]` 即时救济、风险预防、长期能力建设与象征激励如何在不掩盖当前伤害的情况下并行配置。
10. `[R]`、`[V]` 技术中枢、唯一入口与多中心机构怎样形成事实权力，跨中心冲突与串谋如何救济。
11. `[D]`、`[V]` 即时支持、公共事实认定与具体责任程序如何分离并互相衔接。
12. `[R]`、`[V]` 道德外包、定义权复制与退出成本转嫁在现实中如何识别和修正。
13. `[D]`、`[R]`、`[V]` 基本保障、有限互惠公共责任与关键服务连续性怎样协调，哪些方案会把保障条件化、责任无限化、正当理由架空或让关键服务失效。
14. `[D]`、`[R]`、`[V]` 哪些互惠性公共运行权益与公共协作具有足够直接关联，何种后果相称、期限多长，以及如何申诉和恢复。
15. `[R]`、`[V]` 外部证据、替代调查、先行修复和利益追缴能否抵抗监督俘获，又不形成新的证据或调查中心。
16. `[R]`、`[V]` 合作激励能否改善个人需求、时间与安全，同时避免程序便利演化成跨领域信用和机会等级。
17. `[R]`、`[V]` 十环节的三环和四环触发线怎样适配不同风险、规模和连续性，又不被关联主体形式拆分规避。
18. `[R]`、`[V]` 需求归属规则能否同时阻止公共需求私人化与私人需求公共化；公众第一责任怎样转成可追溯机构责任而不平均派工。

## 当前应用层专项

- `[A]`、`[V]` 主体社区与城市渐进可达：确定全城最低底线、主体社区范围、扩容顺序，并防止渐进建设固化为隔离；
- `[A]` 生命周期教育：把未成年探索、逐步自主、成年自定义生活与可重新进入学习转化为具体机制；
- `[A]` 公共能力池与任务池：设计最小字段、认证、邀请、拒绝、隐私、删除和审计流程。
- `[A]`、`[V]` 公共服务连续性：用不同服务检验稳定团队、轮换、承诺储备、交接、疲劳恢复和紧急退出边界。
- `[A]`、`[V]` 保障—有限责任—连续性协调：有限互惠原则已经接受，协调专题继续比较具体工时、分配、正当理由、豁免或替代、记录、权益关联与恢复方案。
- `[V]` 劳动任务压力测试：验证平均指标、认证、企业合作与弹性匹配是否隐藏伤害、垄断、岗位替代或负担集中。
- `[A]`、`[V]` 多中心治理与技术中枢：检验唯一入口、算法修改、中心串谋、跨中心裁决、紧急集中和实际退出。
- `[A]`、`[V]` 儿童公共照护：检验稳定关系、家庭与公共责任、儿童逐步自主、反机构化和独立救济。
- `[V]` 道德外包与退出压力测试：检验需求成本、定义权和迁移负担是否集中给低权力承担者。
- `[A]`、`[V]` 公共权力失效纠错：验证证据删除、监督俘获、无力赔偿、关联获利和多机构串谋场景。
- `[A]`、`[V]` 公共合作激励：验证参与成本、意见影响、现实补偿、拒绝和举报保护及有限程序便利。
- `[A]`、`[V]` 十环节权力集中控制：绘制真实控制网络，检验自动复核、外部审计、权限拆分、小规模功能性分离和紧急例外。
