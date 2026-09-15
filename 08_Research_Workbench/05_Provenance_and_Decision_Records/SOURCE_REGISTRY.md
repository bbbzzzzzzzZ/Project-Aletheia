---
title: Source Registry
layer: research
status: stable
version: 0.4.0
updated: 2026-09-15
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
| `SRC-57C2A8D4` | project-scenario-selection-and-confirmation | 项目发起者把 40 岁转行首次外部验证收窄为中国大陆上海市、40 岁普通企业职工主动离职后转向养老护理员 | [`../06_Current_Round_Source_Notes/2026-08-26_40岁转行上海养老护理员范围与现制来源.md`](../06_Current_Round_Source_Notes/2026-08-26_40岁转行上海养老护理员范围与现制来源.md) | `not-recorded` | 只确认 `D-033`、`PCR-57C2A8` 和场景范围；不确认性别、户籍、学历、住房、储蓄、具体用工、上海规则解释、参与结果或方案效果 |
| `SRC-3F8A6D12` | project-review-and-confirmation | 项目发起者回复“六项按建议确认”，确认上海养老护理员首轮比较所用的六项研究假设 | [`PROJECT_DECISION_CONFIRMATIONS.md`](PROJECT_DECISION_CONFIRMATIONS.md) | `not-recorded` | 只确认 `PCR-3F8A6D`、`D-034` 和六项比较设置；不是现实人物陈述，不确认政策事实、方案效果、参与结果或实施授权 |
| `SRC-5F8A2C19` | project-initiator-theory-confirmation | 项目发起者确认哲学理论补充的四类命题层级、弱者选择权、创新公共回流、劳动主体承认与冲突不可逆伤害边界 | [`../06_Current_Round_Source_Notes/2026-09-15_哲学理论五项桥梁确认.md`](../06_Current_Round_Source_Notes/2026-09-15_哲学理论五项桥梁确认.md) | `not-recorded` | 只确认 `D-035`、`PCR-6E4A91B2` 和理论桥梁方向；不修改第一原则 v1.0，不证明经验假设，不确认机制参数、现实授权或制度效果 |
| `SRC-4E0A1F92` | project-release-direction-and-confirmation | 项目发起者要求整理 `v0.4.0` 发布包，并以“Aletheia 哲学理论 v0.4.0：人的主体性、公共责任与制度边界”为题更新到公开 GitHub 仓库 | [`PROJECT_INITIATOR_CONFIRMATION_v0.4.0.md`](PROJECT_INITIATOR_CONFIRMATION_v0.4.0.md) | `not-recorded` | 只确认 `D-036`、`PCR-4E0A1F` 与 v0.4.0 发布范围；不提升草案、事实核查、验证状态或现实授权 |
| `SRC-7A3C5E91` | mixed-dialogue-research-log | 《解释下一步含义.md》连续调查对话导出，包含项目回贴、用户网络观察、网页截图和 AI 分析 | [`../06_Current_Round_Source_Notes/2026-08-30_上海养老护理调查对话提取与证据分层.md`](../06_Current_Round_Source_Notes/2026-08-30_上海养老护理调查对话提取与证据分层.md) | `2281ab4d548860a7d14bcca5626a1dfd092c6d8e4d7783a2c413aff87a2a7fb4` | 用户直接观察只作待核研究线索；回贴文档、截图与 AI 回答分别归属，不把网络数字、行业通则或 AI 因果解释升级为外部验证 |
| `SRC-E6C1A7D4` | project-research-input | 项目发起者提供“上海长护险居家上门照护 VS 养老机构照护成本对照表”，并要求结合两份 PDF 继续调查 | [`../06_Current_Round_Source_Notes/2026-08-31_上海长护险成本表与两份招聘PDF核对.md`](../06_Current_Round_Source_Notes/2026-08-31_上海长护险成本表与两份招聘PDF核对.md) | `not-recorded` | 成本表只是待核输入；不确认政策时点、床位与保姆价格、机构成本占比、利润或社会成本结论 |
| `SRC-2B6F9A41` | author-provided-recruitment-screenshot-pdf | 两页长护险居家护理招聘应用截图 PDF | [`../06_Current_Round_Source_Notes/2026-08-31_上海长护险成本表与两份招聘PDF核对.md`](../06_Current_Round_Source_Notes/2026-08-31_上海长护险成本表与两份招聘PDF核对.md) | `b9533d5c2b20a113f47d533fa3d62c914e9f34a7bd98f86e00615079979a516c` | 只证明出现过 8000—10000 元、40—43 元/小时、个人商业保险等招聘宣传；缺稳定 URL、雇主确认和合同，不复制个人资料 |
| `SRC-5C8E1D73` | author-provided-recruitment-repost-pdf | 两页“上海虹口区家床护理员招聘”网络转载 PDF | [`../06_Current_Round_Source_Notes/2026-08-31_上海长护险成本表与两份招聘PDF核对.md`](../06_Current_Round_Source_Notes/2026-08-31_上海长护险成本表与两份招聘PDF核对.md) | `a96d0c746a667a01a648ac4c9a1d37c6f675becf38e7d07067693f449b5a6b6f` | 页面自行声明不保证真实性；40 元/小时、每日 7—9 单和月入约万元只作招聘声称，不保存电话、二维码或个人社交账号 |
| `SRC-6A9E3D17` | project-initiator-follow-up-observation | 项目发起者对培训收费、培训期无工资、养老机构工资构成、入职当月社保、跨机构连续六个月与补贴重新计时的六项补充说明 | [`../06_Current_Round_Source_Notes/2026-09-13_上海养老护理转行现制补充确认.md`](../06_Current_Round_Source_Notes/2026-09-13_上海养老护理转行现制补充确认.md) | `not-recorded` | 只作为现制核验线索和现金流字段；不代表官方规则、企业普遍事实、个人申请结果或验证结论 |
| `SRC-2B7D9C41` | project-direction-and-scope-clarification | 项目发起者澄清 A/B/C 比较的是三种制度安排而非三个岗位，指出工资提高的财政承担和 Aletheia 长期教育转型不能预先假定，并要求当前转向合同核验 | [`../06_Current_Round_Source_Notes/2026-09-14_40岁转行比较对象与合同核验范围确认.md`](../06_Current_Round_Source_Notes/2026-09-14_40岁转行比较对象与合同核验范围确认.md) | `not-recorded` | 只确认比较范围和 P0 合同核验方向；不证明财政可行性、工资效果或 Aletheia 方案效果 |
| `SRC-7C2E4A91` | project-initiator-follow-up-observation | 项目发起者澄清招聘薪资常以合计区间宣传，普通养老机构就业不必然要求证书，长护险资格与考证补贴是分支条件 | [`../06_Current_Round_Source_Notes/2026-09-14_养老护理证书与招聘薪酬信息边界补充.md`](../06_Current_Round_Source_Notes/2026-09-14_养老护理证书与招聘薪酬信息边界补充.md) | `not-recorded` | 只作为岗位路径和证据缺口线索；不代表所有机构、长护险岗位或补贴经办结果 |
| `SRC-4A7B9C26` | official-local-pdf | 《上海市养老服务机构养老护理员入职补贴实施办法》（沪民规〔2022〕14号）本地 PDF | [`../06_Current_Round_Source_Notes/2026-09-14_上海养老护理入职补贴与机构岗位样本核对.md`](../06_Current_Round_Source_Notes/2026-09-14_上海养老护理入职补贴与机构岗位样本核对.md) | `dbea0e1c558958c983b88c0cdc1103ee5fa083c26f41f989c4165c526a59fac2` | 官方入职补贴规则；证明适用条件、五年 3/4 万和 1/3/5 年 20/40/40 支付，不证明普通岗位统一准入、培训期工资或即时现金流 |
| `SRC-8D1E6A43` | author-provided-policy-infographic | 用户提供的《养老补贴.png》，混合展示技能提升补贴与在岗激励补贴 | [`../06_Current_Round_Source_Notes/2026-09-14_上海养老护理入职补贴与机构岗位样本核对.md`](../06_Current_Round_Source_Notes/2026-09-14_上海养老护理入职补贴与机构岗位样本核对.md) | `62c68f3e3a569db40b5c7e724c69c1b5f525e835feab52245b7b31999e32a58c` | 二级整理线索；金额、期限、阶段比例须与当期官方目录和经办答复交叉核对，不与正式入职补贴合并 |
| `SRC-9C5F2A71` | author-provided-recruitment-screenshots | 用户提供的上海养老院/养老护理员招聘页面截图组 | [`../06_Current_Round_Source_Notes/2026-09-14_上海养老护理入职补贴与机构岗位样本核对.md`](../06_Current_Round_Source_Notes/2026-09-14_上海养老护理入职补贴与机构岗位样本核对.md) | `not-recorded` | 只记录 5–8K、5–6K、6–8K、13 薪、包吃住及证书等广告声称；不证明法定雇主、社保、基础/绩效结构、实际工时或到手收入 |

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
| `SRC-4E7C1A92` | `local-file-representation-of` | `SRC-73E1A9D5` | 用户提供的 8 页 PDF 是同一上海定向培训通知的本地表征；只增加文件哈希与逐页核对，不作为第二份独立政策证据 |

