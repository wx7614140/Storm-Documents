# About

本项目是 Apache Storm 官方文档的中文翻译版，致力于为有实时流计算项目需求和对 Apache Storm 感兴趣的同学提供有价值的中文资料，希望能够对大家的工作和学习有所帮助。由于本人水平有限，翻译中仍然存在不少问题，还请大家不吝斧正。如果对本项目有任何问题，欢迎在本项目页面中提出，或者直接给本人发邮件（ivicoco at gmail.com），谢谢。

>说明：如果没有特殊声明，本项目文档中所述 Storm 版本均为 0.9.x 版本。

---

# Storm 官方文档索引

原文资料来源（官方网站）：[http://storm.apache.org/documentation/Documentation.html](http://storm.apache.org/documentation/Documentation.html)

---

## Storm 基础篇

- [Javadoc][1]<sup>1</sup>
- [基础概念][2]
- [配置][3]
- [消息的可靠性保障][4]
- [容错性][5]
- [命令行操作][6]
- [理解 Storm 拓扑的并行度(parallelism)概念][7]
- [FAQ][8]

---

## Trident

> _`Trident` 是 Storm 的一种高级操作接口，它能够提供可靠的数据流一次性处理模式、“事务型”数据持久化存储功能以及一系列数据流分析操作通用组件。_

- [Trident 教程 —— 基本概念与参考手册][9]
- [Trident API 概述 —— 数据的转换与整合操作][10]
- [Trident State —— 恰好一次的数据处理与快速、持久化的聚合操作][11]
- [Trident Spouts —— 事务型与非事务型数据入口][12]

---

## 配置与部署

- [配置 Storm 集群][13]
- [本地模式][14]
- [问题与解决][15]
- [在生产环境中运行 topology][16]
- [使用 Maven 构建 Storm 应用][17]

---

## Storm 中级篇

- [序列化][18]
- [常用模式][19]
- Clojure DSL<sup>2</sup>
- 使用非 JVM 语言开发
- [分布式 RPC][22]<sup>3</sup>
- 事务型拓扑<sup>4</sup>
- [Storm 与 Kestrel][24]
- 直接数据流组<sup>5</sup>
- [Hooks][26]
- [Metrics][27]
- Trident tuple 的生命周期<sup>5</sup>

---

## Storm 高级篇

- 为 Storm 定义非 JVM 语言 DSL
- 多语言接口协议（如何为其他语言定义接口）
- [技术实现相关文档][31]

---

>## 说明  
<sup>1</sup> JavaDoc 暂时不在翻译计划之中。  
<sup>2</sup> 由于译者对 Clojure 不是很熟悉，相关内容暂时不提供翻译。  
<sup>3</sup> 由于官方文档关于分布式 RPC 的部分内容已过时，这里重写了相关内容。  
<sup>4</sup> 事务型拓扑已经由 Trident 实现，之前的实现已经被标记为 `@Deprecated`，这里不再讨论。  
<sup>5</sup> 该文官方文档暂未提供。  


[1]: http://storm.apache.org/javadoc/apidocs/index.html
[2]: https://github.com/weyo/Storm-Documents/blob/master/Manual/zh/Concepts.md
[3]: https://github.com/weyo/Storm-Documents/blob/master/Manual/zh/Configuration.md
[4]: https://github.com/weyo/Storm-Documents/blob/master/Manual/zh/Guaranteeing-Message-Processing.md
[5]: https://github.com/weyo/Storm-Documents/blob/master/Manual/zh/Fault-Tolerance.md
[6]: https://github.com/weyo/Storm-Documents/blob/master/Manual/zh/Command-Line-Client.md
[7]: https://github.com/weyo/Storm-Documents/blob/master/Manual/zh/Understanding-The-Parallelism-Of-A-Storm-Topology.md
[8]: https://github.com/weyo/Storm-Documents/blob/master/Manual/zh/FAQ.md
[9]: https://github.com/weyo/Storm-Documents/blob/master/Manual/zh/Trident-Tutorial.md
[10]: https://github.com/weyo/Storm-Documents/blob/master/Manual/zh/Trident-API-Overview.md
[11]: https://github.com/weyo/Storm-Documents/blob/master/Manual/zh/Trident-State.md
[12]: https://github.com/weyo/Storm-Documents/blob/master/Manual/zh/Trident-Spouts.md
[13]: https://github.com/weyo/Storm-Documents/blob/master/Manual/zh/Setting-Up-A-Storm-Cluster.md
[14]: https://github.com/weyo/Storm-Documents/blob/master/Manual/zh/Local-Mode.md
[15]: https://github.com/weyo/Storm-Documents/blob/master/Manual/zh/Troubleshooting.md
[16]: https://github.com/weyo/Storm-Documents/blob/master/Manual/zh/Running-Topologies-On-A-Production-Cluster.md
[17]: https://github.com/weyo/Storm-Documents/blob/master/Manual/zh/Building-Storm-With-Maven.md
[18]: https://github.com/weyo/Storm-Documents/blob/master/Manual/zh/Serialization.md
[19]: https://github.com/weyo/Storm-Documents/blob/master/Manual/zh/Common-Topology-Patterns.md

[22]: https://github.com/weyo/Storm-Documents/blob/master/Manual/zh/Distributed-RPC.md

[24]: https://github.com/weyo/Storm-Documents/blob/master/Manual/zh/Storm-and-Kestrel.md

[26]: https://github.com/weyo/Storm-Documents/blob/master/Manual/zh/Hooks.md
[27]: https://github.com/weyo/Storm-Documents/blob/master/Manual/zh/Metrics.md

[31]: https://github.com/weyo/Storm-Documents/blob/master/Manual/zh/Storm-Internal-Implementation.md
