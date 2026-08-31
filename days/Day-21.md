# Day 21｜AIP：AI 必须进入受控工作流

## 今日目标

区分 AI 的建议能力和业务授权。

## 核心概念

AIP 用于将 AI 连接到组织数据和运营流程，可在 Ontology 与开发工具链上构建工作流、Agent、函数和评估。[来源](https://www.palantir.com/docs/foundry/aip) AI 不应绕开权限和 Action 直接改变现实。

## 案例与 FDE 映射

教学推演：采购 Agent 总结中断证据并提出替代方案，但只能提交建议，不能直接下单；下单仍须经有权限的人执行 Action。FDE 要明确自动化边界。

## 实践

写 Agent 边界卡：可读对象、不可读字段、允许工具、禁止 Action、人工批准点、失败降级策略。

## 复盘

没有 LLM 时流程是否仍能运行？AI 的增量价值是什么？
