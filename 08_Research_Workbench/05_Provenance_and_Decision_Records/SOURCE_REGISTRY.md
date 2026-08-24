---
title: Source Registry
layer: research
status: stable
version: 0.3.0
updated: 2026-08-25
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
| `SRC-73475D63` | mixed-dialogue-export | `额度用完原因分析.md` 中的新制度设计对话 | [`../06_Current_Round_Source_Notes/2026-08-13_新制度对话提取与路由.md`](../06_Current_Round_Source_Notes/2026-08-13_新制度对话提取与路由.md) | `73475d630d2b907f2cb54ca6bc3bd3e5db31918fb189507fadb821d2ef283d5e` | 用户区块与 AI 回答分别归属；不整篇作为项目结论 |
| `SRC-7EBEDFD7` | ai-heavy-rtf | `Aletheia压力测试.rtf` | [`../06_Current_Round_Source_Notes/2026-08-13_新制度对话提取与路由.md`](../06_Current_Round_Source_Notes/2026-08-13_新制度对话提取与路由.md) | `7ebedfd7e5ad2c008e2af4959cb7bf5d2a0231f29ffbb3f73b1ecb6a3a9cbc08` | 压力测试输入；不自动作为事实结论 |
| `SRC-3A1F7903` | ai-heavy-rtf | `Aletheia四个制度.rtf` | [`../06_Current_Round_Source_Notes/2026-08-13_新制度对话提取与路由.md`](../06_Current_Round_Source_Notes/2026-08-13_新制度对话提取与路由.md) | `3a1f790334ddf847021dd80f9004d714c43613362d8a3ed66375dfdae5404740` | 候选制度与开放问题来源 |
| `SRC-2061DD36` | ai-heavy-rtf | `P1问题和四流图.rtf` | [`../06_Current_Round_Source_Notes/2026-08-13_新制度对话提取与路由.md`](../06_Current_Round_Source_Notes/2026-08-13_新制度对话提取与路由.md) | `2061dd36fa8a7af646770ddc3ba880d3da4d76340a7785966741ddd236e4fe14` | 四流与接口设计来源，须经项目确认 |
| `SRC-4C7E9A12` | project-confirmation | 项目发起者确认 v0.2.0 逐项确认表全部 44 项 | [`PROJECT_INITIATOR_CONFIRMATION_v0.2.0.md`](PROJECT_INITIATOR_CONFIRMATION_v0.2.0.md) | `not-recorded` | 只证明项目内部方向接受，不代表现实公共授权或验证 |
| `SRC-9F4B2C71` | ai-heavy-mixed-dialogue-rtf | `3个专题草案.rtf`，包含职业入口、司法资格岗位、婚姻生育亲职、儿童保障与人身安全讨论及 AI 制度扩写 | [`../06_Current_Round_Source_Notes/2026-08-15_三个专题草案提取与确认.md`](../06_Current_Round_Source_Notes/2026-08-15_三个专题草案提取与确认.md) | `ca1087e82a7b2920ba77f7a22f02c2102b53f536b697bd316d46c78fea42f8ce` | 用户方向、AI 扩写与参数混合；只采用经逐条确认的压缩命题，不整篇升级 |
| `SRC-1D6A8E43` | project-confirmation | 项目发起者对三个专题 v0.3 逐条确认表 P1—P10、J1—J11、F1—F12、S1—S4 共 37 项选择全部接受 | [`PROJECT_INITIATOR_CONFIRMATION_v0.2.2.md`](PROJECT_INITIATOR_CONFIRMATION_v0.2.2.md) | `not-recorded` | 只确认项目内部方向；不确认参数、法律效力、现实授权或经验效果 |
| `SRC-C49CCC9B` | project-direction-and-confirmation | 项目发起者确认个人需求责任、共同脆弱性、非等级互助、跨时间传递、基本照护不计功和不制造感恩服从，并要求加入项目 | [`PROJECT_DECISION_CONFIRMATIONS.md`](PROJECT_DECISION_CONFIRMATIONS.md) | `not-recorded` | 只确认 `PCR-C49CCC` 与 `D-021` 所列项目方向；不确认 AI 扩写、现实机制或法律参数 |
| `SRC-5A8E1C42` | ai-heavy-rtf | `掌权者漏洞治理.rtf`，扩展项目生命周期、全成本、监督独立、外包与机构责任等候选机制 | [`../06_Current_Round_Source_Notes/2026-08-15_公共权力纠错与合作激励来源确认.md`](../06_Current_Round_Source_Notes/2026-08-15_公共权力纠错与合作激励来源确认.md) | `f7e59fea153b5047dc73da07576df882968fea9c08e874f78ca21a5701dacfa0` | AI 结构化为主；只作为候选机制来源，不整篇升级 |
| `SRC-B79D3F06` | ai-heavy-pasted-draft | 本轮粘贴的外部证据、替代调查、先行修复、利益追缴及合作激励扩展稿 | [`../06_Current_Round_Source_Notes/2026-08-15_公共权力纠错与合作激励来源确认.md`](../06_Current_Round_Source_Notes/2026-08-15_公共权力纠错与合作激励来源确认.md) | `9884ba41383e502f396309b3fb7bf2328c7064b35e6baed013c3e530adedbe97` | 原稿含未确认参数和风险机制；以 v0.2.4 逐项表为采用边界 |
| `SRC-41C7A9D2` | project-confirmation | 项目发起者对 v0.2.4 的 G-01—G-20、C-01—C-14 逐项建议回复“全部接受” | [`PROJECT_INITIATOR_CONFIRMATION_v0.2.4.md`](PROJECT_INITIATOR_CONFIRMATION_v0.2.4.md) | `not-recorded` | 确认各项按建议状态成立；不等于原材料逐句确认、现实授权或机制有效性证明 |
| `SRC-E4A91C72` | project-direction-and-confirmation | 项目发起者提出十环节权力集中控制矩阵、三级风险与自动纠偏规则，并明确要求正式纳入项目 | [`PROJECT_INITIATOR_CONFIRMATION_v0.2.5.md`](PROJECT_INITIATOR_CONFIRMATION_v0.2.5.md) | `not-recorded` | 确认矩阵框架和触发方向；具体阈值、机构、程序和效果保持 `draft`，不构成现实公共授权 |
| `SRC-6D2A8F31` | project-direction-and-confirmation | 项目发起者要求以周期性基础责任账户、公共贡献履历和领域限定的专业可靠性档案取代 `C-13` | [`PROJECT_INITIATOR_CONFIRMATION_v0.2.6.md`](PROJECT_INITIATOR_CONFIRMATION_v0.2.6.md) | `not-recorded` | 确认 `D-024` 的三分结构和用途限定；不确认公式、周期、达标线、权益清单、后果参数或现实公共授权 |
| `SRC-CE7F7BC6` | ai-review-markdown | 用户提供的《第一原则.md》十一公理评审稿 | [`../06_Current_Round_Source_Notes/2026-08-16_责任积分与有限互惠公共责任机制整合.md`](../06_Current_Round_Source_Notes/2026-08-16_责任积分与有限互惠公共责任机制整合.md) | `ce7f7bc6260e802f51249e51ade30e00313caa7ac385186272cca8bc8596cf42` | 与现行总纲比对，不整篇替换；只吸收经本轮确认且与当前结构兼容的边界 |
| `SRC-476C8C48` | ai-heavy-rtf | 用户提供的《有限互惠公共责任机制草案 v0.1.rtf》及其照护、医疗场景扩写 | [`../06_Current_Round_Source_Notes/2026-08-16_责任积分与有限互惠公共责任机制整合.md`](../06_Current_Round_Source_Notes/2026-08-16_责任积分与有限互惠公共责任机制整合.md) | `476c8c48ec37c15f8189523bedb7370b7ec5d078dc45104aee67463a298de171` | 候选机制来源；法律化条文、案例、参数和“取消责任积分”不自动升级 |
| `SRC-A2D7F914` | project-direction-and-confirmation | 项目发起者确认责任积分三个目的、年度额度与任务系数、年度清零、领域累计贡献、质量评价和领域专业参考摘要，并要求加入项目 | [`PROJECT_INITIATOR_CONFIRMATION_v0.2.7.md`](PROJECT_INITIATOR_CONFIRMATION_v0.2.7.md) | `not-recorded` | 只确认 `D-025` 的结构方向；具体数值、算法、后果和现实授权保持开放 |
| `SRC-5E32B8C1` | project-direction-and-confirmation | 项目发起者要求增加独立验证状态维度，并制作权力—责任—决策交叉一致性表 | [`PROJECT_INITIATOR_CONFIRMATION_v0.2.8.md`](PROJECT_INITIATOR_CONFIRMATION_v0.2.8.md) | `not-recorded` | 只确认 `D-026` 的项目治理与交叉审计方向；不证明任何机制已经现实验证 |
| `SRC-9F3A72C4` | project-direction-and-confirmation | 项目发起者要求选择两个边界明确的历史案例、形成探索性外部讨论与反馈登记，并按对第一原则的支撑关系排序原典核查 | [`PROJECT_INITIATOR_CONFIRMATION_v0.2.9.md`](PROJECT_INITIATOR_CONFIRMATION_v0.2.9.md) | `not-recorded` | 只确认 `D-027` 的工作方向；不逐句确认案例和探索稿，也不代表外部反馈已经发生 |
| `SRC-4B788D7F` | mixed-shared-conversation | 项目发起者提供的需求归属、公众第一责任与私人需求责任对话；页面具有 user / assistant 角色标记 | [`../06_Current_Round_Source_Notes/2026-08-20_需求归属与公共需求责任来源确认.md`](../06_Current_Round_Source_Notes/2026-08-20_需求归属与公共需求责任来源确认.md) | `not-recorded` | 只有 user-role 语句可证明作者方向；AI 回答中的固定分类、角色责任表、判据和机制只作候选重构，不整体升级 |
| `SRC-2622ABAF` | project-direction-and-confirmation | 项目发起者本轮提供上述对话并要求据此修正公共需求责任定义、整理新的项目文档 | [`PROJECT_DECISION_CONFIRMATIONS.md`](PROJECT_DECISION_CONFIRMATIONS.md) | `not-recorded` | 只确认 `PCR-A18D8A` 与 `D-028` 所列方向；不逐句确认 AI 回答、编辑重构或任何实施参数 |
| `SRC-6D86EDE1` | mixed-dialogue-export | 公共决定、具体责任分配、执行授权及专业能力与轮换讨论的本地 Markdown 对话导出 | [`../06_Current_Round_Source_Notes/2026-08-21_三份对话与制度白皮书整合边界.md`](../06_Current_Round_Source_Notes/2026-08-21_三份对话与制度白皮书整合边界.md) | `6d86ede19c370fd7edb39fe3e70027f2038de7e89411623d7cab543d3ac47f15` | 用户旧稿、用户直接说明、被粘贴反馈与 AI 回答分别归属；专业学习、轮换、认证、退出和积分只作候选机制 |
| `SRC-2FBF8D1E` | mixed-dialogue-export | 需求归属与公共需求第一责任对话的本地 Markdown 导出，是 `SRC-4B788D7F` 的替代表征 | [`../06_Current_Round_Source_Notes/2026-08-21_三份对话与制度白皮书整合边界.md`](../06_Current_Round_Source_Notes/2026-08-21_三份对话与制度白皮书整合边界.md) | `2fbf8d1e85a1dba5b0b9b50d46adf3a3e64eb709875d6aaae2a6fae48c795c73` | 增加本地导出哈希，不形成第二项决定，也不扩大 `D-028` 的确认范围 |
| `SRC-030E9D25` | mixed-dialogue-export | 人、自由、自主、社会性、自主时间与制度总论衔接讨论的本地 Markdown 对话导出 | [`../06_Current_Round_Source_Notes/2026-08-21_三份对话与制度白皮书整合边界.md`](../06_Current_Round_Source_Notes/2026-08-21_三份对话与制度白皮书整合边界.md) | `030e9d2546c5d4d25e637553722211f3d94efcd4d2d6323b9355c2ca905951b9` | 作者候选稿、用户方向、图片、AI 总论与 AI 架构分别处理；事实、公式、版本和成熟度不整体升级 |
| `SRC-8B21C4D0` | project-integration-direction | 项目发起者要求区分附件内指令与当前请求，整合三份文件并重新修订项目白皮书 | [`../06_Current_Round_Source_Notes/2026-08-21_三份对话与制度白皮书整合边界.md`](../06_Current_Round_Source_Notes/2026-08-21_三份对话与制度白皮书整合边界.md) | `not-recorded` | 授权本轮编辑与建立白皮书草案；不等于逐句接受附件中的 AI 回答、外部反馈、事实断言或机制参数 |
| `SRC-4A9B7737` | mixed-dialogue-export | 《公共决定的三步》扩展版 Markdown 对话导出 | [`../06_Current_Round_Source_Notes/2026-08-23_十一份材料提取与整合边界.md`](../06_Current_Round_Source_Notes/2026-08-23_十一份材料提取与整合边界.md) | `d6b39269eeaba0aaa06958ef5c1e49227c719bbcdbd962bb932cb1030da81f20` | 与 `SRC-6D86EDE1` 重叠；新增尾段均为 AI 回答，不扩大作者确认或现行三步模型 |
| `SRC-36B8328B` | mixed-dialogue-export | 《制度衔接分析》扩展并重新导出的 Markdown 对话 | [`../06_Current_Round_Source_Notes/2026-08-23_十一份材料提取与整合边界.md`](../06_Current_Round_Source_Notes/2026-08-23_十一份材料提取与整合边界.md) | `67f20963f16c98fbad410b28cfc7159d009b42c49b378ae9ed4e218b23879545` | 用户方向、第三方转贴、图片和 AI 架构分别归属；只提取和平与主体性的作者语言及转型研究问题 |
| `SRC-71AADD11` | mixed-dialogue-export | 《政治系统模型解释》中的需求、能力、事实权力与历史解释讨论 | [`../06_Current_Round_Source_Notes/2026-08-23_十一份材料提取与整合边界.md`](../06_Current_Round_Source_Notes/2026-08-23_十一份材料提取与整合边界.md) | `a8c68d0bb8cd559444a8a170ae648db7a23cfdeaf3f6cd0b47628cbd16fb7407` | 候选图与 AI 解释不作为现行权力模型；只路由为可证伪的历史与事实权力研究题 |
| `SRC-5EAF92FA` | mixed-gemini-dialogue-export | 《母子替代丈夫关系解析》扩展版对话导出 | [`../06_Current_Round_Source_Notes/2026-08-23_十一份材料提取与整合边界.md`](../06_Current_Round_Source_Notes/2026-08-23_十一份材料提取与整合边界.md) | `0aa2566eaadb02659660223dd01507d262ec0b7fb879fc7833a595345fedf618` | 只提取象征尊崇、私域影响和正式参与的研究问题；心理、宗教、文明与性别通则不升级 |
| `SRC-96A55F12` | mixed-dialogue-export | 《责任积分的利弊分析》扩展版 Markdown 对话导出 | [`../06_Current_Round_Source_Notes/2026-08-23_十一份材料提取与整合边界.md`](../06_Current_Round_Source_Notes/2026-08-23_十一份材料提取与整合边界.md) | `b45d64b430cd6d87f9bf571a9de53cfcb18778bc53001835254d4e90cea97d88` | 为 `D-025` 的作者方向提供后来取得的本地佐证；不替换历史 `not-recorded`，AI 公式与综合信用画像不采用 |
| `SRC-D586AA36` | ai-heavy-mixed-dialogue-export | 《项目完成度与优先级》及其中回贴的机制与长期照护候选稿 | [`../06_Current_Round_Source_Notes/2026-08-23_十一份材料提取与整合边界.md`](../06_Current_Round_Source_Notes/2026-08-23_十一份材料提取与整合边界.md) | `1dac2ade7817ce999d162badce4f3348ac9a748b5070bafb357932dae7ea9645` | 完成率和“测试通过”判断不采用；长期照护只保留为未来内部走查候选，不冒充验证记录 |
| `SRC-8C40AF42` | google-ai-search-transcript | 《欧美国家存在职业歧视吗》搜索对话导出 | [`../06_Current_Round_Source_Notes/2026-08-23_十一份材料提取与整合边界.md`](../06_Current_Round_Source_Notes/2026-08-23_十一份材料提取与整合边界.md) | `578e704c24fac2e5b0cc5186a30f1c59f911cad5eac5dd8150d343d9e688386d` | 搜索回答没有可复核来源清单；只生成职业评价、制度自卫与反向排斥的研究问题，不作事实证据 |
| `SRC-7F523911` | mixed-unverified-essay | 《消失的当事人：牧领权力、匮乏之爱与业力轮回》候选稿 | [`../06_Current_Round_Source_Notes/2026-08-23_十一份材料提取与整合边界.md`](../06_Current_Round_Source_Notes/2026-08-23_十一份材料提取与整合边界.md) | `2e86a601362d61c5e334b114dcb309ea95ed3a6e7fb176b9767c4634411fa3ab` | 问题种子可追溯、成文身份混合；只重写当事人表达与善意代言问题，思想家和文明通则待核查 |
| `SRC-384C102C` | mixed-unverified-essay | 《独裁游戏的变体：从“君子远庖厨”到资本的价格审判》候选稿 | [`../06_Current_Round_Source_Notes/2026-08-23_十一份材料提取与整合边界.md`](../06_Current_Round_Source_Notes/2026-08-23_十一份材料提取与整合边界.md) | `c71faff76cc05a96b92dbbd5b96f71958d336b0d93323062a6bbb47d06ac4380` | 与现行“帮助者被看低”主题高度重叠，不另立正文；历史、原典和文明常量判断不升级 |
| `SRC-E189AD08` | mixed-unverified-essay | 《被异化的价值：当“人”成为“价格”》候选稿 | [`../06_Current_Round_Source_Notes/2026-08-23_十一份材料提取与整合边界.md`](../06_Current_Round_Source_Notes/2026-08-23_十一份材料提取与整合边界.md) | `53a165c8b7d151c02ad3464b26d46290d74884954d18949294b6eae3e1c7ba7e` | 只保留价格越界成人格判断的生活问题；薪资、历史与学者断言须另行核查 |
| `SRC-D1C279AA` | mixed-unverified-essay | 《论人的存在、意义与他者》候选稿 | [`../06_Current_Round_Source_Notes/2026-08-23_十一份材料提取与整合边界.md`](../06_Current_Round_Source_Notes/2026-08-23_十一份材料提取与整合边界.md) | `5191e03b8fde644ec4f4369a62238b087261b8ad1c11a3f001f55b9113d082a0` | 只提取关系、承认与外部评价问题；生物学、神经科学、母婴和黑格尔解释不作现行事实 |
| `SRC-B60C2F17` | project-review-and-confirmation | 项目发起者确认七条公众核心命题、保留有限公共责任个案候选，并确认五篇思想书的中心问题 | [`PROJECT_DECISION_CONFIRMATIONS.md`](PROJECT_DECISION_CONFIRMATIONS.md) | `not-recorded` | 只确认 `PCR-B60C2F` 与 `D-029` 所列范围；不表示全文逐句批准、事实核查、现实验证或实施授权完成 |
| `SRC-74C1E290` | project-work-direction | 项目发起者要求正式建立五个候选机制与现有专题、竞争方案、停止线的交叉表，并依次用夜间急救、长期照护和能源连续性作内部场景走查 | [`../../04_Institution_Design/Project_Aletheia_五机制交叉表.md`](../../04_Institution_Design/Project_Aletheia_五机制交叉表.md) | `not-recorded` | 授权建立研究草案和内部假设走查；不确认竞争方案、场景假设或走查结论，也不构成现实验证、公共决定或实施授权 |
| `SRC-91E4C7A2` | mixed-dialogue-feedback-export | 《制度衔接分析 (2)》后续反馈对话导出，包含公开署名反馈转贴、用户澄清、截图和 AI 分析 | [`../06_Current_Round_Source_Notes/2026-08-24_两篇外发文章新增反馈与整合边界.md`](../06_Current_Round_Source_Notes/2026-08-24_两篇外发文章新增反馈与整合边界.md) | `3a891aacb30947cd2de9b53e8b401db80d29029d4392c92937745b5cedf3a83d` | 只把可辨认的第三方反馈作为反馈输入；用户没有确认 AI 提出的新核心问题、理论分类、标题或桥梁章节 |
| `SRC-A6F2D8B9` | mixed-dialogue-feedback-export | 《公共决定的三步 (2)》反馈扩展导出，包含旧稿、公开回答与截图、用户旧说明、内嵌图片和 AI 分析 | [`../06_Current_Round_Source_Notes/2026-08-24_两篇外发文章新增反馈与整合边界.md`](../06_Current_Round_Source_Notes/2026-08-24_两篇外发文章新增反馈与整合边界.md) | `643d6bec609038f5895f0b1f8791e859185a82088ec06bf38cf62428af04dcff` | 公开反馈按链接或截图身份登记；AI 的“第零步”、新模型链、全民责任积分及默认派工方案不升级 |
| `SRC-5C7E1A84` | project-integration-direction | 项目发起者说明两份文件是原来两篇外发文章的新增反馈与修改，并要求判断怎样补充进项目 | [`../06_Current_Round_Source_Notes/2026-08-24_两篇外发文章新增反馈与整合边界.md`](../06_Current_Round_Source_Notes/2026-08-24_两篇外发文章新增反馈与整合边界.md) | `not-recorded` | 授权反馈整理与兼容性修订；不表示接受第三方意见、AI 扩写、事实主张或新的机制决定 |
| `SRC-8D6B4E21` | author-provided-publication-snapshot | 《公共决定之后，还缺什么？》外发正文的用户提供 Markdown 快照 | [`../07_Validation_Records/Publication_Snapshots/PUB-2026-001_公共决定之后还缺什么_用户提供快照.md`](../07_Validation_Records/Publication_Snapshots/PUB-2026-001_公共决定之后还缺什么_用户提供快照.md) | `19d29995b318d867b0aa867eef681a25547344de9a22fec70fee049d4338ff7f` | 只归档用户提供的外发正文表征；平台编辑历史与精确发布日期待核，不覆盖反馈后修订稿 |
| `SRC-2A9C7F40` | author-provided-publication-snapshot | 《为什么需要责任型社会制度：从意义、承认到劳动与价格》外发正文的用户提供 Markdown 快照；文本可追溯为 ChatGPT 对混合输入生成的整合稿 | [`../07_Validation_Records/Publication_Snapshots/PUB-2026-002_为什么需要责任型社会制度_用户提供快照.md`](../07_Validation_Records/Publication_Snapshots/PUB-2026-002_为什么需要责任型社会制度_用户提供快照.md) | `1927410de97e0a9a6f299f074b324ccd348c385ccc6039eb49fe474b94dbdad3` | 保存项目发起者提供并公开发布的文本；思想素材归属混合，不等于作者独立逐句写作、当前白皮书、事实核查或机制确认 |
| `SRC-C4E8173B` | public-feedback-screenshot | 知乎新增制度工程评论截图，显示公开名称“维拉”及回复上下文 | [`../06_Current_Round_Source_Notes/2026-08-24_两篇外发正文快照与制度工程评论整合边界.md`](../06_Current_Round_Source_Notes/2026-08-24_两篇外发正文快照与制度工程评论整合边界.md) | `e1f7e86a64113d3390cb37924978132be5ead14091e7958ea24f5f6f1729c2ef` | 只证明项目收到截图中的公开评论；真实身份、所属页面、精确时间和 permalink 待核 |
| `SRC-73F2A690` | project-source-mapping-direction | 项目发起者说明两份 Markdown 分别对应两个知乎链接，图片是新增评论，长段文字是另一段 AI 对话建议 | [`../06_Current_Round_Source_Notes/2026-08-24_两篇外发正文快照与制度工程评论整合边界.md`](../06_Current_Round_Source_Notes/2026-08-24_两篇外发正文快照与制度工程评论整合边界.md) | `not-recorded` | 只确认来源映射、角色边界并授权兼容性整理；不确认 AI 建议、评论判断或固定实施路线 |
| `SRC-6B2F8E71` | project-direction-and-confirmation | 项目发起者确认冻结第一原则 v1.0，并要求建立司法解释草案、四份人生周期走查、公共责任缺席候选机制及 40 岁转行首次外部验证方案；生育仅作法律、伦理和匿名情境评审 | [`../06_Current_Round_Source_Notes/2026-08-25_第一原则司法解释人生周期与验证范围确认.md`](../06_Current_Round_Source_Notes/2026-08-25_第一原则司法解释人生周期与验证范围确认.md) | `not-recorded` | 只确认 `D-030`、`D-031`、`PCR-4D7A31` 与 `PCR-E9C2B5` 的范围；不表示机制参数、走查事实、验证结果、法律效力或现实实施许可成立 |
| `SRC-8F6C3A21` | project-release-direction-and-confirmation | 项目发起者要求在内容复核通过后继续公开反馈后三步稿，并把当前项目作为 `v0.3.0` 发布到已确认的公开 GitHub 仓库 | [`PROJECT_INITIATOR_CONFIRMATION_v0.3.0.md`](PROJECT_INITIATOR_CONFIRMATION_v0.3.0.md) | `not-recorded` | 只确认 `D-032`、`PCR-C47D91` 和公开研究快照范围；不等于草案逐句批准、事实核查、验证状态升级、知乎重发或现实实施授权 |

