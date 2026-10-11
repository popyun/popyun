# 履历工作台（简历生成辅助） / Resume Workbench

**性质与归属 / Nature and ownership:** 个人独立开发、在本机运行的求职辅助 MVP；不属于公司项目。当前公开的是产品与验证概览，源码、个人履历和岗位记录未公开。\
**Nature and ownership:** An independently developed, locally run job-search assistant MVP, separate from my professional work. This is a public product and validation overview; the source code, personal career history, and job records are private.

## 要解决的问题 / Problem

真实经历分散在任职、项目和个人笔记中。面对不同岗位，如果直接让 AI 改写简历，容易混淆本人贡献、团队成果和未经核对的数字。我希望先把经历整理成可核对的证据，再形成针对岗位的表达。\
Career facts are scattered across roles, projects, and notes. Direct AI rewriting can blur personal contributions, team outcomes, and unverified figures. The workbench first organizes reviewable evidence, then uses it to draft for a specific role.

## 我做了什么 / My contribution

- 设计从经历录入、事实核对、求职方向、职位要求到简历版本和投递反馈的产品流程。\
  Designed the product flow from career capture and fact review to target roles, job requirements, resume versions, and application feedback.
- 将 AI 用于用户主动触发的追问、整理和表达建议；候选内容可编辑，关键经历需本人确认后才能进入自动简历草稿。\
  Used AI for user-initiated questions, structuring, and wording suggestions; candidates remain editable, and key experience must be confirmed before it enters an automatically assembled draft.
- 借助 AI 完成部分实现，并通过虚构资料的隔离测试核对生成、保存、导出和恢复等流程。\
  Used AI to assist implementation and checked generation, saving, export, and recovery flows with isolated fictional data.

## 当前状态与边界 / Status and limits

本地 MVP 已有通用简历、针对具体职位的专用简历、可编辑版本与反馈记录流程，当前重点验证国内全职求职场景。实际投递效果仍需要积累真实反馈；英语及海外场景有基础入口，尚不计入本轮完成范围。工具不自动搜索或投递岗位，也不预测面试机会。\
The local MVP includes general and job-specific resume flows, editable versions, and application feedback records. Current validation focuses on domestic full-time roles. Real application outcomes still require feedback; English and overseas paths have basic entry points but are outside this MVP's acceptance scope. The tool does not automatically search or apply for jobs or predict interview chances.

完整源码、运行环境与私人资料未公开，因此访客无法独立复现本地验证。这里展示的是我的产品拆解、AI 使用边界与验证方法，不将本地测试等同于公开上线。\
The full source, runtime, and personal data are private, so visitors cannot independently reproduce the local checks. This overview shows my product reasoning, boundaries for AI use, and validation method; local tests are not presented as a public deployment.

[返回个人主页 / Back to profile](../README.md) · [AI 赋能专题 / AI practice index](../ai/README.md)
