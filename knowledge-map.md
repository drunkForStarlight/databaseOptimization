# 知识地图

这个文件作为知识库总索引，用来把分散的笔记、问题、案例和实验串起来。

## 优化方法论

- [数据库优化总览](docs/00-overview.md)
- [监控、诊断与性能基线](docs/06-monitoring-diagnosis.md)

## SQL 与执行计划

- [SQL 执行与执行计划](docs/01-query-execution-and-explain.md)
- [SQL 改写与查询调优](docs/03-sql-tuning.md)

待补充：

- 如何阅读 MySQL `EXPLAIN`。
- 如何阅读 PostgreSQL `EXPLAIN ANALYZE`。
- 执行计划为什么会变化。

## 索引

- [索引设计与使用](docs/02-indexing.md)
- [WHERE 条件怎么影响索引使用？](questions/how-where-affects-index-usage.md)

待补充：

- B+ 树索引。
- 联合索引最左前缀。
- 覆盖索引。
- 索引下推。
- 索引选择性。

## 事务、锁与并发

- [事务、锁与并发控制](docs/04-transactions-locks-concurrency.md)

待补充：

- MVCC。
- 间隙锁。
- 死锁分析。
- 长事务影响。

## 表结构与数据模型

- [表结构与数据模型优化](docs/05-schema-design.md)

待补充：

- 字段类型选择。
- 冷热数据拆分。
- 分区表。
- 范式与反范式。

## 问题驱动入口

- [为什么 SQL 会慢？](questions/why-is-sql-slow.md)
- [为什么加了索引还是慢？](questions/why-index-does-not-work.md)
- [WHERE 条件怎么影响索引使用？](questions/how-where-affects-index-usage.md)

## 案例与实验

- [优化案例库](cases/README.md)
- [实验记录](experiments/README.md)
