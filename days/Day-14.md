# Day 14｜Function-backed Action：跨对象事务

## 今日目标

设计一次完成多对象变更的可靠操作。

## 核心概念

复杂编辑函数要配置成 Action 才能在运营上下文写入、配置权限和元数据。[来源](https://www.palantir.com/docs/foundry/action-types/function-actions-getting-started) 需要考虑校验、幂等、失败与补偿。

## 案例与 FDE 映射

教学推演：`处理缺货预警` 更新订单优先级、创建采购任务、链接替代 SKU、通知负责人。它必须避免重复点击产生双份采购。

## 实践

画状态机：草稿→校验→执行→成功/失败→人工复核。列出每一步的输入、写入和审计字段。

## 复盘

哪些外部副作用无法回滚？应如何补偿？
