# AI 赋能 / AI-enabled delivery

本页按**成果归属**分为「公司工作实践」和「个人 AI 项目」。前者展示脱敏后的工作案例及通用化公开方案；后者展示我的独立工具与产品验证。每项另标明实际应用或验证状态。公开内容不包含客户身份、内部代码、业务规则或生产数据。\
This index separates **professional work** from **personal AI projects**. The first group contains an anonymized workplace case and a generalized public design; the second contains independent tools and product experiments. Each item states its implementation or validation status. Client identities, internal code, business rules, and production data are excluded.

## 公司工作实践 / AI at work

**脱敏与数据核查（2026-10-15）/ Redaction and data review:** 当前公开的批量修改案例及 [Agent Code & Test](https://github.com/popyun/agent-code-test) 仓库已核对。未发现客户或雇主标识、企业模板、内部源码、真实业务数据、非公开个人资料、凭证及私有路径；Agent 验证数据为合成状态。结论限于本次核查的公开版本。 / The published case and Agent repository were reviewed. No client or employer identifiers, organization-specific templates, proprietary source, real business data, private personal records, credentials, or private paths were found; Agent verification uses synthetic states. This finding is limited to the reviewed public versions.

| 实践 / Practice | 公开状态 / Visibility | 进度阶段 / Stage | 说明与证据 / Description and evidence |
| --- | --- | --- | --- |
| [批量程序修改与复核 / Batch program changes and review](../cases/ai-assisted-batch-change.md) | 公开脱敏案例 / Public anonymized case | 已在实际工作中应用；团队完成复核。 / Applied in professional work; team review completed. | 定义修改规则，借助 AI 实现批量工具，生成逐文件差异报告；[主页可展开全文](../README.md)。 / Defined rules, used AI to help build a batch tool, and produced file-by-file diffs. |
| [Agent Code & Test](https://github.com/popyun/agent-code-test) | 公开通用化仓库 / Public generalized repository | 产品规格 2.2 与可运行的逻辑参考模型；真实接入待实现。 / Specification 2.2 and executable logic reference model; real integrations remain unfinished. | 将需求、代码生成、检查、测试与修正组织为可追溯流程；[查看验证范围](https://github.com/popyun/agent-code-test/blob/main/docs/verification.md)。 / A traceable design for requirements, generation, checks, testing, and repair, with documented validation limits. |

工作中已应用的成果与尚未真实接入的方案分别标注。公开 Agent 仓库不代表雇主正式产品或生产部署。\
Applied work and designs without real integration are labelled separately. The public Agent repository is not presented as an official employer product or a production deployment.

## 个人 AI 项目 / Personal AI projects

公开与非公开项目并列展示；非公开项目只提供概述，不链接到私有仓库。 / Public and private projects appear together; private projects have descriptions but no repository links.

| 项目 / Project | 公开状态 / Visibility | 进度阶段 / Stage | 展示重点 / What it shows |
| --- | --- | --- | --- |
| [履历工作台（简历生成辅助） / Resume Workbench](../work/resume-workbench.md) | **非公开源码；公开概览 / Private source; public overview** | 本地 MVP 验证 / Local MVP validation | 将真实经历整理为待核对的证据，形成可编辑的岗位简历草稿。 / Turns career history into reviewable evidence and editable role-specific drafts. |
| [金融业务知识平台原型 / Financial workflow knowledge prototype](../work/financial-knowledge-prototype.md) | **非公开源码；公开概览 / Private source; public overview** | 原型验证 / Prototype validation | 用虚构基金场景连接需求、规则、版本与测试；语义检索和模型回答尚未完成。 / Connects requirements, rules, versions, and tests in a fictional fund workflow; semantic retrieval and model answers remain unfinished. |
| [Obsidian Knowledge Import Hub](https://github.com/popyun/knowledgeImportHub) | **公开仓库 / Public repository** | 本地可用、迭代中 / Locally runnable, evolving | 文档图像处理、人工复核与可追溯 Markdown 输出。 / Document-image processing, human review, and traceable Markdown output. |
| [Image-to-Markdown Skills](https://github.com/popyun/image-to-markdown-skills) | **公开仓库 / Public repository** | 工具迭代中 / Tool in iteration | 将图像转 Markdown 封装为可复用的工作流入口。 / Reusable image-to-Markdown workflows. |
| Chat Digest | **非公开 / Private** | 本地运行、迭代中 / Running locally, evolving | 保存个人 AI 对话的可追溯原始快照。 / Captures traceable snapshots of personal AI conversations. |
| Knowledge Compile | **非公开 / Private** | 规则与验证迭代 / Rules and validation iteration | 从原始资料建立可核对、带来源的知识条目；候选内容不直接发布。 / Builds source-linked, reviewable knowledge records; candidates are not published directly. |

我负责问题定义、流程设计、业务规则核对与结果复核；AI 辅助编写脚本、原型和文档。后续验证方向会在形成可检查的结果后补充，不作为当前成果列示。\
I define the problem, design the workflow, check business rules, and review results; AI assists with scripts, prototypes, and documentation. Future directions will appear as outcomes only after they have inspectable evidence.

[返回个人主页 / Back to profile](../README.md)

[浏览完整项目目录 / Browse the full project catalog](../projects/README.md)