## 当前来源之间的关系

下表只说明表征、版本和讨论关系，不提高证据等级。相同内容在多个文件中出现，不得按多个独立来源累计支持度。

| Source ID | 关系 | 相关 Source ID | 审计含义 |
|---|---|---|---|
| `SRC-4A9B7737` | `extended-export-of` | `SRC-6D86EDE1` | 新导出覆盖旧导出并增加 AI 尾段；重叠内容只计一次 |
| `SRC-36B8328B` | `extended-reexport-of` | `SRC-030E9D25` | 内容扩展且导出形式有变化；不是对旧材料的独立佐证 |
| `SRC-96A55F12` | `contains-later-local-representation-of` | `SRC-A2D7F914` | 保存 `D-025` 作者方向的后来本地表征；不倒改原确认来源，也不重复计证据 |
| `SRC-E189AD08` | `embedded-representation-in` | `SRC-36B8328B` | 同一候选文章也出现在扩展对话用户区块中；两者不是独立作者确认 |
| `SRC-D1C279AA` | `embedded-representation-in` | `SRC-36B8328B` | 同一候选文章也出现在扩展对话用户区块中；两者不是独立作者确认 |
| `SRC-71AADD11` | `discusses` | `SRC-7F523911`、`SRC-384C102C`、`SRC-E189AD08`、`SRC-D1C279AA` | 后段是 AI 对四篇候选文章的衔接评论，不是四份文章的外部复核 |
| `SRC-91E4C7A2` | `follow-up-discussion-of` | `SRC-36B8328B` | 新文件是后续局部反馈线程，不是旧导出的覆盖版或独立作者确认 |
| `SRC-91E4C7A2` | `discusses` | `SRC-E189AD08`、`SRC-D1C279AA` | 反馈与 AI 分析讨论价格、人格、存在及制度衔接；不构成对两篇候选正文的独立事实佐证 |
| `SRC-A6F2D8B9` | `extended-feedback-export-of` | `SRC-4A9B7737` | 新导出加入公开反馈、截图及后续 AI 分析；重叠旧稿与旧对话只计一次 |
| `SRC-8D6B4E21` | `publication-snapshot-of-text-in` | `SRC-4A9B7737` | 用户提供的公开正文与旧混合导出中的稿件同源；不作为第二项作者确认 |
| `SRC-2A9C7F40` | `publication-variant-derived-from` | `SRC-36B8328B` | 公开正文来自混合导出中的 AI 整合稿并形成发布变体；不倒称为独立作者原稿 |
| `SRC-A6F2D8B9` | `feedback-about` | `SRC-8D6B4E21` | 反馈扩展导出讨论第一篇外发正文；重叠内容和反馈不累计为多个独立发布版本 |
| `SRC-91E4C7A2` | `feedback-about` | `SRC-2A9C7F40` | 后续反馈线程讨论第二篇外发正文；AI 分析不等于外部复核 |
| `SRC-C4E8173B` | `provisionally-comment-on` | `SRC-2A9C7F40` | 按现有讨论链暂关联第二篇；截图缺页面地址，取得 permalink 后复核 |
| `SRC-73F2A690` | `confirms-publication-mapping-for` | `SRC-8D6B4E21`、`SRC-2A9C7F40` | 只确认文件与问题页的映射，不提高正文作者或事实等级 |

