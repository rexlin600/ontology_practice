# Day 06｜数据映射：从源表到业务对象

## 今日目标

设计最小、可追溯的数据映射。

## 核心概念

Ontology 建在数据和模型之上，不是源库镜像。先统一键值、清洗口径并评估刷新，再把真正支撑决策的结果映射为对象属性和链接。

## 案例与 FDE 映射

公开案例：消费品企业整合 7+ ERP 数据源，构建从供应商到客户的价值链数字孪生，业务人员围绕工厂、SKU、客户操作，而非查询 ERP 表。[案例](https://www.palantir.com/docs/foundry/use-case-examples/optimizing-production-with-erp-data-across-the-supply-chain) FDE 应解释为何先做高价值链路。

## 实践

建一张映射表：源表/字段、转换、目标对象/属性、质量规则、刷新、负责人。标出一个“源数据迟到便禁止 Action”的条件。

## 复盘

若一个源系统停更一天，哪个决定会变得不可信？