## Unreleased 外部研究来源

| Source ID | 来源类别 | 最小描述 | 稳定入口 | 内容哈希 | 使用边界 |
|---|---|---|---|---|---|
| `SRC-18D4C7A9` | official-law | 《中华人民共和国劳动合同法》现行公开文本 | <https://www.samr.gov.cn/zw/zfxxgk/fdzdgknr/bgt/art/2023/art_0abfdd261c03417b949df19d869add8d.html> | `not-recorded` | 只作普通主动辞职、解除证明、关系转移和交接起点；不替代个案合同、补偿、服务期或争议判断 |
| `SRC-6F2B9E41` | official-local-policy | 上海灵活就业人员参加职工养老、医疗保险通知 | <https://www.shanghai.gov.cn/gwk/search/content/t0035_1415199> | `not-recorded` | 只说明实际灵活就业人员的登记与自缴入口；不认定脱产学习自动构成灵活就业 |
| `SRC-90A3D5C7` | official-local-policy-explanation | 上海 2026 年失业保险金申领政策问答 | <https://rsj.sh.gov.cn/tzcjd_17352_17352/20260812/t0035_1443066.html> | `not-recorded` | 核对非因本人意愿中断就业等条件；不据此否定其他就业服务或困难支持 |
| `SRC-2C8F4B16` | official-local-rule | 上海职工基本医疗保险办法实施细则 | <https://ybj.sh.gov.cn/gfxwj/20250905/6173c838284f43c3b4d8c8d4513364ed.html> | `not-recorded` | 核对灵活就业医保等待期与三个月内切换；实际身份和月份仍须经办复核 |
| `SRC-73E1A9D5` | official-local-policy | 上海 2026 年定向培训通知 | <https://rsj.sh.gov.cn/tjypx_17728/20260717/t0035_1442545.html> | `not-recorded` | 核对培训对象、项目、用人协作和补贴兑现；不等于普遍免费脱产学习或个人直接领款 |
| `SRC-B4D6F208` | official-local-guidance | 上海养老护理员考证与补贴官方说明 | <https://www.shanghai.gov.cn/xbhygq/20260527/cede1eb2a761451cab7beb911d61aabe.html> | `not-recorded` | 核对认可培训、评价、证书和就业后补贴入口；与正式办法冲突时以正式办法为基线 |
| `SRC-3B7A5C94` | official-local-policy | 上海市职业技能提升补贴目录（2026年） | <https://www.shanghai.gov.cn/gwk/search/content/t0035_1438001> | `not-recorded` | 只核对目录入口和实施日期；不单独证明个人资格、申请成功或培训免费 |
| `SRC-5A7C1E93` | official-local-rule | 上海市养老服务机构护理员入职补贴实施办法 | <https://www.shanghai.gov.cn/rcjysj/20250606/2e0ee4798f7742b4a2fa3899f4c9e6a7.html> | `not-recorded` | 核对合同、社保、学历、一线工作和分段发放；不是辞职当月过渡收入 |
| `SRC-E9B3D620` | official-local-rule | 上海市养老护理员激励补贴实施办法 | <https://mzj.sh.gov.cn/MZ_zhuzhan2739_0-2-8-15-55/20241231/0e5bea31283d453ba106b2739a347991.html> | `not-recorded` | 核对合同、社保、证书和留任激励；不得折抵正常工资或冒充转行过渡支持 |
| `SRC-C6A1F835` | official-local-rule | 上海市长期护理保险试点办法 | <https://www.shanghai.gov.cn/202602bgtwj/20260122/83a46aaeed2448e4a54666ceb3d663df.html> | `not-recorded` | 只用于定点长期护理服务分支；不扩展成全部养老护理岗位统一准入 |
| `SRC-D8E4A271` | official-local-law | 《上海市养老服务条例》 | <https://www.shanghai.gov.cn/ylfwflfg/20230420/dfd20f4a7eb94bc186ae1bdc6ab8d3e4.html> | `not-recorded` | 核对备案机构、人员、健康、培训、劳动保护、老人权益和安全责任；不替代岗位实践材料 |
| `SRC-6A4D9C25` | official-local-policy-explanation | 上海就业困难人员认定条件说明 | <https://rsj.sh.gov.cn/tcjjyyhzc_17545/20260127/t0035_1438274.html> | `not-recorded` | 只用于性别、年龄、户籍、连续失业与公共就业服务条件的敏感性分支；不认定本场景人物自动符合 |
| `SRC-A5C9D317` | official-local-service-guidance | 上海公共职业指导服务说明 | <https://rsj.sh.gov.cn/trdhy_17355/20250512/t0035_1432417.html> | `not-recorded` | 核对现制已有政策、市场、职业方向、培训信息和机构推荐入口；不证明个人实际取得培训或岗位 |
| `SRC-7D2E8B45` | official-local-rule | 上海 2026 年阶段性职工医保费率通知 | <https://www.shanghai.gov.cn/gwk/search/content/921e047144694b61b6df8ca0c5ef2cfc> | `not-recorded` | 只用于核对灵活就业职工医保 10% 阶段性费率及有效期；未来费率变化须重算 |
| `SRC-F3A6C281` | official-local-policy-explanation | 上海 2026 年 7 月起社会保险缴费基数上下限说明 | <https://rsj.sh.gov.cn/tdjjf_17554/20260824/t0035_1443297.html> | `not-recorded` | 只用于按当前下限估算养老与医保自缴现金成本；计算值不是固定政策定额 |
| `SRC-1B9E4D76` | official-local-rule | 上海养老护理员在岗培训指导意见 | <https://www.shanghai.gov.cn/202323bmgfxwj/20231211/9ecf9828ae5644b38cb1d4f3d4806615.html> | `not-recorded` | 核对在岗培训覆盖无技能等级证书护理员及机构培训责任；不等于所有机构现实上无证录用或允许独立任务 |
| `SRC-8C5A2F30` | official-local-agency-response | 上海市民政局关于养老护理人才队伍建设的代表建议答复 | <https://mzj.sh.gov.cn/MZ_zhuzhan2595_0-2-8-2593/20240530/15f73f0e4c424363acb8a20ddffb1141.html> | `not-recorded` | 只辅助核对普通养老服务机构可先入职再培训带教的市级说明；具体雇主要求、健康证明、长护险资格和任务授权仍分开 |
| `SRC-4E7C1A92` | author-provided-official-pdf-copy | `沪人社规〔2026〕9号` 上海定向培训通知的用户提供 PDF 副本 | [`../06_Current_Round_Source_Notes/2026-08-26_养老护理在线课程与定向培训通知来源核对.md`](../06_Current_Round_Source_Notes/2026-08-26_养老护理在线课程与定向培训通知来源核对.md) | `39708ee1f63e3eedd363d67c2e5447083f4de30874fb82b431a783e990d09db1` | 是 `SRC-73E1A9D5` 的本地表征；只核对通知文本，不复制用户本机路径，也不重复累计证据 |
| `SRC-2D9F6B40` | official-platform-reference | 人社部门官方页面所指向的“中国职业培训在线”及国家职业技能标准查询入口 | <https://px.class.com.cn/>；<https://www.mohrss.gov.cn/wap/xw/rsxw/202106/t20210602_415698.html> | `not-recorded` | 只证明平台与职业标准查询入口及养老护理资源线索；不证明 2026 年所有课程全量免费、课程记录或证书“国网可查” |
| `SRC-6C3A8E15` | official-training-platform | 就业创业和职业培训在线服务平台及养老护理员公开课程页 | <https://jc.mohrss.gov.cn/>；<https://jc.mohrss.gov.cn/lesson/25>；<https://jc.mohrss.gov.cn/lesson/34>；<https://jc.mohrss.gov.cn/lesson/50> | `not-recorded` | 核对公开课时、目录和课程说明；页面价格、试看或课程完成不自动证明普遍免费、上海认可培训、技能等级证书或独立上岗资格 |
| `SRC-4F8B2D61` | official-occupational-research-summary | 上海市政府转载的《2025年养老护理员职业发展报告》摘要 | <https://www.shanghai.gov.cn/nw4411/20251218/3507519749744088bd9b21f87ff6c81b.html> | `not-recorded` | 只用于全国样本的年龄、性别、青年占比和职业发展问题；预测缺口不等于上海已测缺口，也不证明单一流失原因 |
| `SRC-5E2A9C74` | official-public-recruitment-sample | 上海市政府公开的一则养老护理员招聘信息 | <https://www.shanghai.gov.cn/nw17239/20260813/adbaee5f54f34bbe889730fa7051253b.html> | `not-recorded` | 只作一个雇主的工资、岗位数量、职责和资格要求样本；不得外推为全市典型工资、班次或准入 |
| `SRC-B7E2C491` | official-local-service-list | 上海长期护理保险定点评估与护理服务机构名单（截至 2026 年 7 月 31 日） | <https://ybj.sh.gov.cn/ybdt/20260814/d2bb1c1a07c64c5881ba1c0c92679363.html> | `not-recorded` | 只核对评估与服务机构数量及名单时点；不证明实时接单容量、用工方式、订单分配或服务质量 |
| `SRC-8A4D6F20` | official-local-policy-explanation | 上海长期护理保险居家照护待遇与支付示例 | <https://ybj.sh.gov.cn/ybdt/20230131/3672a3bb6dcf4ec8942f8724a4c92f8b.html> | `not-recorded` | 只用于官方示例中的基金 90% 与个人 10% 支付关系；不能由服务费直接反推劳动者报酬、机构成本、抽成或利润 |
| `SRC-1D7F3B82` | official-local-enforcement-case | 上海长期护理保险定点护理机构违规结算查处案例 | <https://ybj.sh.gov.cn/ybdt/20250606/9c4682d776ef4ceabed7f8d1a55db721.html> | `not-recorded` | 证明无服务结算、时长不足、资格冒用和虚假上传风险可以发生；单一案件不证明行业发生率或普遍性 |
| `SRC-3C9E1A57` | official-local-enforcement-case | 上海职业培训机构违规培训与收费查处案例 | <https://rsj.sh.gov.cn/dzb/rsj/2025-12-18/aid/02-02.html> | `not-recorded` | 证明违规培训和收费风险可以发生；不把所有收费培训、考试或证书概括为骗局 |
| `SRC-6D1A9E43` | official-occupation-explanation | 上海市政府关于长期照护师与既有护理资格的说明 | <https://www.shanghai.gov.cn/nw4411/20251224/c8c3d4aa259f4f9fb9a4311b20f215ca.html> | `not-recorded` | 只核对新职业定位及旧养老护理员、医疗护理员等证书继续有效；不证明岗位、待遇或职责已经完成现实转换 |
| `SRC-9E4B7C16` | official-local-policy-material | 上海养老服务人员队伍政策材料中对低收入、高强度、高流动等问题的概括 | <https://www.shanghai.gov.cn/jcsfbylfw/20240618/958a1eb262f141bf8a3ca8ca948ed7ac.html> | `not-recorded` | 只证明政策材料承认相关结构性困难；不替代上海全市工资、工时、伤害和离职率统计 |
| `SRC-7D3A9F26` | official-current-policy-qa | 上海医保局 2026-07-15 社区居家服务收费标准问答 | <https://ybj.sh.gov.cn/chxbmwd/20260715/913f3113dac34914a8d1be5c15db50e0.html> | `not-recorded` | 核对 40/65/80 元三类服务人员价格及中级以上养老护理员参照规则；服务收费不等于护理员到手工资 |
| `SRC-A1E6C5B8` | official-current-policy-qa | 上海医保局 2026-07-15 养老机构支付标准问答 | <https://ybj.sh.gov.cn/chxbmwd/20260715/1306ff012ac04ac790f2c94defe595e7.html> | `not-recorded` | 页面仍列 20/25/30 元／天；经 `SRC-3E7A1C95` 与 `SRC-D7F3A219` 交叉核对，确认为未同步 2025-09-01 调整的旧口径，不再用于现行计算 |
| `SRC-4B9D2E67` | official-local-agency-response | 上海医保局 2026-06-08 关于养老机构支付标准的提案答复 | <https://ybj.sh.gov.cn/jytabl2/20260803/9836a654e2e842ca82379f9891ce76b2.html> | `not-recorded` | 明确称机构标准已由 20/25/30 提高至 25/35/45 元／天；现由民政局年度材料与实施日期答复交叉确认，原通知全文仍待补 |
| `SRC-3E7A1C95` | author-provided-official-page-pdf | 上海市民政局《2025年度“养老答卷”》官方网页 PDF 副本 | [`../06_Current_Round_Source_Notes/2026-08-31_上海长护险支付调整成本模型与十条招聘样本核对.md`](../06_Current_Round_Source_Notes/2026-08-31_上海长护险支付调整成本模型与十条招聘样本核对.md) | `a7e8d991eaa6df4f04a2de0f339e4f59b71037948b957e4aa13272aae3caf7d5` | 核对 2025 年长护险机构标准已由 20/25/30 调整为 25/35/45，并提供全市养老服务总量；网页 PDF 未写生效日期，不单独用于确定时点或单位成本 |
| `SRC-D7F3A219` | official-local-agency-response | 上海市民政局关于认知障碍照护支付的政协提案答复 | <https://mzj.sh.gov.cn/MZ_zhuzhan2595_0-2-8-2593/20260608/f4d9f23719494eed9845c0269fd09609.html> | `not-recorded` | 明确机构照护支付标准于 2025-09-01 上调；与 `SRC-3E7A1C95`、`SRC-4B9D2E67` 合用以解决实施时点，不把提案答复当作原通知替代件 |
| `SRC-6B2D8F41` | author-provided-cost-model | 民办普惠养护院成本测算 Markdown | [`../06_Current_Round_Source_Notes/2026-08-31_上海长护险支付调整成本模型与十条招聘样本核对.md`](../06_Current_Round_Source_Notes/2026-08-31_上海长护险支付调整成本模型与十条招聘样本核对.md) | `803c8c201da3c6478846ccbcd3b144b435790053c3dd0243e87d8849b037e616` | 25/35/45 的政策算术可与官方来源交叉核对；成本占比、固定成本、入住率、工资和利润均为无底稿候选假设，不作行业事实 |
| `SRC-9C4E1A73` | author-provided-cost-model | 居家定点护理站成本测算 Markdown | [`../06_Current_Round_Source_Notes/2026-08-31_上海长护险支付调整成本模型与十条招聘样本核对.md`](../06_Current_Round_Source_Notes/2026-08-31_上海长护险支付调整成本模型与十条招聘样本核对.md) | `eb70fb023e6e4d8caa4db84a3939f1feb81f588e3ce546cd1061c8071d06cafc` | 40/65/80 服务价格和 90/10 支付可与官方来源交叉核对；成本占比、护士配置、场地、提成、工单密度和利润均待账目、许可与机构复核 |
| `SRC-2F8C5D16` | author-provided-recruitment-page-pdf | 上海莲润科技养老护理／长护险招聘页面 PDF | [`../07_Validation_Records/External_Validation_Plans/40岁转行_上海长护险招聘样本表.md`](../07_Validation_Records/External_Validation_Plans/40岁转行_上海长护险招聘样本表.md) | `fdb4ec93829b6ca2024f86d08b4c0c6ecdb23a3390b7c7aa780542d2a2da895f` | 只作 2026-08-31 保存的招聘宣传样本；养老院、医院、住家与长护险方向混列，工资、单量、保险、培训和实际用工须分别核验 |
| `SRC-7A1E6B94` | author-provided-recruitment-page-pdf | 上海抚理健康徐汇长护险护理员招聘页面 PDF | [`../07_Validation_Records/External_Validation_Plans/40岁转行_上海长护险招聘样本表.md`](../07_Validation_Records/External_Validation_Plans/40岁转行_上海长护险招聘样本表.md) | `27420cf033082869bcc113d4f799c9c44b874275eab70fda46efaebd758f1a0d` | 只作广告字段样本；与同企业其他地区页面不按独立雇主累计，工资、单量、社保和实际录用未验证 |
| `SRC-4D9C2F68` | author-provided-recruitment-page-pdf | 上海抚理健康浦东长护险护理员招聘页面 PDF | [`../07_Validation_Records/External_Validation_Plans/40岁转行_上海长护险招聘样本表.md`](../07_Validation_Records/External_Validation_Plans/40岁转行_上海长护险招聘样本表.md) | `b6cafdde12a72642625c7e9336f6a7a4a74a63a30b37e57fa8a8d92d18582ce2` | 只作广告字段样本；与同企业其他地区页面不按独立雇主累计，工资、单量、社保和实际录用未验证 |
| `SRC-B3E7A521` | author-provided-recruitment-page-pdf | 上海抚理健康黄浦长护险护理员招聘页面 PDF | [`../07_Validation_Records/External_Validation_Plans/40岁转行_上海长护险招聘样本表.md`](../07_Validation_Records/External_Validation_Plans/40岁转行_上海长护险招聘样本表.md) | `7ece3572da9c6ae973688903c5e6c32f2d4f746b30de9c95c16418eb2e0190bd` | 只作广告字段样本；与同企业其他地区页面不按独立雇主累计，福利标签和岗位承诺须由合同核验 |
| `SRC-8F2D6C47` | author-provided-recruitment-page-pdf | 上海卓胜讯“5000—15000、培训提供宿舍”招聘页面 PDF | [`../07_Validation_Records/External_Validation_Plans/40岁转行_上海长护险招聘样本表.md`](../07_Validation_Records/External_Validation_Plans/40岁转行_上海长护险招聘样本表.md) | `6c02e14766e129b876bf8f8a2a86ae720abd03098536a461e070c4ddab736c96` | 标题、页面薪资和正文上限不一致；养老院、医院、住家与长护险方向混列，只作待核招聘宣传 |
| `SRC-1C9A4E75` | author-provided-recruitment-page-pdf | 上海卓胜讯“全市就近分配”长护险护理员招聘页面 PDF | [`../07_Validation_Records/External_Validation_Plans/40岁转行_上海长护险招聘样本表.md`](../07_Validation_Records/External_Validation_Plans/40岁转行_上海长护险招聘样本表.md) | `dc13445536a2676dbbdc1fad51a90dc5ae950db598b8965daaa32ac0e7fe6b57` | 只作同一企业的第二个岗位广告版本；不得与另一版本相加推算企业需求或工资分布 |
| `SRC-5E3B8D12` | author-provided-recruitment-page-pdf | 上海抚理健康长宁长护险护理员招聘页面 PDF | [`../07_Validation_Records/External_Validation_Plans/40岁转行_上海长护险招聘样本表.md`](../07_Validation_Records/External_Validation_Plans/40岁转行_上海长护险招聘样本表.md) | `e39ec19c57ab59ba91019bd96f1d5ee54e12ef60f7b2c07570a748f2ddf9463d` | 只作广告字段样本；页面要求 1—2 年经验和高中学历，不证明同企业全市统一门槛 |
| `SRC-A7C2F691` | author-provided-recruitment-page-pdf | 康伴夕阳长护险白班护理员招聘页面 PDF | [`../07_Validation_Records/External_Validation_Plans/40岁转行_上海长护险招聘样本表.md`](../07_Validation_Records/External_Validation_Plans/40岁转行_上海长护险招聘样本表.md) | `17e8ddae64bf682893a6ccb5313fb128bb77f2be724267b88fa0b55fdc751bf6` | 40—50 元/小时、7—9 单及 8000—15000 元均为广告声称；服务收费、计费工时、劳动报酬、通勤、休息和社保须拆开核验 |
| `SRC-6D4A9E23` | author-provided-recruitment-page-pdf | 黑丫家政长期照护师招聘页面 PDF | [`../07_Validation_Records/External_Validation_Plans/40岁转行_上海长护险招聘样本表.md`](../07_Validation_Records/External_Validation_Plans/40岁转行_上海长护险招聘样本表.md) | `64c5d1fb892e579c3eac081979ae2a80a56d7f8015ed6f91613fba7a9b29e1c6` | 只作广告字段样本；“无经验也可”与“持证上岗”须由雇主解释，工资、工时和五险一金未验证 |
| `SRC-2A8F5C71` | author-provided-recruitment-page-pdf | 上海香香园长护险长白班护理员招聘页面 PDF | [`../07_Validation_Records/External_Validation_Plans/40岁转行_上海长护险招聘样本表.md`](../07_Validation_Records/External_Validation_Plans/40岁转行_上海长护险招聘样本表.md) | `f3349633e2ba9e3f6e0890efdc199720bb28cedbc422cdafc8185b867bd56583` | 40—50 元/小时、8—9 小时及 9000—15000 元为广告声称；未写证书与社保细节，不得反推实际准入和保障 |
| `SRC-C5B1E847` | author-provided-facility-price-photo | 松江社会福利院华康养老院收费展示照片 | [`../06_Current_Round_Source_Notes/2026-08-31_上海长护险支付调整成本模型与十条招聘样本核对.md`](../06_Current_Round_Source_Notes/2026-08-31_上海长护险支付调整成本模型与十条招聘样本核对.md) | `42243be2fc2f19cb362a9de59d9de4b81b76c35e67ab7aa03f6cef8474b5da90` | 只记录一处未注明拍摄日期的展示价：床位、护理和餐费；不证明当前价格、长护险抵扣、其他收费或全市代表性 |

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
