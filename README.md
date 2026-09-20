# TreeLaw

<p align="center">
  <img src="assets/treelaw-readme-header.png" alt="TreeLaw 中国法律智能体技能库" width="100%">
</p>

**十年以上执业律师水平的中国法律智能体。**<br>
212 个由执业法律专业人员手写并验证的法律智能体技能（Agent Skills），覆盖诉讼律师、非诉律师、常年法律顾问和企业合规团队，贯穿检索 → 推理 → 论证 → 文书 → 交付的完整链条。

A curated library of 212 hand-crafted, lawyer-verified legal agent skills for Chinese legal practice, covering litigation lawyers, transactional lawyers, general counsel, and corporate compliance teams.

[技能总览](#skill-index) · [设计理念](#自主编排的法律智能体) · [评测覆盖](#真实律师工作流打磨) · [使用方式](https://treelaw.top) · [贡献技能](https://treelaw.top)

<p align="center">
  <a href="https://treelaw.top">
    <img src="assets/skill-index/button-start-using.png" alt="开始使用 TreeLaw" width="520">
  </a>
</p>

TreeLaw 不是一个泛用聊天机器人。它是面向中国法律实务构建的法律 Agent，把诉讼律师、非诉律师、常年法律顾问和企业合规团队的工作流，拆成可执行、可核验、可交付的专业技能。

[访问官网](https://treelaw.top) · [开始使用](https://treelaw.top) · [Skill（技能）](https://treelaw.top)

## Skill Index

TreeLaw 的核心不是“回答法律问题”，而是把中国律师真实工作中的判断、检索、核验、起草、复核和交付拆成可编排的 Skills。

下面是当前公开展示的一部分 TreeLaw Skills。每个 Skill 都可以在 TreeLaw Agent 中被组合、调用，并与文件读取、OCR、法律检索、文书生成和人工确认环节衔接。

<p align="center">
  <img src="assets/skill-index/skills-distribution-pie.png" alt="TreeLaw Skills 分布饼图" width="100%">
</p>

<p>
  <img src="assets/skill-index/section-01.png" alt="法律检索与依据核验" width="560">
</p>

> **理论依据** IRAC 争点分析、请求权基础检索、类案检索、法条体系解释、裁判规则归纳、法律依据可追溯核验。

<p><a href="https://treelaw.top"><img src="assets/skill-index/skill-case-issue-decomposition.png" alt="case-issue-decomposition"></a></p>

把案件事实拆成可检索的争点、要件和抗辩路径。

<p><a href="https://treelaw.top"><img src="assets/skill-index/skill-statute-authority-verification.png" alt="statute-authority-verification"></a></p>

围绕国家法律法规、司法解释、部门规章和裁判规则核验依据。

<p><a href="https://treelaw.top"><img src="assets/skill-index/skill-known-case-number-check.png" alt="known-case-number-check"></a></p>

根据案号、法院、当事人和裁判要旨核验已知案例。

<p><a href="https://treelaw.top"><img src="assets/skill-index/skill-favorable-case-retrieval.png" alt="favorable-case-retrieval"></a></p>

寻找同争点、同法院层级或同地区裁判倾向下的有利案例。

<p><a href="https://treelaw.top"><img src="assets/skill-index/skill-adverse-authority-mapping.png" alt="adverse-authority-mapping"></a></p>

主动整理不利观点、不利案例和对方可能引用的材料。

<p><a href="https://treelaw.top"><img src="assets/skill-index/skill-citation-source-audit.png" alt="citation-source-audit"></a></p>

对输出中的法条、案例和政策依据做可追溯核查。

<p>
  <img src="assets/skill-index/section-02.png" alt="事实证据与材料处理" width="560">
</p>

> **理论依据** 证据三性、证明责任分配、事实要件映射、材料索引、OCR 来源追踪、矛盾事实比对。

<p><a href="https://treelaw.top"><img src="assets/skill-index/skill-fact-evidence-indexing.png" alt="fact-evidence-indexing"></a></p>

把事实、证据、证明目的和页码来源整理成可复核目录。

<p><a href="https://treelaw.top"><img src="assets/skill-index/skill-ocr-source-tracing.png" alt="ocr-source-tracing"></a></p>

扫描件 OCR 后保留原文、页码和字段来源，便于人工确认。

<p><a href="https://treelaw.top"><img src="assets/skill-index/skill-evidence-chain-mapping.png" alt="evidence-chain-mapping"></a></p>

按法律要件建立证据链，识别证明缺口和补强方向。

<p><a href="https://treelaw.top"><img src="assets/skill-index/skill-contradiction-spotting.png" alt="contradiction-spotting"></a></p>

比对合同、流水、聊天记录和陈述中的冲突信息。

<p><a href="https://treelaw.top"><img src="assets/skill-index/skill-pleading-fact-extraction.png" alt="pleading-fact-extraction"></a></p>

从材料中抽取起诉状、答辩状和法律意见书所需事实。

<p>
  <img src="assets/skill-index/section-03.png" alt="诉讼策略与文书生成" width="560">
</p>

> **理论依据** 请求权基础、诉讼请求设计、举证责任、程序节点、庭审争点整理、救济路径规划。

<p><a href="https://treelaw.top"><img src="assets/skill-index/skill-litigation-strategy-map.png" alt="litigation-strategy-map"></a></p>

从请求权基础、举证责任、程序节点和诉讼目标生成策略图。

<p><a href="https://treelaw.top"><img src="assets/skill-index/skill-complaint-drafting.png" alt="complaint-drafting"></a></p>

根据案件台账和证据结构生成民事起诉状。

<p><a href="https://treelaw.top"><img src="assets/skill-index/skill-defense-and-counterclaim.png" alt="defense-and-counterclaim"></a></p>

组织答辩意见、反诉路径和抗辩要点。

<p><a href="https://treelaw.top"><img src="assets/skill-index/skill-preservation-application.png" alt="preservation-application"></a></p>

生成财产保全、证据保全和行为保全申请材料。

<p><a href="https://treelaw.top"><img src="assets/skill-index/skill-hearing-outline-generation.png" alt="hearing-outline-generation"></a></p>

整理庭审提纲、发问清单、质证意见和争点回应。

<p><a href="https://treelaw.top"><img src="assets/skill-index/skill-judgment-remedy-planning.png" alt="judgment-remedy-planning"></a></p>

评估上诉、再审、执行和和解路径。

<p>
  <img src="assets/skill-index/section-04.png" alt="合同审查与交易文件" width="560">
</p>

> **理论依据** 交易结构还原、合同目的解释、权利义务配置、违约责任设计、风险分配、商业谈判可执行性。

<p><a href="https://treelaw.top"><img src="assets/skill-index/skill-transaction-structure-analysis.png" alt="transaction-structure-analysis"></a></p>

先识别交易结构、主体关系和履约路径，再审条款。

<p><a href="https://treelaw.top"><img src="assets/skill-index/skill-contract-risk-review.png" alt="contract-risk-review"></a></p>

按客户立场审查付款、交付、验收、违约、解除和争议解决。

<p><a href="https://treelaw.top"><img src="assets/skill-index/skill-redline-clause-suggestion.png" alt="redline-clause-suggestion"></a></p>

给出可替换条款、红线修改意见和谈判口径。

<p><a href="https://treelaw.top"><img src="assets/skill-index/skill-missing-clause-check.png" alt="missing-clause-check"></a></p>

识别缺失条款、冲突条款和表述不确定条款。

<p><a href="https://treelaw.top"><img src="assets/skill-index/skill-counterparty-risk-screen.png" alt="counterparty-risk-screen"></a></p>

围绕主体资格、授权链条、履约能力和监管风险做初筛。

<p><a href="https://treelaw.top"><img src="assets/skill-index/skill-negotiation-playbook.png" alt="negotiation-playbook"></a></p>

把审查意见转化为可执行的谈判优先级。

<p>
  <img src="assets/skill-index/section-05.png" alt="批量诉讼与金融案件" width="560">
</p>

> **理论依据** 标准化台账、OCR 人工确认、金融借款/担保/还款事实核验、模板化文书生成、批量质量控制。

<p><a href="https://treelaw.top"><img src="assets/skill-index/skill-batch-litigation-intake.png" alt="batch-litigation-intake"></a></p>

从合同、扫描件、流水和还款记录中批量生成标准台账。

<p><a href="https://treelaw.top"><img src="assets/skill-index/skill-ledger-human-review.png" alt="ledger-human-review"></a></p>

生成可视化核验页，让实习生或律师确认关键字段。

<p><a href="https://treelaw.top"><img src="assets/skill-index/skill-repayment-interest-check.png" alt="repayment-interest-check"></a></p>

核对本金、利息、罚息、逾期金额和律师费。

<p><a href="https://treelaw.top"><img src="assets/skill-index/skill-template-document-filling.png" alt="template-document-filling"></a></p>

把确认台账填入起诉状、委托书、条件表和证据目录模板。

<p><a href="https://treelaw.top"><img src="assets/skill-index/skill-evidence-binder-production.png" alt="evidence-binder-production"></a></p>

批量生成证据目录、附件清单和可追溯材料包。

<p><a href="https://treelaw.top"><img src="assets/skill-index/skill-batch-output-qc.png" alt="batch-output-qc"></a></p>

检查主体、金额、日期、案由和模板字段是否一致。

<p>
  <img src="assets/skill-index/section-06.png" alt="常年法律顾问与企业合规" width="560">
</p>

> **理论依据** 企业法律问题分诊、制度治理、授权链条、劳动用工、数据合规、公司治理和业务风险闭环。

<p><a href="https://treelaw.top"><img src="assets/skill-index/skill-general-counsel-triage.png" alt="general-counsel-triage"></a></p>

把日常法律问题分流到合同、劳动、公司治理、合规或诉讼路径。

<p><a href="https://treelaw.top"><img src="assets/skill-index/skill-compliance-gap-assessment.png" alt="compliance-gap-assessment"></a></p>

围绕业务流程识别制度、授权、数据、用工和监管缺口。

<p><a href="https://treelaw.top"><img src="assets/skill-index/skill-policy-drafting.png" alt="policy-drafting"></a></p>

生成制度、流程、通知、函件和内部合规文件初稿。

<p><a href="https://treelaw.top"><img src="assets/skill-index/skill-labor-and-data-compliance.png" alt="labor-and-data-compliance"></a></p>

处理劳动用工、个人信息保护和数据出境相关问题。

<p><a href="https://treelaw.top"><img src="assets/skill-index/skill-company-governance-check.png" alt="company-governance-check"></a></p>

核查股东会、董事会、授权、印章和内部审批规则。

<p><a href="https://treelaw.top"><img src="assets/skill-index/skill-board-resolution-review.png" alt="board-resolution-review"></a></p>

审查或生成决议、会议纪要和授权文件。

<p>
  <img src="assets/skill-index/section-07.png" alt="法律意见书与专题研究" width="560">
</p>

> **理论依据** 法律意见书结构、事实与问题分离、依据检索、风险矩阵、管理层决策表达。

<p><a href="https://treelaw.top"><img src="assets/skill-index/skill-legal-opinion-drafting.png" alt="legal-opinion-drafting"></a></p>

按事实、问题、依据、分析、结论和风险边界生成法律意见书。

<p><a href="https://treelaw.top"><img src="assets/skill-index/skill-regulatory-research.png" alt="regulatory-research"></a></p>

围绕行业监管、地方规则和最新政策生成专题研究。

<p><a href="https://treelaw.top"><img src="assets/skill-index/skill-risk-matrix-generation.png" alt="risk-matrix-generation"></a></p>

把法律风险转化为概率、影响、依据和整改动作矩阵。

<p><a href="https://treelaw.top"><img src="assets/skill-index/skill-source-backed-memo.png" alt="source-backed-memo"></a></p>

输出带来源、适用条件和人工复核提示的研究备忘录。

<p><a href="https://treelaw.top"><img src="assets/skill-index/skill-executive-briefing.png" alt="executive-briefing"></a></p>

把复杂法律分析压缩成管理层可读的决策简报。

## 自主编排的法律智能体

TreeLaw 通过技能路由、工具调用、文件读取、OCR、法律检索、引用核验和文书生成，把一个开放式法律任务拆成多个可复核步骤。它强调的是“律师能接着用的结果”，而不是单轮问答。

<p align="center">
  <img src="assets/treelaw-agent-workflow.png" alt="TreeLaw 法律智能体核心技术流程" width="100%">
</p>

## 真实律师工作流打磨

TreeLaw 的技能体系来自真实法律工作，而不是只把法律文本塞进模型。

- 200+ 专家技能，覆盖诉讼、非诉、合同、合规、常年法律顾问和企业自查。
- 两家红圈所、三家精品所律师参与使用、反馈和实务打磨。
- 全国 26 座城市的律师用户已经参与使用与测试。
- 上千名律师正在进入 TreeLaw 的真实工作流测试。
- 已有真实案件中，律师借助 TreeLaw 的类案检索和引用核验定位有利案例，并转化为诉讼论证材料。
- 经验来源覆盖中关村学院、北京理工大学、天津大学、厦门大学法学院，以及红圈所、精品所和地方律协相关实践。

<p align="center">
  <img src="assets/treelaw-market-trust.png" alt="TreeLaw 市场真实反馈" width="100%">
</p>

## 参与测试 / 提交技能

如果你对中国法律 AI 感兴趣，或者希望 TreeLaw 支持你的真实法律工作流，可以从官网开始使用并加入内测。请不要在公开仓库中粘贴客户姓名、合同正文、身份证号、案号、手机号、商业秘密或其他敏感信息。

<p>
  <a href="https://treelaw.top">
    <img src="assets/skill-index/button-submit-workflow.png" alt="Skill（技能）" width="360">
  </a>
  <a href="https://treelaw.top">
    <img src="assets/skill-index/button-join-beta.png" alt="开始使用 TreeLaw" width="360">
  </a>
</p>

官网：[https://treelaw.top](https://treelaw.top)

## English Summary

TreeLaw is a China-focused legal AI agent designed around real lawyer workflows. It targets lawyer-level legal research, citation verification, contract review, litigation drafting, batch litigation document generation, source-backed legal reasoning, and human-in-the-loop review for Chinese legal practice.

Website: [https://treelaw.top](https://treelaw.top)
