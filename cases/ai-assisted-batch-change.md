# 批量程序修改与复核 / Batch program changes and review

> 脱敏职业案例。只说明个人工作方法和团队复核方式，不展示客户、内部代码或具体业务规则。\
> An anonymized account of my work and the team's review process. Client details, internal code, and business rules are omitted.

**分类 / Category:** 公司工作实践；不代表雇主的官方项目说明。 / Professional work practice; not an official statement by the employer.

## 问题 / Problem

同类修改分散在大量程序文件中。逐个修改需要重复操作，完成后仍须检查每个文件的结果。\
A similar change was needed across many program files. Editing each file manually required repetitive work, and each result still needed review.

## 我的行动 / My contribution

我梳理修改规则，借助 AI 编写并执行批量处理脚本，使用 WinMerge 生成差异报告，让复核人员能逐文件检查实际改动。\
I defined the change rules, used AI to help build and run a batch script, and generated WinMerge diff reports for file-by-file review.

## 团队复核与结果 / Team review and outcome

团队对修改结果进行了逐文件复核。批量工具减少了重复的手工修改步骤，但没有省去必要的检查；复核是团队工作，我负责规则、工具与执行。具体规模和工时口径暂不公开。\
The team reviewed the changed files individually. The batch tool reduced repetitive manual edits while preserving the necessary checks. I owned the rules, tool, and execution; review was a team contribution. Scale and time figures are withheld from this public account.

## 体现的工作方法 / What this illustrates

识别可规则化的重复任务，把 AI 用于工具实现，并用差异报告和人工复核控制批量变更的质量。\
Identify repetitive work with explicit rules, use AI to help build the tool, and control the quality of batch changes through diffs and human review.

[返回主页 / Back to profile](../README.md)

[AI 赋能专题 / AI practice index](../ai/README.md)
