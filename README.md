# Database Optimization Notes

这个仓库用于整理数据库优化学习内容，重点关注可复用的分析方法、SQL 调优思路、索引设计、执行计划阅读、事务与锁、表结构设计、监控诊断和实际案例复盘。

## 学习路线

建议按下面顺序学习和补充笔记：

1. [数据库优化总览](docs/00-overview.md)
2. [SQL 执行与执行计划](docs/01-query-execution-and-explain.md)
3. [索引设计与使用](docs/02-indexing.md)
4. [SQL 改写与查询调优](docs/03-sql-tuning.md)
5. [事务、锁与并发控制](docs/04-transactions-locks-concurrency.md)
6. [表结构与数据模型优化](docs/05-schema-design.md)
7. [监控、诊断与性能基线](docs/06-monitoring-diagnosis.md)
8. [优化案例库](cases/README.md)

## 仓库结构

```text
.
|-- docs/                 # 系统化学习笔记
|-- cases/                # 真实或模拟优化案例复盘
|-- experiments/          # 实验脚本、压测记录和结论
|-- templates/            # 记录模板
`-- README.md
```

## 记录原则

- 先描述现象，再给出证据，最后写结论。
- 每次优化都记录优化前后的执行计划、耗时、扫描行数和影响范围。
- 区分通用原则和具体数据库实现差异，例如 MySQL、PostgreSQL、SQL Server、Oracle。
- 不只记录“怎么做”，还要记录“为什么这样做”和“不适用的场景”。

## 快速模板

新增优化案例时，可以复制 [案例复盘模板](templates/case-study-template.md)。