## v0.3.0 外部研究来源

| Source ID | 来源类别 | 最小描述 | 稳定入口 | 内容哈希 | 使用边界 |
|---|---|---|---|---|---|
| `SRC-A13F6C90` | official-law | 《中华人民共和国社会保险法》全国人大官网文本 | <https://www.npc.gov.cn/npc/c2/c10134/201905/t20190522_175815.html> | `not-recorded` | 仅作 40 岁转行现制国家级社会保险法律起点；具体离职衔接、待遇与办理仍须选定地域并核查当期规则 |
| `SRC-5D0B7E42` | official-law | 《中华人民共和国就业促进法》人力资源和社会保障部官网文本 | <https://www.mohrss.gov.cn/xxgk2020/fdzdgknr/zcfg/fl/202011/t20201102_394626.html?xxgkhide=1> | `not-recorded` | 用于核查自主择业、平等就业、公共就业服务与职业培训的国家级法律基线；不证明现实可及性或地方执行效果 |
| `SRC-92C4F1D8` | official-law | 《中华人民共和国职业教育法》教育部官网文本 | <https://www.moe.gov.cn/jyb_sjzl/sjzl_zcfg/zcfg_jyfl/202204/t20220421_620064.html> | `not-recorded` | 用于核查职业教育与终身学习的法律入口；具体培训容量、学费、认证和就业结果仍须外部复核 |
| `SRC-3E8A6B51` | official-policy | 人力资源和社会保障部关于健全全国统一社会保险公共服务平台的意见（2025） | <https://www.mohrss.gov.cn/xxgk2020/fdzdgknr/qt/gztz/202503/t20250318_538687.html> | `not-recorded` | 仅说明国家层面对转移接续和灵活就业参保服务的当前政策方向；不据此假定各地流程已经无缝或保障完全连续 |

