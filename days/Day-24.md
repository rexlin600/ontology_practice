# Day 24｜医疗运营：优先低风险高协同场景

## 今日目标

选择适合第一阶段落地的医疗运营用例。

## 核心概念

优先考虑随访、床位、耗材、预约、转诊、科研队列等运营协同；诊断建议不是首个交付。对象应贯彻最小必要数据、角色权限、审计和人工复核。

## 案例与 FDE 映射

公开医疗器械案例的重点是账户级运营信息和销售决策，并非临床诊断。[案例](https://www.palantir.com/docs/foundry/use-case-examples/effectively-adjusting-sales-and-marketing-pipelines-on-the-fly) FDE 应谨慎划定业务与临床边界。

## 实践

设计“高风险随访队列”：患者、就诊、任务、负责人对象；一个优先级规则；确认 Action；按时完成率指标。

## 复盘

哪些字段必须脱敏？谁可查看患者级明细？