## v0.2.9 外部研究来源

| Source ID | 来源类别 | 最小描述 | 稳定入口 | 内容哈希 | 使用边界 |
|---|---|---|---|---|---|
| `SRC-4E7B2A19` | published-research | Polly Wiessner 关于 Ju/’hoansi 狩猎、`hxaro` 和长期互惠网络的研究 | <https://doi.org/10.1016/S1090-5138(02)00096-X>；<https://wiki.santafe.edu/images/d/df/Wiessner.pdf> | `not-recorded` | 特定地区、时期和样本，不代表全部 Ju/’hoansi、采集社会或史前人类 |
| `SRC-9D31C6F4` | published-research | Robert K. Hitchcock 关于多贝和 XaiXai 土地、领导与资源权的研究 | <https://cas-sca.journals.uvic.ca/index.php/anthropologica/article/download/2304/2083/3315> | `not-recorded` | 后期资料用于检验外部资源权条件，不倒推早期全部内部制度 |
| `SRC-6A8F13D2` | published-research | Anjel Errasti 对 Fagor 跨国合作社结构的参与观察与访谈研究 | <https://revistas.ucm.es/index.php/REVE/article/download/43385/41057> | `not-recorded` | 论文在最终破产前完成，不能单独重建破产决策全过程 |
| `SRC-2C74E9B5` | organization-self-report | MONDRAGON Corporation 2014 年报 | <https://www.mondragon-corporation.com/wp-content/themes/mondragon/docs/eng/annual-report-2014.pdf> | `not-recorded` | 组织自我报告；保留成员、时点和“就业解决方案”口径 |
| `SRC-7F15B8C3` | post-crisis-research | 蒙德拉贡大学出版的法戈尔危机后反思文集 | <https://doi.org/10.48764/ec2h-1s59> | `not-recorded` | 作为危机后研究入口，不替代独立统计或全部受影响者材料 |

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
| `SRC-8D4F2B90` | [`道德与不公的悖论_提取笔记.md`](../04_Source_Extractions/道德与不公的悖论_提取笔记.md)；本轮复核见 [`2026-08-15_个人需求责任与非等级互助来源确认.md`](../06_Current_Round_Source_Notes/2026-08-15_个人需求责任与非等级互助来源确认.md) | mixed dialogue; user direction relatively traceable; original file obtained 2026-08-15 | `c16989c8511e6f0de8ba8f5a1885388ba0fd65a459140b81d24f886bbcaebf53` |
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
